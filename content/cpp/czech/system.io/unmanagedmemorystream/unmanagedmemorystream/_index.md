---
title: UnmanagedMemoryStream()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří novou instanci UnmanagedMemoryStream.
type: docs
weight: 118
url: /cs/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) konstruktor

Vytvoří novou instanci [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pointer | **uint8_t** * | Ukazatel na neřízený buffer |
| length | **int64_t** | Velikost neřízeného bufferu v bajtech |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) konstruktor

Vytvoří novou instanci [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pointer | **uint8_t** * | Ukazatel na neřízený buffer |
| length | **int64_t** | Velikost neřízeného bufferu v bajtech |
| capacity | **int64_t** | Celková velikost paměti přidělené streamu |
| access | [FileAccess](../../fileaccess/) | Určuje, zda má být stream jen pro čtení, jen pro zápis nebo oba |

## Viz také

* Enum [FileAccess](../../fileaccess/)
* Třída [UnmanagedMemoryStream](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)