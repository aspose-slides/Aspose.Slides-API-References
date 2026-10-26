---
title: VerifyHash()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar datasignatur.
type: docs
weight: 222
url: /sv/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) method


Kontrollerar datasignatur.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash beräknad för mottagen data. |
| str | const [String](../../../system/string/)\& | Namn på hash-algoritm som användes. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signatur som mottogs. |

### Returvärde

Sant om signaturen är giltig, annars falskt.

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) method


Verifierar att signaturen för den angivna hash-värdet är giltig.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hashvärde för den signerade datan. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Signaturdata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Utfyllnadsläge. return true om signaturen är giltig, annars - false. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [RSACryptoServiceProvider](../)
* Klass [RSASignaturePadding](../../rsasignaturepadding/)
* Struktur [HashAlgorithmName](../../hashalgorithmname/)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)