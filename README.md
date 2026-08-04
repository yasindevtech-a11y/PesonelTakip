# Personel Takip - APK

Bu klasör, Personel Takip uygulamasını Android APK'sına çeviren küçük bir "kabuk" projesidir.
İçindeki `app/src/main/assets/www/index.html` dosyası, Supabase'e bağlı asıl uygulamadır.

## APK'yı nasıl alırım?

1. Bu klasördeki tüm dosyaları bir GitHub deposuna (repository) yükle.
2. GitHub'da deponun üstündeki **"Actions"** sekmesine gir.
3. Soldaki **"APK Oluştur"** iş akışına tıkla, sağ tarafta **"Run workflow"** butonuna bas (veya dosyaları yükleyince otomatik başlar).
4. 3-5 dakika bekle, yeşil ✅ işareti çıkınca işlem bitmiştir.
5. Aynı sayfanın altındaki **"Artifacts"** (Yapıtlar) bölümünde **"personel-takip-apk"** yazan dosyaya tıkla, indir.
6. İndirdiğin `.zip` dosyasını aç, içinden çıkan `app-debug.apk` dosyasını telefonuna at ve kur.

> Not: Bu bir "debug" (test) APK'sıdır — Play Store'a yüklemek için değil, kendi telefonlarınıza kurmak için uygundur.
> Telefonun "Bilinmeyen kaynaklardan yükleme" ayarını açman gerekebilir, Android bunu kurulum sırasında zaten soracaktır.
