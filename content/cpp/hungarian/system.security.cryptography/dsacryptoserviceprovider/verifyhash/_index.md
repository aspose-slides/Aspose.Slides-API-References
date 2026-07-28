---
title: VerifyHash()
second_title: Aspose.Slides C++ API referencia
description: Ellenőrzi az adat aláírását.
type: docs
weight: 222
url: /hu/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) metódus


Ellenőrzi az adat aláírását.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A fogadott adatokhoz számított hash. |
| str | const [String](../../../system/string/)\& | A hasheléshez használt algoritmus neve. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Az átvett aláírás. |

### Visszatérési érték

Igaz, ha az aláírás érvényes, egyébként hamis.

## Lásd még

* Típusdefiníció [ByteArrayPtr](../../../system/bytearrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [DSACryptoServiceProvider](../)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)