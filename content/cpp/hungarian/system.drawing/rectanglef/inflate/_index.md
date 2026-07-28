---
title: Inflate()
second_title: Aspose.Slides C++ API Referencia
description: Növeli a jelen objektum által képviselt téglalap szélességét és magasságát, miközben megőrzi a téglalap geometriai középpontjának helyét. A szélesség és a magasság mindkét irányban a megadott értékekkel növekszik.
type: docs
weight: 261
url: /hu/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) metódus

Növeli a jelen objektum által képviselt téglalap szélességét és magasságát, miközben megőrzi a téglalap geometriai középpontjának helyét. A szélesség és a magasság mindkét irányban a megadott értékekkel növekszik.

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| width | **float** | Az a mennyiség, amellyel a téglalap szélessége mindkét irányban növekszik |
| height | **float** | Az a mennyiség, amellyel a téglalap magassága mindkét irányban növekszik |

## RectangleF::Inflate(const SizeF\&) metódus

Növeli a jelen objektum által képviselt téglalap szélességét és magasságát, miközben megőrzi a téglalap geometriai középpontjának helyét. A szélesség és a magasság mindkét irányban a megadott méretobjektum szélesség- és magasságértékei által meghatározott mértékben növekszik.

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | A [SizeF](../../sizef/) objektum, amely meghatározza a téglalap szélességének és magasságának növelésének mennyiségét |

## RectangleF::Inflate(const RectangleF\&, float, float) metódus

Növeli a megadott objektum által képviselt téglalap szélességét és magasságát, miközben megőrzi a téglalap geometriai középpontjának helyét. A szélesség és a magasság mindkét irányban a megadott értékekkel növekszik.

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | A felfújandó téglalap |
| x | **float** | Az a mennyiség, amellyel a téglalap szélessége mindkét irányban növekszik |
| y | **float** | Az a mennyiség, amellyel a téglalap magassága mindkét irányban növekszik |

### Visszatérési érték

A [RectangleF](../) objektum, amely a megnövelt téglalapot képviseli

## Lásd még

* Osztály [RectangleF](../)
* Osztály [SizeF](../../sizef/)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)