# Connity Site

Connity Android uygulamasının resmî APK indirme sitesi. Zyven Studios.

## Yapı
- `index.html`: tüm site (tek dosya, kütüphanesiz)
- `assets/logo.png`: Connity logosu
- `assets/screens/`: gerçek uygulama ekran görüntüleri (`ekran-1.png`, `ekran-2.png`, `ekran-3.png`). Dosya yoksa boş çerçeve görünür.

## APK
İndirme butonu sitenin içindeki dosyaya gider: `download/connity.apk`

Yeni sürüm çıkınca bu dosyanın üzerine yeni APK'yı aynı adla yükle ve `index.html` içindeki sürüm/boyut satırını (`class="meta"`) güncelle.

## Yasal sayfalar
Gizlilik Politikası, Kullanım Koşulları, KVKK, Hesap Silme ve İletişim bağlantıları "Yakında" olarak bekliyor. Sayfalar hazır olunca `index.html` içindeki ilgili `href="#"` değerlerini güncelle.

## Yayın
Settings → Pages → Branch: `main`, klasör `/ (root)`.
