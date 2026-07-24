---
title: Encrypt()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen doldurma modunu kullanarak giriş verilerini şifreler.
type: docs
weight: 53
url: /tr/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metodu


Belirtilen doldurma modunu kullanarak giriş verilerini şifreler.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) şifrelemek için dizi. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Doldurma modu. |

### Dönüş Değeri

Şifrelenmiş veri bayt dizisi formatında.

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Sınıf [RSA](../)
* Ad alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)