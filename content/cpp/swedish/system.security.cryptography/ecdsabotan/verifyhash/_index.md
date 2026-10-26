---
title: VerifyHash()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar datasignatur.
type: docs
weight: 183
url: /sv/system.security.cryptography/ecdsabotan/verifyhash/
---
## ECDsaBotan::VerifyHash(ByteArrayPtr, ByteArrayPtr) metod

Kontrollerar datasignatur.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash beräknad för mottagen data. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Signatur som mottogs. |

### Returvärde

Sant om signaturen är giltig, annars falskt.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klass [ECDsaBotan](../)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)