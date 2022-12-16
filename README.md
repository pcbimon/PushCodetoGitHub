**สำหรับเครื่องที่ติดError 407 proxy ให้ใช้คำสั่ง**
```git config --global http.proxy http://proxyuser:proxypwd@proxy.server.com:port```

**ขั้นตอนนำโปรเจ็คขึ้น git**
1. สร้าง git folder ในแฟ้ม Project

```git init```

2. เพิ่ม Github repository URL

```git remote add origin https://github.com/usr/repoitory```

3. เช็ค Github repository URL

```git remote -v```

4. pull ไฟล์ git ignore 

```git pull origin main```

5. เพิ่มไฟล์ที่มีอยู่ใน Project ทั้งหมด (ไฟล์ที่ถูก ignore จะไม่เพิ่มเข้าไป)

```git add .```

6. Commit เข้า Git

```git commit -m "First commit"```

7. Push เข้า Github

```git push origin main```
