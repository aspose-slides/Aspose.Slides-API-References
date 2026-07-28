---
title: UnmanagedMemoryStream()
second_title: Aspose.Slides C++ API referencia
description: Új példányt hoz létre az UnmanagedMemoryStream osztályból.
type: docs
weight: 118
url: /hu/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) konstruktor

Új példányt hoz létre a(z) [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pointer | **uint8_t** * | Mutató a nem kezelt pufferhez |
| length | **int64_t** | A nem kezelt puffer mérete bájtokban |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) konstruktor

Új példányt hoz létre a(z) [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pointer | **uint8_t** * | Mutató a nem kezelt pufferhez |
| length | **int64_t** | A nem kezelt puffer mérete bájtokban |
| capacity | **int64_t** | A streamnek kiosztott memória teljes mennyisége |
| access | [FileAccess](../../fileaccess/) | Megadja, hogy a stream csak olvasható, csak írásra vagy mindkettő legyen |

## Lásd még

* Enum [FileAccess](../../fileaccess/)
* Class [UnmanagedMemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)