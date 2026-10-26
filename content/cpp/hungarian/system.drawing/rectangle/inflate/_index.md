---
title: Inflate()
second_title: Aspose.Slides for C++ API referencia
description: Növeli a jelen objektum által képviselt téglalap szélességét és magasságát, miközben megőrzi a téglalap geometriai középpontjának helyzetét. A szélesség és magasság mindkét irányban a megadott értékekkel nő.
type: docs
weight: 261
url: /hu/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) metódus


Növeli a jelen objektum által képviselt téglalap szélességét és magasságát, miközben megőrzi a téglalap geometriai középpontjának helyzetét. A szélesség és magasság mindkét irányban a megadott értékekkel nő.

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| width | int | A téglalap szélességének mindkét irányban növelésének mértéke |
| height | int | A téglalap magasságának mindkét irányban növelésének mértéke |

## Rectangle::Inflate(const Size\&) metódus


Növeli a jelen objektum által képviselt téglalap szélességét és magasságát, miközben megőrzi a téglalap geometriai középpontjának helyzetét. A szélesség és magasság a megadott méretobjektum szélesség- és magasságértékei által meghatározott összegekkel nőnek megfelelően.

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| size | const [Size](../../size/)\& | [Size](../../size/) objektum, amely meghatározza a téglalap szélességének és magasságának növelésének mértékét |

## Rectangle::Inflate(const Rectangle\&, int, int) metódus


Növeli a megadott objektum által képviselt téglalap szélességét és magasságát, miközben megőrzi a téglalap geometriai középpontjának helyzetét. A szélesség és magasság mindkét irányban a megadott értékekkel nő.

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | A felfújandó téglalap |
| x | int | A téglalap szélességének mindkét irányban növelésének mértéke |
| y | int | A téglalap magasságának mindkét irányban növelésének mértéke |

### Visszatérési érték

[Rectangle](../) objektum, amely a megnövelt téglalapot reprezentálja

## Lásd még

* Osztály [Rectangle](../)
* Osztály [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)