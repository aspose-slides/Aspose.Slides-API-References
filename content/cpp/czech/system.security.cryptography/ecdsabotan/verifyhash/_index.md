---
title: VerifyHash()
second_title: Aspose.Slides pro C++ API Reference
description: Ověřuje podpis dat.
type: docs
weight: 183
url: /cs/system.security.cryptography/ecdsabotan/verifyhash/
---
## ECDsaBotan::VerifyHash(ByteArrayPtr, ByteArrayPtr) metoda

Ověřuje podpis dat.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash vypočítaný pro přijatá data. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Podpis, jak byl přijat. |

### Návratová hodnota

True pokud je podpis platný, false jinak.

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Třída [ECDsaBotan](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)