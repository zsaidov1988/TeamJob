# TeamJob
https://zsaidov1988.github.io/TeamJob/

dev branchdan pull olib, yana shu branchga push qilasizlar

1. git init
2. git remote add origin https://github.com/zsaidov1988/TeamJob.git
3. git pull origin dev

O'zingizga yangi branch ochasiz: git checkout -b nameOfNewBranch

O'zgartirishlarni qilib bo'lib:

1. git pull origin dev
2. git push origin nameOfNewBranch # nameOfNewBranch - O'zingiz ochgan branch nomi

Keyin github ga kirib Pull request qilasiz va yangi ochgan branchingizdan dev branchiga pull request qilasiz

Keyinchalik har safar ish boshlashdan oldin:

1. git pull origin dev

Agar avval yaratgan branchingizni ishlatmoqchi bo'lsangiz: Branch bor yoki yo'qligini tekshirasiz:

1. git branch

Agar branch bo'lsa:

1. git branch BranchNomi

Agar branch ro'yxatda bo'lmasa yoki eski branchdan foydalanmay, yangi  branch ochib olmoqchi bo'lsangiz ham:

1. git checkout -b YangiBranchNomi

Keyin ishlarni qilasiz va:

1. git pull origin dev
2. git push origin YangiBranchNomi

Keyin github ga kirib Pull request qilasiz va yangi ochgan branchingizdan dev branchiga pull request qilasiz
