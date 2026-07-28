---
title: VerifyHash()
second_title: Aspose.Slides C++ API-referencia
description: Ellenőrzi az adat aláírását.
type: docs
weight: 118
url: /hu/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash(ByteArrayPtr, ByteArrayPtr) metódus


Ellenőrzi az adat aláírását.

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash calculated for received data. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Signature as received. |

### Visszatérési érték

Igaz, ha az aláírás érvényes, hamis egyébként.

## Lásd még

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Osztály [ECDsa](../)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)