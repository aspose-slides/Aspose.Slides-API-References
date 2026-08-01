---
title: VerifyData()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert de handtekening van de gegevens.
type: docs
weight: 209
url: /nl/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) method


Controleert de handtekening van de gegevens.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) om de handtekening te controleren. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hash-algoritme om te gebruiken. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekening zoals ontvangen. |

### Retourwaarde

True if signature is valid, false otherwise.

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)