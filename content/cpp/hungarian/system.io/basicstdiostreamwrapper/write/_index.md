---
title: Write()
second_title: Aspose.Slides for C++ API referencia
description: Ha a csomagolási mód bináris, a megadott bájt tömbből a megadott bájt alrészletet írja a folyamra, egyébként a megadott bájt alrészletet a megadott bájt tömbből char_type típusra konvertálja, majd az eredményt írja a folyamra.
type: docs
weight: 79
url: /hu/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Ha a csomagolási mód bináris, akkor a megadott bájtosorozat megadott részletét írja a folyamra a megadott bájt tömbből, egyébként a megadott részletet a megadott bájt tömbből char_type típusra konvertálja, majd az eredményt írja a folyamra.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A tömb, amely a írni kívánt bájtokat tartalmazza |
| offset | **int32_t** | A **buffer**-ben lévő elem 0-alapú indexe, ahol a írni kívánt részlet kezdődik |
| count | **int32_t** | Az írni kívánt részletben lévő elemek száma |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

A megadott bájt tömbből a megadott részletet írja a folyamra.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A tömbnézet, amely a írni kívánt bájtokat tartalmazza |
| offset | **int32_t** | A **buffer**-ben lévő elem 0-alapú indexe, ahol a írni kívánt részlet kezdődik |
| count | **int32_t** | Az írni kívánt részletben lévő elemek száma |

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [BasicSTDIOStreamWrapper](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)