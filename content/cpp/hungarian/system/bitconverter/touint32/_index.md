---
title: ToUInt32()
second_title: Aspose.Slides for C++ API referencia
description: Négy bájtot konvertál a megadott tömbből a megadott indexnél kezdve unsigned 32 bites egész értékké.
type: docs
weight: 105
url: /hu/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) metódus

Négy bájtot konvertál a megadott tömbből a megadott indexnél kezdve unsigned 32 bites egész értékké.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) ami a konvertálandó bájtokat tartalmaz |
| startIndex | int | [Index](../../index/) az index a tömbben, ahol a bájtok konvertálását elkezdjük |

### Visszatérési érték

Az átalakítás eredményeként kapott unsigned 32 bites egész érték

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) metódus

Négy bájtot konvertál a megadott tömbből a megadott indexnél kezdve unsigned 32 bites egész értékké.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView ami a konvertálandó bájtokat tartalmaz |
| startIndex | int | [Index](../../index/) az index a tömbben, ahol a bájtok konvertálását elkezdjük |

### Visszatérési érték

Az átalakítás eredményeként kapott unsigned 32 bites egész érték

## Lásd még

* Típusdefiníció [ArrayPtr](../../arrayptr/)
* Osztály [BitConverter](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)