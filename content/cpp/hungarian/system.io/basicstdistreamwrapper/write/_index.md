---
title: Write()
second_title: Aspose.Slides C++ API Hivatkozás
description: Ha a csomagolási mód bináris, a megadott bájttömbből a megadott részintervallumot írja a streambe, egyébként a megadott bájttömbből a megadott részintervallumot átalakítja char_type típusra, majd az eredményt írja a streambe. Nem támogatott!
type: docs
weight: 79
url: /hu/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus

Ha a csomagolási mód bináris, a megadott bájttömbből a megadott részintervallumot írja a streambe, egyébként a megadott bájttömbből a megadott részintervallumot átalakítja char_type típusra, majd az eredményt írja a streambe. Nem támogatott!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The array containing the bytes to write. |
| offset | **int32_t** | A 0-based index of the elemnet in **buffer** at which the subrange to write begins. |
| count | **int32_t** | The number of elements in the subrange to write. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metódus

A megadott bájttömbből a megadott részintervallumot írja a streambe.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | The array view containing the bytes to write |
| offset | **int32_t** | A 0-based index of the element in **buffer** at which the subrange to write begins |
| count | **int32_t** | The number of elements in the subrange to write |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [BasicSTDIStreamWrapper](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)