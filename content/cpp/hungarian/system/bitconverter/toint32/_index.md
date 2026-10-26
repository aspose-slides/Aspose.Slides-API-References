---
title: ToInt32()
second_title: Aspose.Slides C++ API hivatkozás
description: Négy bájtot konvertál a megadott tömbből a megadott indexnél kezdve egy 32 bites egész értékre.
type: docs
weight: 66
url: /hu/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) metódus

Négy bájtot konvertál a megadott tömbből a megadott indexnél kezdve egy 32 bites egész értékre.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) amely tartalmazza a konvertálandó bájtokat |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok átalakítását elkezdjük |

### Visszatérési érték

32-bits egész érték, amely a konverzió eredménye

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) metódus

Négy bájtot konvertál a megadott tömbből a megadott indexnél kezdve egy 32 bites egész értékre.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, amely tartalmazza a konvertálandó bájtokat |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok átalakítását elkezdjük |

### Visszatérési érték

32-bits egész érték, amely a konverzió eredménye

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [BitConverter](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)