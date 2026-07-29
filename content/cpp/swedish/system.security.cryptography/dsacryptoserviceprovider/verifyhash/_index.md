---
title: VerifyHash()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar datasignatur.
type: docs
weight: 222
url: /sv/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) metod

Kontrollerar datasignatur.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash beräknad för mottagen data. |
| str | const [String](../../../system/string/)\& | Namn på den använda hashalgoritmen. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signatur som mottogs. |

### Returvärde

Sant om signaturen är giltig, falskt annars.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klass [String](../../../system/string/)
* Klass [DSACryptoServiceProvider](../)
* Namnrymd [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)