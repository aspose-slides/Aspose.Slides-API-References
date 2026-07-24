---
title: WebExceptionStatus
second_title: Aspose.Slides için C++ API Referansı
description: WebException sınıfının durum kodlarını listeler.
type: docs
weight: 651
url: /tr/system.net/webexceptionstatus/
---
## WebExceptionStatus enum

WebException sınıfının durum kodlarını listeler.

```cpp
enum class WebExceptionStatus
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Success | 0 | Hata oluşmadı. |
| NameResolutionFailure | 1 | Ad çözümleme hizmeti ana bilgisayar adını çözemedi. |
| ConnectFailure | 2 | Uzak hizmet noktası taşıma düzeyinde temasa geçilemedi. |
| ReceiveFailure | 3 | Uzak sunucudan tam bir yanıt alınamadı. |
| SendFailure | 4 | Tam bir istek uzak sunucuya gönderilemedi. |
| PipelineFailure | 5 | İstek bir ardışık istekti ve yanıt alınmadan bağlantı kapatıldı. |
| RequestCanceled | 6 | İstek iptal edildi veya sınıflandırılamayan bir hata oluştu. |
| ProtocolError | 7 | Sunucudan alınan yanıt tamdı ancak protokol düzeyinde bir hata gösterdi. |
| ConnectionClosed | 8 | Bağlantı erken kapatıldı. |
| TrustFailure | 9 | Sunucu sertifikası doğrulanamadı. |
| SecureChannelFailure | 10 | SSL kullanılarak bağlantı kurulurken bir hata oluştu. |
| ServerProtocolViolation | 11 | Sunucu yanıtı geçerli bir HTTP yanıtı değildi. |
| KeepAliveFailure | 12 | 'Keep-Alive' başlığını belirten istek için bağlantı beklenmedik şekilde kapatıldı. |
| Pending | 13 | Dahili bir eşzamansız istek beklemede. |
| Timeout | 14 | İstek için zaman aşımı süresi boyunca yanıt alınmadı. |
| ProxyNameResolutionFailure | 15 | Ad çözümleme hizmeti vekil ana bilgisayar adını çözemedi. |
| UnknownError | 16 | Bilinmeyen türde bir istisna oluştu. |
| MessageLengthLimitExceeded | 17 | Belirtilen sınırı aşan bir ileti alındı. |
| CacheEntryNotFound | 18 | Belirtilen önbellek girişi bulunamadı. |
| RequestProhibitedByCachePolicy | 19 | İstek önbellek politikası tarafından izin verilmedi. |
| RequestProhibitedByProxy | 20 | Bu istek vekil tarafından izin verilmedi. |

## Ayrıca Bakınız

* Ad Alanı [System::Net](../)
* Kütüphane [Aspose.Slides](../../)