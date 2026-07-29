---
title: SignData()
second_title: Aspose.Slides för C++ API-referens
description: Beräknar signaturen för det specificerade indatavärdet.
type: docs
weight: 183
url: /sv/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) method


Beräknar signaturen för det angivna indatavärdet.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) för att läsa indata från. |

### Returvärde

[DSA](../../dsa/) signatur för angivna data.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) method


Beräknar signaturen för det angivna indatavärdet.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Ström för att läsa data som ska signeras från. |

### Returvärde

[DSA](../../dsa/) signatur för angivna data.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) method


Beräknar signaturen för det angivna indatavärdet.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) för att läsa indata från. |
| offset | **int32_t** | Startindex för inmatningsbuffertens del. |
| count | **int32_t** | Storlek för inmatningsbuffertens del. |

### Returvärde

[DSA](../../dsa/) signatur för angivna data.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method


Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen och signerar resultatet.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Indatadatararray. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. returnerar [DSA](../../dsa/) signatur för indata. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method


Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen och signerar resultatet.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Indatadatararray. |
| offset | **int32_t** | Offset i **data**. |
| count | **int32_t** | Antal byte som ska användas som indata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. returnerar [DSA](../../dsa/) signatur för indata. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) method


Beräknar hashvärdet för det angivna binära flödet med den angivna hash-algoritmen och signerar resultatet.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binärt flöde. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. returnerar [DSA](../../dsa/) signatur för indata. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klass [DSACryptoServiceProvider](../)
* Klass [Stream](../../../system.io/stream/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namnrymd [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)