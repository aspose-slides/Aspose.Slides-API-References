---
title: X509KeyUsageFlags
second_title: Aspose.Slides for C++ API Referansı
description: Sertifika anahtarının nasıl kullanılabileceğini tanımlar.
type: docs
weight: 274
url: /tr/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum

Sertifika anahtarının nasıl kullanılabileceğini tanımlar.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | 0 | Anahtar kullanım parametreleri yok. |
| EncipherOnly | 1 | Anahtar yalnızca şifreleme için kullanılabilir. |
| CrlSign | 2 | Anahtar bir sertifika iptal listesi imzalamak için kullanılabilir. |
| KeyCertSign | 4 | Anahtar sertifikaları imzalamak için kullanılabilir. |
| KeyAgreement | 8 | Anahtar, anahtar anlaşması belirlemek için kullanılabilir. |
| DataEncipherment | 16 | Anahtar veri şifrelemesi için kullanılabilir. |
| KeyEncipherment | 32 | Anahtar anahtar şifrelemesi için kullanılabilir. |
| NonRepudiation | 64 | Anahtar kimlik doğrulama için kullanılabilir. |
| DigitalSignature | 128 | Anahtar dijital imza olarak kullanılabilir. |
| DecipherOnly | 32768 | Anahtar yalnızca şifre çözme için kullanılabilir. |

## Ayrıca Bakınız

* Ad alanı [System::Security::Cryptography::X509Certificates](../)
* Kütüphane [Aspose.Slides](../../)