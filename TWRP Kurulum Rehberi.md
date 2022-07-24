# [Redmi 10x 4G/Redmi Note 9][MERLIN]TWRP Kurulum Rehberi


Buradaki anlatım V12.0.1.0.RJOMIXM(Android 11) Sürümü baz alınarak anlatılmıştır.

https://forum.xda-developers.com/t/twrp-pbrp-collection-of-twrp-pbrp-for-merlin-redmi-note-9-redmi-10x-4g.4227751/

Farklı bir Miui sürümünde iseniz
Yukarıdaki Linkteki verilen sürümlere uygun twrp dosyalarını kurmanız gerekmektedir.

NOT: Bazı cihazlarda twrp yüklenmesi sonucu dokunmatik çalışmaması ve siyah ekran sorunları oluşmaktadır. Bu sorunları göze alarak twrp kurmayı deneyiniz.
Yapacağınız işlemlerde bütün sorumluluk size aittir. Oluşabilecek sorunlardan şahsım ve "TurkDevs.com" sorumlu tutulamaz.
Lütfen Başka Forumlarda Veya Platformlarda İznim Olmadan Paylaşmayınız.

Kurulum için Mi kilidi açık olması gerekmektedir.


https://xiaomitools.com/download/minimal-adb-ve-fastboot-v1-4-3/

İlk Önce minimal adb ve fastboot aracını indirip Kuruyoruz
Sonra Redmi_Note_9_Merlin_Android_11_TWRP adlı dosyayı indiriyoruz (twrp by wzsx150 tarafından yapılmıştır. )

https://disk.yandex.com.tr/d/dy3i417yfFrtlg

Telefonun Ayarlar/Telefon Hakkında/Tüm Özellikler/Mıuı sürümüne 5 kez tıklayın
Sonra Ayarlar / Ek Ayarlar / Seçenekler / USB Hata ayıklamayı açınız
Telefonu kapatıp Ses Kısma + Güç Tuşuna basılı tutun Fastboot mod açılsın
İndirdiğiniz Redmi_Note_9_Merlin_Android_11_TWRP zipin içindekileri Mınımal adb ve fastboot aracının olduğu klasöre atın

![Uygulama Ekran Görüntüsü](https://i.hizliresim.com/l3o60nd.PNG)

Mınımal adb ve fastboot aracını yönetici olarak çalıştırıp açınız

Gelen komut ekranına sırayla

```
fastboot flash recovery 3.4.2b-0109.img

```
yazıyoruz enter a basıyoruz.

```
fastboot flash vbmeta vbmeta.img 

```
yazıyoruz enter a basıyoruz.

```
fastboot flash misc misc.bin 

```
yazıyoruz enter a basıyoruz

```
fastboot boot 3.4.2b-0109.img 

```


yazıyoruz enter a basıyoruz 5sn-10sn arası bekliyoruz açılırken ses açmaya basıp recovery ekranına geçmiş oluyoruz.

![Uygulama Ekran Görüntüsü](https://i.hizliresim.com/iu8wpfu.png)
