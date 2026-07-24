---
title: VerifyData()
second_title: Aspose.Slides für C++ API Referenz
description: Überprüft die Signatur der Daten.
type: docs
weight: 209
url: /de/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) Methode


Überprüft die Signatur der Daten.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) zum Prüfen der Signatur für. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hash-Algorithmus, der verwendet werden soll. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Erhaltene Signatur. |

### Rückgabewert

True, wenn die Signatur gültig ist, andernfalls false.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [RSACryptoServiceProvider](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)