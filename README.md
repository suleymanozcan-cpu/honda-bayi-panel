# Honda Bayi Sosyal Medya Denetim Paneli

Honda kurumsal kimliğine uygun, mobil uyumlu, statik HTML/CSS/JavaScript demo uygulamasıdır. Kullanıcının ilettiği Honda logosu doğrudan `index.html` içine gömülüdür. Ek dosya veya sunucu kurulumu gerekmez.

## Özellikler
- Beş bayi için dönem bazlı, manuel 100 puanlık uyumluluk değerlendirmesi
- Aylık paylaşım hedeflerini izleme
- Honda'nın 10 maddelik yayın öncesi içerik kontrolü
- Reels, post ve story kayıtları; bayi filtresi
- Dönem raporları, CSV dışa aktarımı, JSON yedekleme ve yazdırma
- Mobil alt menü ve masaüstü yönetim görünümü

## Veri ve güvenlik
- Mevcut sürüm Instagram/Meta API'sine bağlı değildir; reklamlar doğrulanmaz.
- Veriler yalnızca tarayıcının localStorage alanında tutulur; cihazlar arasında eşitlenmez.
- Mevcut `hondaAuditV1` anahtarı ve kayıtları korunur.
- Üretilen puanlar resmi Honda Türkiye onayı veya otomatik değerlendirmesi değildir.
- Gerçek müşteri bilgileri veya gizli API anahtarları bu herkese açık GitHub Pages sitesinde saklanmamalıdır.

## Yayın
GitHub Pages: `main` dalı, `/(root)` klasörü. `index.html` güncellenince yeniden yayınlanır.

## Geri alma
Önceki ilk sürüm `backup-before-honda-redesign` dalında saklanır.
