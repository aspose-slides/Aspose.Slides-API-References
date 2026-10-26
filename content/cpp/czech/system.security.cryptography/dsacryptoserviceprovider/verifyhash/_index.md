---
title: VerifyHash()
second_title: Aspose.Slides pro C++ reference API
description: Kontroluje podpis dat.
type: docs
weight: 222
url: /cs/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) metoda

Kontroluje podpis dat.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash vypočítaný pro přijatá data. |
| str | const [String](../../../system/string/)\& | Název použitého hash algoritmu. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podpis tak, jak byl přijat. |

### Návratová hodnota

True pokud je podpis platný, false jinak.

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* třída [String](../../../system/string/)
* třída [DSACryptoServiceProvider](../)
* jmenný prostor [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)