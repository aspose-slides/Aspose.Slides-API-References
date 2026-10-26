---
title: SignHash()
second_title: Aspose.Slides för C++ API-referens
description: Beräknar signaturen för angivet inmatningsvärde.
type: docs
weight: 196
url: /sv/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) metod


Beräknar signaturen för det angivna inmatningsvärdet.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hashvärde för data som ska signeras. |
| str | const [String](../../../system/string/)\& | Identifierare för hash-algoritm som används för att skapa hashen. |

### Returvärde

[DSA](../../dsa/) signatur för specificerad data.

## Se också

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klass [String](../../../system/string/)
* Klass [DSACryptoServiceProvider](../)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)