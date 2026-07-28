---
title: ToInt64()
second_title: Aspose.Slides for C++ API referencia
description: Átalakítja a megadott tömbből a megadott indexnél kezdődő nyolc bájtot 64-bites egész értékké.
type: docs
weight: 79
url: /hu/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) metódus

Átalakítja a megadott tömbből a megadott indexnél kezdődő nyolc bájtot 64-bites egész értékké.

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) amely tartalmazza a konvertálandó bájtokat |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok átalakítását elkezdjük |

### Visszatérési érték

64-bites egész érték a konverzió eredményeként

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) metódus

Átalakítja a megadott tömbből a megadott indexnél kezdődő nyolc bájtot 64-bites egész értékké.

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView amely tartalmazza a konvertálandó bájtokat |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok átalakítását elkezdjük |

### Visszatérési érték

64-bites egész érték a konverzió eredményeként

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [BitConverter](../)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)