---
title: ToDouble()
second_title: Aspose.Slides for C++ API Referenciája
description: Átalakítja a megadott tömb nyolc bájtját a megadott indexnél kezdődően double pontosságú lebegőpontos értékké.
type: docs
weight: 144
url: /hu/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) method

Átalakítja a megadott tömb nyolc bájtját a megadott indexnél kezdődően double pontosságú lebegőpontos értékké.

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) amely a konvertálandó bájtokat tartalmaz |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok konvertálását meg kell kezdeni |

### Visszatérési érték

Double pontosságú lebegőpontos érték, amely a konvertálás eredménye

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) method

Átalakítja a megadott tömb nyolc bájtját a megadott indexnél kezdődően double pontosságú lebegőpontos értékké.

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, amely a konvertálandó bájtokat tartalmazza |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok konvertálását meg kell kezdeni |

### Visszatérési érték

Double pontosságú lebegőpontos érték, amely a konvertálás eredménye

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [BitConverter](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)