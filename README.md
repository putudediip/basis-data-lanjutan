Panduan Praktik Instalasi MongoDB dan Mongo Express GUI dengan Docker
📚 Pendahuluan
Panduan ini dirancang khusus untuk mahasiswa yang ingin mempelajari MongoDB melalui antarmuka grafis (GUI) menggunakan Mongo Express dengan Docker. Docker memungkinkan kita menjalankan database dan antarmuka pengguna dalam lingkungan yang terisolasi, konsisten, dan mudah diatur tanpa perlu instalasi yang kompleks di komputer lokal.
MongoDB adalah database NoSQL berbasis dokumen yang menyimpan data dalam format JSON-like, sementara Mongo Express menyediakan antarmuka web yang user-friendly untuk mengelola database MongoDB. Kombinasi ini sangat ideal untuk pembelajaran karena memungkinkan mahasiswa fokus pada konsep database tanpa terhalang oleh setup yang rumit.
✅ Prasyarat Sebelum Memulai
Sebelum memulai instalasi, pastikan komputer Anda telah terinstall dengan software berikut:
1. Docker Engine
Docker Engine diperlukan untuk menjalankan kontainer. Untuk memeriksa instalasi Docker, buka terminal dan jalankan:
docker --version
Output yang diharapkan:
Docker version 24.0.7, build afdd53b
2. Docker Compose
Docker Compose digunakan untuk mendefinisikan dan menjalankan aplikasi multi-kontainer. Periksa instalasi dengan:
docker compose version
Output yang diharapkan:
Docker Compose version v2.20.2
Catatan: Setup ini bekerja di Windows, macOS, dan Linux (Debian atau Ubuntu) 

