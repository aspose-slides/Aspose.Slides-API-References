---
title: ComputeHash()
second_title: Aspose.Slides voor C++ API-referentie
description: Hasht de buffer.
type: docs
weight: 14
url: /nl/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) methode


Hasht de buffer.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bronbuffer. |

### Retourwaarde

Berekende hashwaarde.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) methode


Hasht een buffersegment.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bronbuffer. |
| offset | int | Offset in de bronbuffer. |
| count | int | Aantal bytes te gebruiken uit de bronbuffer. |

### Retourwaarde

Berekende hashwaarde.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) methode


Leest de stream tot het einde en berekent de hash van de gelezen gegevens.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | Stream om gegevens van te lezen. |

### Retourwaarde

Berekende hashwaarde voor alle gegevens van de stream.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [HashAlgorithm](../)
* Klasse [Stream](../../../system.io/stream/)
* Namespace [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)