---
title: SignData()
second_title: Aspose.Slides för C++ API-referens
description: Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen och signerar resultatet.
type: docs
weight: 79
url: /sv/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method

Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen och signerar resultatet.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Indata-array. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. return ECDSA signature for the input data. |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method

Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen och signerar resultatet.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Indata-array. |
| offset | **int32_t** | Offset i **data**. |
| count | **int32_t** | Antal byte att använda som indataström. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. return ECDSA signature for the input data. |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) method

Beräknar hashvärdet för den angivna binära strömmen med den angivna hash-algoritmen och signerar resultatet.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binär ström. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. return ECDSA signature for the input data. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klass [ECDsa](../)
* Struktur [HashAlgorithmName](../../hashalgorithmname/)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)