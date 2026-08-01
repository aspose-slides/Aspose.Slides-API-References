---
title: SignData()
second_title: Aspose.Slides voor C++ API-referentie
description: Berekent de handtekening van de opgegeven invoerwaarde.
type: docs
weight: 183
url: /nl/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) method


Berekent de handtekening van de opgegeven invoerwaarde.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) om invoergegevens uit te lezen. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hash-algoritme te gebruiken. |

### Retourwaarde

[RSA](../../rsa/) handtekening voor opgegeven gegevens.

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) method


Berekent de handtekening van de opgegeven invoerwaarde.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream om gegevens die worden ondertekend te lezen. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hash-algoritme te gebruiken. |

### Retourwaarde

[RSA](../../rsa/) handtekening voor opgegeven gegevens.

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) method


Berekent de handtekening van de opgegeven invoerwaarde.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) om invoergegevens uit te lezen. |
| offset | **int32_t** | Beginindex van het invoerbuffer-deel. |
| count | **int32_t** | Grootte van het invoerbuffer-deel. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hash-algoritme te gebruiken. |

### Retourwaarde

[RSA](../../rsa/) handtekening voor opgegeven gegevens.

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [RSACryptoServiceProvider](../)
* Klasse [Stream](../../../system.io/stream/)
* Naamruimte [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)