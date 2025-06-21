# Nextcloud Nedir?

Nextcloud, OwnCloud’un eski geliştiricileri tarafından tasarlandı ve Haziran 2016’da pi- yasaya sürüldü. Windows, MacOS, iOS, Linux ve Android dahil olmak üzere çeşitli işletim sistemlerinde kullanılabiliyor. Bu bulut yazılım ile kullanıcılar dosyalarını kendi sunucu- larına kaydedebilme imkanına sahiptir. Bu durum, özel bir sunucu ya da bir sağlayıcıdaki sunucu olduğu anlamına gelir. Nextcloud, dosyalarının kontrolünü elinde tutan kulla- nıcılara güvenir. Yani kullanıcılar, belgelerin veya fotoğrafların nerede saklanacağına ve bunlara kimlerin erişebileceğine her zaman kendileri karar verebilirler, ki bu özellik güvenli bir kullanım sunduğundan bu sistemin kullanıcıları tarafından tercih ediliyor. Nextcloud, PHP komut dosyalarını kullanarak çeşitli veritabanlarına erişir. Bu amaçla kullanılan is- temciler, sunuculardaki yerel dizinleri otomatik olarak senkronize etmeye de hizmet eder. Bulut sağlayıcı, özel kullanıcılar için ücretsiz kullanımın reklamını da yapar. Nextcloud’un işlevsel ilkesi, ownCloud veya Google Drive gibi diğer bulut hizmetlerine benzer. Kullanı- cılar dosyalarını buluta yükler ve ardından birden fazla cihazda bunlara esnek bir şekilde erişebilir ve bunları düzenleyebilir.

# Nextcloud Kurulumu ve Yapı Raporu

Nextcloud, Ubuntu 22.04 üzerinde aşağıdaki bileşenlerden oluşur ve kendi aralarında şu şekilde haberleşir:

- **Kullanıcılar:** Web tarayıcıları veya mobil uygulamalar ile erişim sağlar.
- **Web Sunucusu (Apache/Nginx):** HTTP(S) isteklerini karşılar.
- **Nextcloud Uygulaması:** PHP tabanlı, dosya yönetimi ve kullanıcı arayüzünü sağlar.
- **Veritabanı (MySQL/PostgreSQL):** Verileri saklar.
- **Depolama Alanı:** Kullanıcı dosyalarının tutulduğu alan.

## Klasör Yapısı

- `docs/`: Dökümantasyon ve mimari diyagramlar
- `outputs/`: Kurulum sonrası elde edilen çıktı ve raporlar
- `README.md`: Proje genel açıklaması ve hızlı başlangıç

## Kurulum Özeti

1. **Sunucu Hazırlığı:** Ubuntu 22.04 güncellemesi ve temel paketlerin kurulumu.
2. **Web Sunucusu ve PHP:** Apache/Nginx ve gerekli PHP modüllerinin kurulumu.
3. **Veritabanı:** MySQL kurulumu ve Nextcloud için veritabanı oluşturulması.
4. **Nextcloud İndirimi ve Yapılandırma:** Nextcloud dosyalarının indirilip sunucuya yerleştirilmesi, kurulum sihirbazı ile yapılandırma.

## Çalışma Akışı

1. Kullanıcı tarayıcı üzerinden Nextcloud’a erişir.
2. Web sunucusu isteği Nextcloud’a iletir.
3. Nextcloud gelen isteği işler, gerekirse veritabanına veya dosya sistemine erişir.
4. Sonuç kullanıcıya iletilir.

![bigpicture](https://github.com/user-attachments/assets/621cd333-f3c1-4270-9b3b-4ff5a65277dd)


## Nextcloud İle Entegre Servisler

>Ofis/Belge Düzenleme

>E-posta Servisleri

>Takvim ve Kişiler

>Anlık Mesajlaşma ve Video Konferans

>Antivirüs ve Güvenlik

## Çıktılar ve Sonuçlar


Kurulum sonrası Nextcloud arayüzüne başarılı şekilde erişildi. Dosya yükleme, paylaşma ve kullanıcı yönetimi gibi temel işlevler sağlıklı çalışmaktadır. Detaylı kurulum raporu ve ekran görüntüleri için `outputs/` klasörüne bakabilirsiniz.


Muhammet Ömer Bilgili

Serkan Kamilçelebi
