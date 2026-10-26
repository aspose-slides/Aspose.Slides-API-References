---
title: ComputeHash()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří hash bufferu.
type: docs
weight: 14
url: /cs/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) metoda


Vytvoří hash bufferu.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Zdrojový buffer. |

### Návratová hodnota

Vypočtená hodnota hashe.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) metoda


Vytvoří hash úseku bufferu.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Zdrojový buffer. |
| offset | int | Posun ve zdrojovém bufferu. |
| count | int | Počet bajtů použitých ze zdrojového bufferu. |

### Návratová hodnota

Vypočtená hodnota hashe.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) metoda


Čte stream až do konce a vypočítá hash pro přečtená data.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | Stream, ze kterého se čtou data. |

### Návratová hodnota

Vypočtená hodnota hashe pro všechna data streamu.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)