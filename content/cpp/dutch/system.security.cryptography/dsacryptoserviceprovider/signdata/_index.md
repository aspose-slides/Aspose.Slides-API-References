---
title: SignData()
second_title: Aspose.Slides voor C++ API-referentie
description: Berekent de handtekening van de opgegeven invoerwaarde.
type: docs
weight: 183
url: /nl/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) methode


Berekent de handtekening van de opgegeven invoerwaarde.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) om invoergegevens van te lezen. |

### Retourwaarde

[DSA](../../dsa/) handtekening voor de opgegeven gegevens.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) methode


Berekent de handtekening van de opgegeven invoerwaarde.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream om de te ondertekenen gegevens van te lezen. |

### Retourwaarde

[DSA](../../dsa/) handtekening voor de opgegeven gegevens.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) methode


Berekent de handtekening van de opgegeven invoerwaarde.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) om invoergegevens van te lezen. |
| offset | **int32_t** | Beginindex van het invoerbuffersegment. |
| count | **int32_t** | Grootte van het invoerbuffersegment. |

### Retourwaarde

[DSA](../../dsa/) handtekening voor de opgegeven gegevens.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) methode


Berekent de hashwaarde van de opgegeven gegevensarray met behulp van het opgegeven hash-algoritme en ondertekent het resultaat.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Invoergegevensarray. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. retourneert [DSA](../../dsa/) handtekening voor de invoergegevens. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) methode


Berekent de hashwaarde van de opgegeven gegevensarray met behulp van het opgegeven hash-algoritme en ondertekent het resultaat.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Invoergegevensarray. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Aantal bytes dat als invoergegevens wordt gebruikt. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. retourneert [DSA](../../dsa/) handtekening voor de invoergegevens. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) methode


Berekent de hashwaarde van de opgegeven binaire stream met behulp van het opgegeven hash-algoritme en ondertekent het resultaat.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binaire stream. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. retourneert [DSA](../../dsa/) handtekening voor de invoergegevens. |

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSACryptoServiceProvider](../)
* Class [Stream](../../../system.io/stream/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)