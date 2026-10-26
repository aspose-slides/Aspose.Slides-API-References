---
title: VerifyData()
second_title: Aspose.Slides a C++ API Referenciája
description: Ellenőrzi az adat aláírását.
type: docs
weight: 209
url: /hu/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) method

Ellenőrzi az adat aláírását.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) az aláírás ellenőrzéséhez. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hash algoritmus a használathoz. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A kapott aláírás. |

### Visszatérési érték

Igaz, ha az aláírás érvényes, egyébként hamis.

## Lásd még

* Típusdefiníció [ByteArrayPtr](../../../system/bytearrayptr/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [RSACryptoServiceProvider](../)
* Névterület [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)