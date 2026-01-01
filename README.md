# Merhaba Dünya Docker Projesi

Bu proje Docker kullanarak basit bir HTML sayfasını Ubuntu container'ında Nginx ile yayınlar.

## Kullanılan Teknolojiler
- Docker
- Ubuntu
- Nginx
- HTML/CSS

## Yerel Çalıştırma
```bash
docker build -t merhaba-dunya .
docker run -d -p 8080:80 --name merhaba-test merhaba-dunya
```

Tarayıcıda: http://localhost:8080

## Durdurma
```bash
docker stop merhaba-test
docker rm merhaba-test
```
```

4. **Ctrl+S** ile kaydedin

---

**Şu anda dosya yapınız:**
```
merhaba-dunya-docker/
├── .gitignore
├── Dockerfile
├── index.html
└── README.md