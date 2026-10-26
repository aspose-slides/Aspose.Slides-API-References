---
title: Decrypt()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen doldurma modunu kullanarak giriş verisini çözer.
type: docs
weight: 27
url: /tr/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) yöntemi

Belirtilen doldurma modunu kullanarak giriş verisini çözer.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) şifrelenecek dizi. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Doldurma modu. |

### Dönüş Değeri

Byte dizi biçiminde çözülen veri.

## İlgili

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Sınıf [RSA](../)
* Ad alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)