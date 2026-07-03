# i2i-Academy-Containerization-1-OskayFirat

Bu proje, konteynerleştirme teknolojilerinin temellerini öğrenmek amacıyla geliştirilmiştir. Uygulama, statik bir web sayfasını Docker ve Docker Compose kullanarak izole edilmiş bir ortamda çalıştırmayı hedeflemektedir.

## Proje Hakkında
- **Amaç:** Konteynerleştirme ile uygulama dağıtım süreçlerini standartlaştırmak ve çevresel tutarsızlıkları gidermek.
- **Teknolojiler:** Docker, Nginx, Docker Compose.
- **İşleyiş:** `docker-compose.yml` dosyası ile Nginx sunucusu üzerinde `index.html` dosyasının bir konteyner içerisinde servis edilmesi sağlanmıştır.

## Nasıl Çalıştırılır?
1. Projeyi bilgisayarınıza klonlayın: `git clone [repo-linkiniz]`
2. Proje klasörüne gidin.
3. Konteyneri başlatın: `docker compose up -d`
4. Tarayıcınızdan `http://localhost:8080` adresine gidin.
