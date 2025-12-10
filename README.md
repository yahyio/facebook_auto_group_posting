# Facebook Grup Post Atma Aracı

Facebook gruplarına otomatik post atmak için geliştirilmiş masaüstü uygulaması. Birden fazla gruba aynı anda mesaj ve fotoğraf paylaşımı yapabilirsiniz.

## 🚀 Özellikler

- **Toplu Grup Paylaşımı**: Birden fazla Facebook grubuna aynı anda post atma
- **Fotoğraf Desteği**: Mesajlarınıza fotoğraf ekleme imkanı
- **Otomatik Giriş**: Facebook hesap bilgilerini kaydedip otomatik giriş yapma
- **Arka Planda Çalışma**: Postları arka planda otomatik olarak gönderme
- **Durum Takibi**: Her postun gönderim durumunu anlık izleme
- **Basit Arayüz**: Kullanıcı dostu ve sade tasarım

## 📋 Gereksinimler

- Python 3.8 veya üzeri
- Google Chrome tarayıcısı
- ChromeDriver (Selenium için)
- Aktif Facebook hesabı
- İnternet bağlantısı

## ⚙️ Kullanım

### 1. Facebook Giriş Bilgileri

Uygulamayı ilk açtığınızda Facebook giriş bilgilerinizi girmeniz gerekir:

- **E-posta**: Facebook hesabınızın e-posta adresi
- **Şifre**: Facebook hesabınızın şifresi
- **Giriş Yap**: Bilgileri kaydeder ve Facebook'a giriş yapar

**Not**: Giriş bilgileriniz yerel olarak şifrelenmiş şekilde saklanır.

### 2. Grup Linkleri Ekleme

"Facebook Grup Linkleri" bölümüne post atmak istediğiniz grupların linklerini ekleyin:

- Her satıra bir grup linki yazın
- Link formatı: `https://www.facebook.com/groups/grup-adi/`
- Birden fazla grup ekleyebilirsiniz

**Örnek:**
```
https://www.facebook.com/groups/alimsat/
https://www.facebook.com/groups/teknoloji/
https://www.facebook.com/groups/yazilim/
```

### 3. Post İçeriği Hazırlama

**Mesaj:**
- "Mesaj" alanına paylaşmak istediğiniz metni yazın
- Emoji ve özel karakterler desteklenir
- Birden fazla satır yazabilirsiniz

**Fotoğraf (Opsiyonel):**
- "Dosya Seç" butonuna tıklayın
- Paylaşmak istediğiniz fotoğrafı seçin

### 4. Post Gönderme

- **"Postları Gönder"** butonuna tıklayın
- Program seçili gruplara sırayla post atmaya başlar
- **"Arka planda çalıştır"** seçeneğini işaretlerseniz tarayıcı görünmez modda çalışır
- **Durum**: Her postun durumu alt kısımda gösterilir (Hazır/Gönderiliyor/Tamamlandı)

## 🎯 Özellikler ve Ayarlar

### Arka Planda Çalıştır
- Bu seçenek işaretlendiğinde Chrome tarayıcısı görünmez modda açılır
- Bilgisayarınızda başka işlerle uğraşırken post gönderebilirsiniz
- İşlem sırasında tarayıcı penceresi görünmez

### Güvenlik
- Facebook giriş bilgileriniz şifrelenmiş olarak saklanır
- Hassas veriler bellekte tutulmaz
- Her oturumda güvenli bağlantı kullanılır

## 📊 Durum Takibi

Uygulama alt kısımda gerçek zamanlı durum gösterir:

- **Hazır**: Program kullanıma hazır
- **Gönderiliyor**: Postlar gönderilme aşamasında
- **Tamamlandı**: Tüm postlar başarıyla gönderildi
- **Hata**: Bir sorun oluştu (detaylar log dosyasında)

## ⚠️ Önemli Uyarılar

### Facebook Kuralları
- Facebook'un spam politikalarına uyun
- Kısa sürede çok fazla post atmayın (hesabınız kısıtlanabilir)
- Sadece üyesi olduğunuz gruplara post atın
- Grup kurallarına uygun içerik paylaşın

### Kullanım Limitleri
- **Önerilen**: Saatte en fazla 5-10 post
- Gruplar arasında 30-60 saniye bekleme süresi bırakın
- Günde 20-30 gruptan fazlasına post atmayın

### Güvenlik Uyarıları
- E-posta ve şifrenizi kimseyle paylaşmayın
- Güvenilir olmayan gruplara post atmayın
- İki faktörlü kimlik doğrulaması (2FA) kullanırsanız uygulama şifresi oluşturun
- Programı kapatırken giriş bilgilerini silme seçeneğini kullanabilirsiniz

## 🐛 Sorun Giderme

### Giriş Yapamıyorum
- E-posta ve şifrenizi kontrol edin
- Facebook'ta 2FA varsa uygulama şifresi kullanın
- Captcha çıkarsa manuel olarak çözmeniz gerekebilir
- VPN kullanıyorsanız kapatmayı deneyin

### Post Gönderilmiyor
- İnternet bağlantınızı kontrol edin
- Gruplara üye olduğunuzdan emin olun
- Grup linklerinin doğru olduğunu kontrol edin
- Facebook'un geçici kısıtlama koyup koymadığını kontrol edin

### ChromeDriver Hataları
- Chrome tarayıcınızın güncel olduğundan emin olun
- ChromeDriver sürümünün Chrome ile uyumlu olduğunu kontrol edin
- ChromeDriver'ı tekrar indirip yükleyin

### Hesap Kısıtlandı
- Facebook'un spam politikalarını ihlal etmiş olabilirsiniz
- Bir süre bekleyin ve daha az sıklıkta post atmayı deneyin
- Facebook destek ile iletişime geçin

## 📝 İpuçları

1. **Test Edin**: İlk kullanımda 1-2 grupla test edin
2. **Zamanlama**: Postları farklı saatlerde atmayı deneyin
3. **İçerik Çeşitliliği**: Her post için farklı mesajlar kullanın
4. **Bekleme Süreleri**: Gruplar arası en az 1 dakika bekleyin
5. **Log Tutun**: Hangi gruplara ne zaman post attığınızı not alın

## 🔒 Gizlilik ve Güvenlik

- Giriş bilgileriniz sadece sizin bilgisayarınızda saklanır
- Hiçbir veri dış sunuculara gönderilmez
- Şifreler AES-256 ile şifrelenir
  
## 📧 İletişim

Sorularınız için issue açabilir veya email ile iletişime geçebilirsiniz.

---

## 📸 Ekran Görüntüleri

### Ana Arayüz
[![arayüz}](https://i.hizliresim.com/73x25s7.png)](https://hizliresim.com/73x25s7)

*Facebook giriş bilgileri, grup linkleri ve post içeriği girme ekranı*

---

**⚖️ Yasal Uyarı**: Bu araç yalnızca eğitim amaçlıdır. Facebook'un kullanım şartlarına ve politikalarına uygun şekilde kullanılmalıdır. Kötüye kullanımdan kaynaklanan sorunlardan geliştirici sorumlu değildir. Spam yapmayın ve grup kurallarına uyun.
