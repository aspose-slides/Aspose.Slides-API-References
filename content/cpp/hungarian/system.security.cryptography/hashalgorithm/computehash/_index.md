---
title: ComputeHash()
second_title: Aspose.Slides C++ API referencia
description: Hash-eli a puffert.
type: docs
weight: 14
url: /hu/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) metódus


Hash-eli a puffert.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Forrás puffer. |

### Visszatérési érték

Kiszámított hash érték.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) metódus


Hash-eli a puffer szeletet.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Forrás puffer. |
| offset | int | Eltolás a forrás pufferen. |
| count | int | A forrás pufferből felhasználandó bájtok száma. |

### Visszatérési érték

Kiszámított hash érték.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) metódus


Olvas adatfolyamot a végéig, és kiszámítja a beolvasott adatok hash-értékét.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | Az adatfolyam, amelyből olvasni kell. |

### Visszatérési érték

A teljes adatfolyam adatainak kiszámított hash-értéke.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)