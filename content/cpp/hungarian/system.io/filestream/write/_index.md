---
title: Write()
second_title: Aspose.Slides for C++ API referencia
description: A megadott bájt tömbből a megadott részarányú bájtokat a folyamra írja.
type: docs
weight: 248
url: /hu/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus

A megadott bájt tömbből a megadott részarányú bájtokat a folyamra írja.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Az írandó bájtokat tartalmazó tömb. |
| offset | **int32_t** | A **buffer** tömbben a 0-bázisú index, ahol a írandó részarány kezdődik. |
| count | **int32_t** | Az írandó részarány elemeinek száma. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metódus

A megadott bájt tömbből a megadott részarányú bájtok a folyamra írásra kerülnek.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Az írandó bájtokat tartalmazó tömbnézet. |
| offset | **int32_t** | A **buffer** tömbben a 0-bázisú index, ahol a írandó részarány kezdődik. |
| count | **int32_t** | Az írandó részarány elemeinek száma. |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [FileStream](../)
* Névtere [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)