---
title: Encrypt()
second_title: Aspose.Slides for C++ API Referansı
description: Mesajı şifreler. Henüz uygulanmadı.
type: docs
weight: 118
url: /tr/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) metot


Mesajı şifreler. Henüz uygulanmadı.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) şifrelemek için. |
| use_oaep | **bool** | OAEP doldurması kullanmak için true, PKCS#1 v1.5 doldurması kullanmak için false. |

### Dönüş Değeri

Encrypted data array.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metot


Belirtilen dolgu modunu kullanarak giriş verisini şifreler.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) dizi şifrelemek için. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Dolgu modu. |

### Dönüş Değeri

Encrypted data in byte array format.

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [RSACryptoServiceProvider](../)
* Sınıf [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Ad Alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)