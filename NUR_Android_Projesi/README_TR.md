# NUR Android projesi

Bu proje, NUR HTML uygulamasını Android WebView içinde açan bir Android uygulamasıdır. APK, GitHub Actions tarafından otomatik derlenir.

## GitHub üzerinden APK alma (bilgisayardan)

1. https://github.com adresine gir ve ücretsiz hesap aç / giriş yap.
2. Sağ üstteki **+** işaretine bas, **New repository** seç.
3. Repository name alanına `NUR-Android` yaz. **Public** seçip **Create repository** düğmesine bas.
4. Açılan boş depoda **uploading an existing file** bağlantısına tıkla. Görünmüyorsa **Add file > Upload files** seç.
5. Bu ZIP'in içindeki dosya ve klasörleri çıkar. ZIP dosyasının kendisini değil, içindekilerin tamamını GitHub sayfasına sürükleyip bırak. `.github` klasörünün de yüklendiğinden emin ol.
6. Aşağı in, **Commit changes** düğmesine bas.
7. Depoda **Actions** sekmesine gir. `NUR APK oluştur` iş akışını aç. İlk derleme otomatik başlamazsa **Run workflow > Run workflow** seç.
8. İşlem bitince yeşil tik görünür. Çalışmanın içine gir, sayfanın altındaki **Artifacts** bölümünden `NUR-APK` dosyasını indir.
9. İnen ZIP'i aç. İçindeki `app-debug.apk` dosyasını Android telefonuna gönderip kur.

## Önemli
- GitHub hesabı ücretsiz yeterlidir; Public repository seç.
- APK ilk derlemede birkaç dakika sürebilir.
- Kur'an metinleri ve namaz vakitleri internet bağlantısı gerektirir.
- Bu proje debug APK üretir. Play Store'a yüklemek için ayrıca imzalı release paketi gerekir.
