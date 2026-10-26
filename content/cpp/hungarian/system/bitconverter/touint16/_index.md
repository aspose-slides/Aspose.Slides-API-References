---
title: ToUInt16()
second_title: Aspose.Slides C++ API referencia
description: Átalakít két bájtot a megadott tömbből a megadott indexnél, egy előjeles nélküli 16 bites egész értékké.
type: docs
weight: 92
url: /hu/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) metódus

Átalakít két bájtot a megadott tömbből a megadott indexnél, egy előjeles nélküli 16 bites egész értékké.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) amely tartalmazza a konvertálandó bájtokat |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok átalakítását elkezdjük |

### Visszatérési érték

Az átalakításból származó előjeles nélküli 16 bites egész érték

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) metódus

Átalakít két bájtot a megadott tömbből a megadott indexnél, egy előjeles nélküli 16 bites egész értékké.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView amely tartalmazza a konvertálandó bájtokat |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok átalakítását elkezdjük |

### Visszatérési érték

Az átalakításból származó előjeles nélküli 16 bites egész érték

## Lásd még

* Típusdefiníció [ArrayPtr](../../arrayptr/)
* Osztály [BitConverter](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)