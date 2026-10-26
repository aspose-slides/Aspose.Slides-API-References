---
title: Write()
second_title: Aspose.Slides for C++ API-referencia
description: Ha a becsomagolási mód bináris, akkor a megadott byte tömb adott részét írja a folyamra, egyébként a megadott byte tömb adott részét char_type típusra konvertálja, majd az eredményt írja a folyamra.
type: docs
weight: 79
url: /hu/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Ha a becsomagolási mód bináris, akkor a megadott byte tömb adott részét írja a folyamra, egyébként a megadott byte tömb adott részét char_type típusra konvertálja, majd az eredményt írja a folyamra.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A byte-okat tartalmazó tömb |
| offset | **int32_t** | A **buffer** elemének 0-alapú indexe, ahol a írandó rész kezdődik |
| count | **int32_t** | A írandó rész elemeinek száma |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

A megadott byte tömb adott részét írja a folyamra.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A byte-okat tartalmazó tömb nézet |
| offset | **int32_t** | A **buffer** elemének 0-alapú indexe, ahol a írandó rész kezdődik |
| count | **int32_t** | A írandó rész elemeinek száma |

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [BasicSTDOStreamWrapper](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)