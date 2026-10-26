---
title: UnmanagedMemoryStream()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Tworzy nową instancję UnmanagedMemoryStream.
type: docs
weight: 118
url: /pl/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) konstruktor


Tworzy nową instancję [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pointer | **uint8_t** * | Wskaźnik do niezarządzanego bufora |
| length | **int64_t** | Rozmiar niezarządzanego bufora w bajtach |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) konstruktor


Tworzy nową instancję [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pointer | **uint8_t** * | Wskaźnik do niezarządzanego bufora |
| length | **int64_t** | Rozmiar niezarządzanego bufora w bajtach |
| capacity | **int64_t** | Całkowita ilość pamięci przydzielonej strumieniowi |
| access | [FileAccess](../../fileaccess/) | Określa, czy strumień ma być tylko do odczytu, tylko do zapisu lub oba |

## Zobacz także

* Wyliczenie [FileAccess](../../fileaccess/)
* Klasa [UnmanagedMemoryStream](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)