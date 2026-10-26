---
title: SignHash()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vypočítá podpis zadané vstupní hodnoty.
type: docs
weight: 196
url: /cs/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash(const ByteArrayPtr&, const String&) metoda

Vypočítá podpis zadané vstupní hodnoty.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hashová hodnota dat, která mají být podepsána. |
| str | const [String](../../../system/string/)\& | Identifikátor hash algoritmu použitý k vytvoření hash. |

### Návratová hodnota

[DSA](../../dsa/) podpis pro zadaná data.

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Třída [String](../../../system/string/)
* Třída [DSACryptoServiceProvider](../)
* Obor názvů [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)