# Pull Request Menggunakan Branch

## 1. Persiapan Repo

1. Buat remote repo baru di github
2. Undang collaborator
3. Clone remote repository

   ```bash
   git clone [url]
   ```

## 2. Membuat Commit Pada Branch Baru

1. Buat branch baru pada local repo

   ```bash
   # membuat branch
   git branch [nama-branch]

   # pindah ke branch
   git checkout [nama-branch]
   ```

2. Lakukan perubahan

3. Buat commit

   ```bash
   git add .
   git commit -m "keterangan commit"
   ```

4. Push ke remote menggunakan branch baru tersebut

   ```bash
   git push origin [nama-branch]
   ```

## 3. Melakukan pull request

1. Buat pull request ke master
2. Review tim
3. Terima pull request
4. Delete remote branch

## 4. Update Repo Local

1. Update commit master pada local branch dengan commit master pada remote branch yang sudah dilakukan pull request

   ```bash
   git pull origin master
   ```

2. Delete local branch

   ```bash
   git branch -D [nama-branch]
   ```
