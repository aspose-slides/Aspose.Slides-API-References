---
title: ToChar()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott tömbből a megadott indexnél kezdődő két bájtot char_t értékké.
type: docs
weight: 40
url: /hu/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) metódus

Átalakítja a megadott tömbből a megadott indexnél kezdődő két bájtot char_t értékké.

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) amely tartalmazza a konvertálandó bájtokat |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok átvétele kezdődik |

### Visszatérési érték

char_t érték, amely a konverzió eredménye

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) metódus

Átalakítja a megadott tömbből a megadott indexnél kezdődő két bájtot char_t értékké.

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView amely tartalmazza a konvertálandó bájtokat |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok átvétele kezdődik |

### Visszatérési érték

char_t érték, amely a konverzió eredménye

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [BitConverter](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)