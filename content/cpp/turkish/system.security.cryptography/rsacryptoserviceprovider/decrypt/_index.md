---
title: Decrypt()
second_title: Aspose.Slides için C++ API Referansı
description: Mesajı çözer. Henüz uygulanmadı.
type: docs
weight: 105
url: /tr/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) metodu

Mesajı çözer. Henüz uygulanmadı.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) çözmek için. |
| use_oaep | **bool** | OAEP doldurmayı kullanmak için true, PKCS#1 v1.5 doldurmayı kullanmak için false. |

### Dönüş Değeri

Şifre çözülmüş veri dizisi.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metodu

Belirtilen doldurma modunu kullanarak giriş verilerini çözer.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) dizisini çözmek için. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Doldurma modu. |

### Dönüş Değeri

Şifre çözülmüş veri bayt dizisi biçiminde.

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSACryptoServiceProvider](../)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)