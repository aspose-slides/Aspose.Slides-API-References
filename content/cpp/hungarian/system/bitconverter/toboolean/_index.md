---
title: ToBoolean()
second_title: Aspose.Slides C++ API Referencia
description: Átalakít egy bájtot a megadott tömbből a megadott indexnél logikai értékké.
type: docs
weight: 27
url: /hu/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) metódus

Átalakít egy bájtot a megadott tömbből a megadott indexnél logikai értékké.

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Paraméterek

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) amely a konvertálandó bájtokat tartalmazza |
| startIndex | int | [Index](../../index/) a tömbben, ahol a konvertáláshoz a bájtok átvétele kezdődik |

### Visszatérési érték

[Boolean](../../boolean/) érték, amely a konverzió eredménye

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) metódus

Átalakít egy bájtot a megadott tömbből a megadott indexnél logikai értékké.

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Paraméterek

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView amely a konvertálandó bájtokat tartalmazza |
| startIndex | int | [Index](../../index/) a tömbben, ahol a konvertáláshoz a bájtok átvétele kezdődik |

### Visszatérési érték

[Boolean](../../boolean/) érték, amely a konverzió eredménye

## Lásd még

* Típusdefiníció [ArrayPtr](../../arrayptr/)
* Osztály [BitConverter](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)