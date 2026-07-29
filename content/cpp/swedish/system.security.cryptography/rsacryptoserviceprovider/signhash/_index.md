---
title: SignHash()
second_title: Aspose.Slides för C++ API-referens
description: Beräknar signaturen för det angivna hashvärdet.
type: docs
weight: 196
url: /sv/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) metod


Beräknar signaturen för det angivna hashvärdet.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hashvärde. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hashalgoritm. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Padding-läge. returnerar [RSA](../../rsa/) signatur för den angivna hashen. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) metod


Beräknar signaturen för det angivna inmatningsvärdet. Inte implementerad.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hashvärde för data som ska signeras. |
| str | const [String](../../../system/string/)\& | Hashalgoritm-identifierare som används för att skapa hashen. |

### Returvärde

[RSA](../../rsa/) signatur för angiven data.

## Se även

* Typdefinition [ByteArrayPtr](../../../system/bytearrayptr/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [RSASignaturePadding](../../rsasignaturepadding/)
* Klass [RSACryptoServiceProvider](../)
* Klass [String](../../../system/string/)
* Struktur [HashAlgorithmName](../../hashalgorithmname/)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)