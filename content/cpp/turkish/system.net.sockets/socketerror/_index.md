---
title: SocketError
second_title: Aspose.Slides C++ API Referansı
description: Soket hata türlerini listeler.
type: docs
weight: 209
url: /tr/system.net.sockets/socketerror/
---
## SocketError enum


Enumerates the socket error types.

```cpp
enum class SocketError
```

### Values

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Success | 0 | Bir soket işlemi başarıyla tamamlandı. |
| SocketError | -1 | Belirtilmemiş bir soket hatası oluştu. |
| Interrupted | 10004 | Engelleyen bir soket çağrısı iptal edildi. |
| AccessDenied | 10013 | Bir sokete erişim reddedildi. |
| Fault | 10014 | Geçersiz bir işaretçi adresi tespit edildi. |
| InvalidArgument | 10022 | Geçersiz bir argüman sağlandı. |
| TooManyOpenSockets | 10024 | Temel soket sağlayıcısında çok fazla açık soket var. |
| WouldBlock | 10035 | Bloklamayan bir sokette bir işlem anında tamamlanamıyor. |
| InProgress | 10036 | Bloklayan bir işlem sürüyor. |
| AlreadyInProgress | 10037 | Bloklamayan bir sokette zaten çalışan bir işlem var. |
| NotSocket | 10038 | Soket olmayan bir nesne üzerinde bir soket işlemi çağırma girişimi. |
| DestinationAddressRequired | 10039 | Gerekli bir adres, soket işleminden çıkarıldı. |
| MessageSize | 10040 | Bir datagram çok uzun. |
| ProtocolType | 10041 | Bu soket bir protokol türünü desteklemiyor. |
| ProtocolOption | 10042 | Bilinmeyen, geçersiz veya desteklenmeyen bir seçenek ya da seviye kullanıldı. |
| ProtocolNotSupported | 10043 | Bir protokol uygulanmamış ya da yapılandırılmamış. |
| SocketNotSupported | 10044 | Adres ailesi belirtilen soketi desteklemiyor. |
| OperationNotSupported | 10045 | Protokol ailesi bir adres ailesini desteklemiyor. |
| ProtocolFamilyNotSupported | 10046 | Protokol ailesi uygulanmamış ya da yapılandırılmamış. |
| AddressFamilyNotSupported | 10047 | Belirtilen adres ailesi desteklenmiyor. |
| AddressAlreadyInUse | 10048 | Bir adres yalnızca bir kez kullanılabilir. |
| AddressNotAvailable | 10049 | Seçilen IP adresi bu bağlamda geçerli değil. |
| NetworkDown | 10050 | Ağ kullanılamıyor. |
| NetworkUnreachable | 10051 | Uzak ana bilgisayara giden yol yok. |
| NetworkReset | 10052 | Bir uygulama, zaman aşımına uğramış bir bağlantıda 'Keep-Alive' ayarlamaya çalıştı. |
| ConnectionAborted | 10053 | Bir bağlantı iptal edildi. |
| ConnectionReset | 10054 | Bir bağlantı uzak eş tarafından yeniden ayarlandı. |
| NoBufferSpaceAvailable | 10055 | Soket işlemi için boş tampon alanı yok. |
| IsConnected | 10056 | Bir soket zaten bağlı. |
| NotConnected | 10057 | Bir uygulama veri göndermeye veya almaya çalıştı, ancak soket bağlı değil. |
| Shutdown | 10058 | Soket zaten kapatıldığı için veri gönderme veya alma isteği yasaktır. |
| TimedOut | 10060 | Bir bağlantı denemesi zaman aşımına uğradı veya bağlanan ana bilgisayar yanıt vermedi. |
| ConnectionRefused | 10061 | Uzak bir ana bilgisayar aktif olarak bir bağlantıyı reddediyor. |
| HostDown | 10064 | Uzak bir ana bilgisayar kapalı olduğu için bir işlem başarısız oldu. |
| HostUnreachable | 10065 | Belirtilen ana bilgisayara ağ yolu yok. |
| ProcessLimit | 10067 | Temel soket sağlayıcısını çok fazla süreç kullanıyor. |
| SystemNotReady | 10091 | Bir ağ alt sistemi mevcut değil. |
| VersionNotSupported | 10092 | Temel soket sağlayıcısının bir sürümü kapsam dışı. |
| NotInitialized | 10093 | Temel soket sağlayıcısı başlatılmadı. |
| Disconnecting | 10101 | Kibar bir kapatma işlemi sürüyor. |
| TypeNotFound | 10109 | Belirtilen sınıf bulunamadı. |
| HostNotFound | 11001 | Belirtilen ana bilgisayar bilinmiyor. |
| TryAgain | 11002 | Bir ana bilgisayar adı çözülemedi. |
| NoRecovery | 11003 | Bir hata kurtarılamaz ya da istenen veri tabanı bulunamıyor. |
| NoData | 11004 | İstenen ad veya IP adresi isim sunucusunda bulunamadı. |

## See Also

* AdAlanı [System::Net::Sockets](../)
* Kütüphane [Aspose.Slides](../../)