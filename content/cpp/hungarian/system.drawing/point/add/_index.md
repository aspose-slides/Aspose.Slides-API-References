---
title: Add()
second_title: Aspose.Slides for C++ API Referencia
description: Hozzáadja a megadott Size objektum szélesség- és magasságértékeit a megadott Point objektum X és Y koordinátáihoz.
type: docs
weight: 183
url: /hu/system.drawing/point/add/
---
## Point::Add(const Point\&, const Size\&) metódus


Hozzáadja a megadott [Size](../../size/) objektum szélesség- és magasságértékeit a megadott [Point](../) objektum X és Y koordinátáihoz.

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | const [Point](../)\& | A pont, amelyet át kell helyezni |
| size | const [Size](../../size/)\& | A [Size](../../size/) objektum, amely meghatározza a koordináták értékeihez hozzáadandó értékeket a **point** számára |

### Visszatérési érték

Új [Point](../) objektum, amelynek X koordináta értéke megegyezik a **point** X koordináta értékének és a **size** szélesség értékének összegével, Y koordináta értéke pedig megegyezik a **point** Y koordináta értékének és a **size** magasság értékének összegével.

## Lásd még

* Osztály [Point](../)
* Osztály [Size](../../size/)
* Névterület [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)