# Online Film Sistemi UML Tasarımı

**Yiğit İrfan Turan**

Bu projede, online film satın alma ve kiralama sistemi için nesne yönelimli (OOP) bir **UML Class Diagram** tasarlanmıştır.

## Sistem Özeti

Sistem aşağıdaki temel özellikleri içerecek şekilde modellenmiştir:

- Filmler listelenebilir ve sıralanabilir
- Kullanıcılar sisteme üye olabilir
- Kullanıcılar ikiye ayrılır:
  - Normal Kullanıcı
  - Abone Kullanıcı
- Abone kullanıcılar:
  - Kredi satın alabilir
  - Kredileri ile film kiralayabilir
- Tüm kullanıcılar film satın alabilir
- Film mevcut değilse talep oluşturulabilir

## Tasarım Yaklaşımı

- `Kullanici` abstract class olarak tanımlanmıştır
- `NormalKullanici` ve `AboneKullanici` inheritance ile türetilmiştir
- Satın alma (`SatinAl`) ve kiralama (`Kirala`) işlemleri ayrı sınıflar olarak modellenmiştir
- Kredi satın alma işlemi (`KrediAlim`) ayrı tutulmuştur
- Film durumu `enum (FilmDurumu)` ile ifade edilmiştir
- Film yönetimi için `FilmKatalog` sınıfı kullanılmıştır

## Amaç

Bu tasarım ile:
- OOP prensiplerine uygun bir yapı kurmak
- Sınıflar arası ilişkileri doğru modellemek
- Genişletilebilir ve okunabilir bir sistem oluşturmak hedeflenmiştir

## UML Diyagramı

Aşağıda sistemin UML Class Diagram görseli yer almaktadır:

# Online Film Sistemi UML Tasarımı

**Yiğit İrfan Turan**

Bu projede, online film satın alma ve kiralama sistemi için nesne yönelimli (OOP) bir **UML Class Diagram** tasarlanmıştır.

## Sistem Özeti

Sistem aşağıdaki temel özellikleri içerecek şekilde modellenmiştir:

- Filmler listelenebilir ve sıralanabilir
- Kullanıcılar sisteme üye olabilir
- Kullanıcılar ikiye ayrılır:
  - Normal Kullanıcı
  - Abone Kullanıcı
- Abone kullanıcılar:
  - Kredi satın alabilir
  - Kredileri ile film kiralayabilir
- Tüm kullanıcılar film satın alabilir
- Film mevcut değilse talep oluşturulabilir

## Tasarım Yaklaşımı

- `Kullanici` abstract class olarak tanımlanmıştır
- `NormalKullanici` ve `AboneKullanici` inheritance ile türetilmiştir
- Satın alma (`SatinAl`) ve kiralama (`Kirala`) işlemleri ayrı sınıflar olarak modellenmiştir
- Kredi satın alma işlemi (`KrediAlim`) ayrı tutulmuştur
- Film durumu `enum (FilmDurumu)` ile ifade edilmiştir
- Film yönetimi için `FilmKatalog` sınıfı kullanılmıştır

## Amaç

Bu tasarım ile:
- OOP prensiplerine uygun bir yapı kurmak
- Sınıflar arası ilişkileri doğru modellemek
- Genişletilebilir ve okunabilir bir sistem oluşturmak hedeflenmiştir

## UML Diyagramı

Aşağıda sistemin UML Class Diagram görseli yer almaktadır:

<img width="1040" height="742" alt="image" src="https://github.com/user-attachments/assets/30ad60be-353e-4f8d-8184-9ef4306849d3" />

