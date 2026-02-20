# git-commands

🔹 1️⃣ List Branches
👉 Show local branches
git branch

👉 Show remote branches
git branch -r

👉 Show all (local + remote)
git branch -a

🔹 2️⃣ Create a New Branch
git branch branch_name


Example:

git branch feature-login

🔹 3️⃣ Switch to a Branch

Old method:

git checkout branch_name


New recommended method:

git switch branch_name

🔹 4️⃣ Create + Switch (One Command)
git checkout -b branch_name


OR

git switch -c branch_name

🔹 5️⃣ Rename a Branch

Rename current branch:

git branch -m new_name


Rename specific branch:

git branch -m old_name new_name

🔹 6️⃣ Delete a Branch

Safe delete:

git branch -d branch_name


Force delete:

git branch -D branch_name

🔹 7️⃣ Merge a Branch
git merge branch_name


Example:

git switch main
git merge feature-login

🔹 8️⃣ Push Branch to Remote (GitHub)
git push origin branch_name


Push and set upstream:

git push -u origin branch_name

🔹 9️⃣ Delete Remote Branch
git push origin --delete branch_name

