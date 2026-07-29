---
title: SignData()
second_title: Aspose.Slides för C++ API-referens
description: Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen och signerar resultatet.
type: docs
weight: 79
url: /sv/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metod

Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen och signerar resultatet.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Indata-array. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. returnerar [DSA](../) signatur för indata. |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metod

Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen och signerar resultatet.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Indata-array. |
| offset | **int32_t** | Offset i **data**. |
| count | **int32_t** | Antal byte som ska användas som indata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. returnerar [DSA](../) signatur för indata. |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) metod

Beräknar hashvärdet för den angivna binära strömmen med den angivna hash-algoritmen och signerar resultatet.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binär ström. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. returnerar [DSA](../) signatur för indata. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klass [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namnrymd [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)