---
title: VerifyData()
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje podpis dat.
type: docs
weight: 209
url: /cs/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) metoda


Kontroluje podpis dat.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) pro kontrolu podpisu. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hashovací algoritmus k použití. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podpis, jak byl přijat. |

### Návratová hodnota

True, pokud je podpis platný, false jinak.

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [RSACryptoServiceProvider](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)