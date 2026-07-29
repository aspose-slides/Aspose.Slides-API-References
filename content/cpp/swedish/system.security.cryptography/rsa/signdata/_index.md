---
title: SignData()
second_title: Aspose.Slides för C++ API-referens
description: Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen och padding, och signerar resultatet.
type: docs
weight: 131
url: /sv/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metod


Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen och padding, och signerar resultatet.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Inmatningsdataarray. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Padding-läge. returnerar [RSA](../) signatur för inmatningsdata. |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metod


Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen och padding, och signerar resultatet.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Inmatningsdataarray. |
| offset | **int32_t** | Offset i **data**. |
| count | **int32_t** | Antal byte som ska användas som indata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Padding-läge. returnerar [RSA](../) signatur för inmatningsdata. |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metod


Beräknar hashvärdet för den angivna binära strömmen med den angivna hash-algoritmen och padding, och signerar resultatet.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binär ström. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Padding-läge. returnerar [RSA](../) signatur för inmatningsdata. |

## Se också

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klass [RSASignaturePadding](../../rsasignaturepadding/)
* Klass [RSA](../)
* Struktur [HashAlgorithmName](../../hashalgorithmname/)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)