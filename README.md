🎭 Doğruluk mu Cesaret mi? Telegram Botu

Telegram üzerinde arkadaş gruplarıyla oynanabilen Doğruluk mu Cesaret mi? oyun botu.

🎮 Özellikler

👤 Tek kişilik ve grup kullanımı

🎯 Doğruluk ve cesaret seçenekleri

🎲 Rastgele görev/soru sistemi

👥 Grup içindeki oyuncuları otomatik tanıma

🏆 Puan sistemi

📊 Oyuncu istatistikleri

🔘 Inline butonlarla kolay kullanım

💾 Kalıcı SQLite veritabanı

🛡️ Hatalara karşı güvenli çalışma

⚡ Hızlı ve sade Telegram arayüzü

📋 Oyun Mantığı

Oyuncular oyuna katılır.

Sırası gelen oyuncu:

🔵 DOĞRULUK
veya
🔴 CESARET

seçeneklerinden birini seçer.

Bot rastgele bir doğruluk sorusu veya cesaret görevi gönderir.

Oyuncu görevi tamamladıktan sonra sıradaki oyuncuya geçilir.

🕹️ Temel Komutlar

/start       → Botu başlatır
/oyun        → Yeni oyun başlatır
/katil       → Oyuna katılır
/bilgi       → Oyun hakkında bilgi
/istatistik  → Oyuncu istatistikleri
/bitir       → Devam eden oyunu bitirir

🏆 Puan Sistemi

Oyuncular tamamladıkları görevlere göre puan kazanabilir.

Örnek:

Doğruluk → +10 puan
Cesaret  → +15 puan

Puanlar veritabanında kalıcı olarak saklanır.

💾 Veritabanı

Proje SQLite kullanır.

Saklanabilecek veriler:

Telegram kullanıcı ID

Kullanıcı adı

Oyun sayısı

Tamamlanan doğruluk görevleri

Tamamlanan cesaret görevleri

Kazanılan toplam puan

Grup oyunları

Oyun istatistikleri

🛠️ Kurulum

Python 3.10 veya üzeri önerilir.

Gerekli paketleri yükleyin:

pip install -r requirements.txt

.env.example dosyasını .env olarak kopyalayın ve Telegram bot tokeninizi girin.

Ardından:

python bot.py

🔐 Güvenlik

Bot tokeni doğrudan bot.py içerisine yazılmamalıdır.

Token .env dosyasında tutulmalıdır.

.env dosyası .gitignore içerisinde bulunmalıdır.

📁 Proje Yapısı

dogruluk-cesaret-bot/
│
├── README.md
├── bot.py
├── config.py
├── database.py
├── requirements.txt
├── .env.example
├── .gitignore
│
└── data/
    └── .gitkeep

🚀 Gelecek Özellikler

🌐 Global liderlik tablosu

👑 Grup yöneticisi sistemi

🎨 Farklı oyun kategorileri

🔥 Seri/Combo sistemi

🎁 Ödül sistemi

🏅 Başarı rozetleri

🔊 Sesli görevler

⚙️ Grup özel ayarları

📜 Lisans

Bu proje kişisel ve eğitim amaçlı geliştirilmiştir.
