---
title: SignHash()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen giriş değerinin imzasını hesaplar.
type: docs
weight: 196
url: /tr/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) metodu

Belirtilen giriş değerinin imzasını hesaplar.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmzalanacak verinin hash değeri. |
| str | const [String](../../../system/string/)\& | Hash oluşturmak için kullanılan hash algoritması tanımlayıcısı. |

### Dönüş Değeri

[DSA](../../dsa/) belirtilen veri için imza.

## İlgili

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [DSACryptoServiceProvider](../)
* AdAlanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)