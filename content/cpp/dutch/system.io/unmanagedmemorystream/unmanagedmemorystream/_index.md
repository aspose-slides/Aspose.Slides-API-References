---
title: UnmanagedMemoryStream()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar van UnmanagedMemoryStream.
type: docs
weight: 118
url: /nl/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) constructor

Construeert een nieuw exemplaar van [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pointer | **uint8_t** * | Een pointer naar een niet-beheerde buffer |
| length | **int64_t** | De grootte van de niet-beheerde buffer in bytes |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) constructor

Construeert een nieuw exemplaar van [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pointer | **uint8_t** * | Een pointer naar een niet-beheerde buffer |
| length | **int64_t** | De grootte van de niet-beheerde buffer in bytes |
| capacity | **int64_t** | De totale hoeveelheid geheugen die aan de stream is toegewezen |
| access | [FileAccess](../../fileaccess/) | Specificeert of de stream alleen-lezen, alleen-schrijven of beide moet zijn |

## Zie ook

* Enum [FileAccess](../../fileaccess/)
* Klasse [UnmanagedMemoryStream](../)
* Namespace [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)