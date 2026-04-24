# (1) start

git fetch origin
git rebase origin/main

# (2) code

git commit

# (3) trước khi push

git fetch origin
git rebase origin/main

# (4) push

git push --force-with-lease

🚀 Best practice chuẩn hơn (nâng level)

# (1) Bắt đầu ngày → rebase

git fetch origin
git rebase origin/main

# (2) Code

git commit

# (3) Trước khi push → rebase

git fetch origin
git rebase origin/main

# (4) Push

git push --force-with-lease

# (5) Trước khi tạo PR → squash (1 lần duy nhất)

git rebase -i origin/main

# (6) Push lại sau squash

git push --force-with-lease
