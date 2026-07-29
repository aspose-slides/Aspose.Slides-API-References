---
title: SignData()
second_title: Aspose.Slides för C++ API-referens
description: Beräknar hashvärdet för den angivna dataarrayen och signerar resultatet.
type: docs
weight: 131
url: /sv/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) metod

Beräknar hashvärdet för den angivna dataarrayen och signerar resultatet.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Indata-array. returnerar ECDSA-signatur för indata. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) metod

Beräknar hashvärdet för den angivna dataarrayen och signerar resultatet.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Indata-array. |
| offset | **int32_t** | Offset i **data**. |
| count | **int32_t** | Antal byte som ska användas som indata. returnerar ECDSA-signatur för indata. |

## ECDsaBotan::SignData(const StreamPtr\&) metod

Beräknar hashvärdet för den angivna binära strömmen och signerar resultatet.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binärström. returnerar ECDSA-signatur för indata. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metod

Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen och signerar resultatet.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Indata-array. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. returnerar ECDSA-signatur för indata. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metod

Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen och signerar resultatet.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Indata-array. |
| offset | **int32_t** | Offset i **data**. |
| count | **int32_t** | Antal byte som ska användas som indata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. returnerar ECDSA-signatur för indata. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) metod

Beräknar hashvärdet för den angivna binära strömmen med den angivna hash-algoritmen och signerar resultatet.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binärström. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. returnerar ECDSA-signatur för indata. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klass [ECDsaBotan](../)
* Struktur [HashAlgorithmName](../../hashalgorithmname/)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)