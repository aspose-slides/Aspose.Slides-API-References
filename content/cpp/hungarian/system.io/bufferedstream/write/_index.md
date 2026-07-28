---
title: Write()
second_title: Aspose.Slides C++ API hivatkozás
description: A megadott bájttömbből a megadott bájtok al-tartományát írja az alapul szolgáló streambe.
type: docs
weight: 66
url: /hu/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

A megadott bájtok al-tartományát írja a megadott bájt tömbből az alapul szolgáló streambe.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájtokat tartalmazó tömb |
| offset | **int32_t** | Az **buffer**-ben lévő elem 0-alapú indexe, ahol a írandó részintervallum kezdődik |
| count | **int32_t** | Az írandó részintervallum elemeinek száma |

## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

A megadott bájtok al-tartományát írja a megadott bájt tömbből az alapul szolgáló streambe.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A bájtokat tartalmazó tömb |
| offset | **int32_t** | Az **buffer**-ben lévő elem 0-alapú indexe, ahol a írandó részintervallum kezdődik |
| count | **int32_t** | Az írandó részintervallum elemeinek száma |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [BufferedStream](../)
* Névtere [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)