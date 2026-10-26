---
title: TryFromOid()
second_title: Aspose.Slides for C++ API Referansı
description: OID değerinden HashAlgorithmName oluşturmayı deneyin.
type: docs
weight: 66
url: /tr/system.security.cryptography/hashalgorithmname/tryfromoid/
---
## HashAlgorithmName::TryFromOid(const String&, HashAlgorithmName&) metod

OID-değerinden [HashAlgorithmName](../) oluşturmayı deneyin.

```cpp
static bool System::Security::Cryptography::HashAlgorithmName::TryFromOid(const String &oid_value, HashAlgorithmName &value)
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| oid_value | const [String](../../../system/string/)\& | OID değeri. |
| value | [HashAlgorithmName](../)\& | Çıktı [HashAlgorithmName](../). |

### Dönüş Değeri

Belirtilen OID geçerli bir hash algoritmasıysa true, aksi takdirde false.

## İlgili

* Sınıf [String](../../../system/string/)
* Yapı [HashAlgorithmName](../)
* Ad Alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)