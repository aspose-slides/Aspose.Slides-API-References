---
title: VerifyHash()
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje podpis dat.
type: docs
weight: 118
url: /cs/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash(ByteArrayPtr, ByteArrayPtr) metoda

Kontroluje podpis dat.

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash vypočítaný pro přijatá data. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Podpis tak, jak byl přijat. |

### Návratová hodnota

True pokud je podpis platný, false jinak.

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsa](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)