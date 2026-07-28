---
title: ToUInt64()
second_title: Aspose.Slides for C++ API referencia
description: Átalakítja a megadott tömbben a megadott indexnél kezdődő nyolc bájtot egy előjel nélküli 64 bites egész értékre.
type: docs
weight: 118
url: /hu/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) metódus

Átalakítja a megadott tömbben a megadott indexnél kezdődő nyolc bájtot egy előjel nélküli 64 bites egész értékre.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) amely tartalmazza az átalakítandó bájtokat |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok átalakítását elkezdjük |

### Visszatérési érték

Előjel nélküli 64 bites egész érték, amely az átalakítás eredménye

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) metódus

Átalakítja a megadott tömbben a megadott indexnél kezdődő nyolc bájtot egy előjel nélküli 64 bites egész értékre.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView amely tartalmazza az átalakítandó bájtokat |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok átalakítását elkezdjük |

### Visszatérési érték

Előjel nélküli 64 bites egész érték, amely az átalakítás eredménye

## Lásd még

* Típusdefiníció [ArrayPtr](../../arrayptr/)
* Osztály [BitConverter](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)