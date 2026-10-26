---
title: SecurityPermissionFlag
second_title: Aspose.Slides for C++ API Referansı
description: Güvenlik izni bayrakları.
type: docs
weight: 27
url: /tr/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum

Güvenlik izni bayrakları.

```cpp
enum class SecurityPermissionFlag
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| NoFlags | 0 | Erişim yok. |
| Assertion | 1 | İznin verildiğini doğrula. |
| UnmanagedCode | 2 | Yönetilmeyen kodu çağır. |
| SkipVerification | 4 | Kod doğrulamasını atla. |
| Execution | 8 | Kodu çalıştır. |
| ControlThread | 16 | İş parçacıklarında işlemler gerçekleştir. |
| ControlEvidence | 32 | CLR kanıtını kontrol et veya değiştir. |
| ControlPolicy | 64 | Politikayı görüntüle ve değiştir. |
| SerializationFormatter | 128 | Seri hale getir. |
| ControlDomainPolicy | 256 | Alan politikasını ayarla. |
| ControlPrincipal | 512 | Ana nesneyi kontrol et. |
| ControlAppDomain | 1024 | Uygulama alanını kontrol et. |
| RemotingConfiguration | 2048 | Uzak nesneleri yapılandır. |
| Infrastructure | 4096 | CLR altyapısına bağlan. |
| BindingRedirects | 8192 | Açık bağlama yönlendirmesi gerçekleştir. |
| AllFlags | 16383 | Sınırsız. |

## Ayrıca Bakınız

* Ad Alanı [System::Security::Permissions](../)
* Kütüphane [Aspose.Slides](../../)