---
title: Write()
second_title: Aspose.Slides C++ API hivatkozás
description: A megadott bájttömbből a meghatározott bájt részhalmazt írja a folyamra.
type: docs
weight: 92
url: /hu/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus

Az adott bájttömbből a megadott bájt részhalmazt írja a folyamra.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A tömb, amely a írandó bájtokat tartalmazza |
| offset | **int32_t** | 0-alapú index a **buffer**-ben, ahol a írandó részhalmaz kezdődik |
| count | **int32_t** | Az írandó részhalmaz elemeinek száma |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metódus

Az adott bájttömbből a megadott bájt részhalmazt írja a folyamra.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A tömbnézet, amely a írandó bájtokat tartalmazza |
| offset | **int32_t** | 0-alapú index a **buffer**-ben, ahol a írandó részhalmaz kezdődik |
| count | **int32_t** | Az írandó részhalmaz elemeinek száma |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [MemoryStream](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)