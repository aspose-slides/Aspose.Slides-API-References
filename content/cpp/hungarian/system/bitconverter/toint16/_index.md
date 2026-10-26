---
title: ToInt16()
second_title: Aspose.Slides C++ API referencia
description: Átalakít két bájtot a megadott tömbből a megadott indexről 16 bites egész értékké.
type: docs
weight: 53
url: /hu/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) method

Átalakít két bájtot a megadott tömbből a megadott indexről 16 bites egész értékké.

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) amely tartalmazza a konvertálandó bájtokat |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok átalakítását el kell kezdeni |

### Visszatérési érték

16 bites egész érték, amely az átalakítás eredménye

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) method

Átalakít két bájtot a megadott tömbből a megadott indexről 16 bites egész értékké.

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView amely tartalmazza a konvertálandó bájtokat |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok átalakítását el kell kezdeni |

### Visszatérési érték

16 bites egész érték, amely az átalakítás eredménye

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [BitConverter](../)
* Névtér [System](../../)
* Library [Aspose.Slides](../../../)