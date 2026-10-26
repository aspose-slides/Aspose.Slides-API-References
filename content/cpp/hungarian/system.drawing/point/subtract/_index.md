---
title: Subtract()
second_title: Aspose.Slides for C++ API Referenciája
description: A megadott Size objektum szélesség- és magasságértékeit levonja a megadott Point objektum X és Y koordinátaértékeiből megfelelően.
type: docs
weight: 196
url: /hu/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) metódus


A megadott [Size](../../size/) objektum szélesség- és magasságértékeit levonja a megadott [Point](../) objektum X és Y koordinátaértékeiből megfelelően.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | const [Point](../)\& | A fordítandó pont |
| size | const [Size](../../size/)\& | [Size](../../size/) objektum, amely meghatározza a **point** koordinátáiból levonandó értékeket |

### Visszatérési érték

Egy új [Point](../) objektum, amelynek X koordinátaértéke megegyezik a **size** szélességértékének **point** X koordinátaértékéből történt kivonás eredményével, és Y koordinátaértéke megegyezik a **size** magasságértékének **point** Y koordinátaértékéből történt kivonás eredményével.

## Lásd még

* Osztály [Point](../)
* Osztály [Size](../../size/)
* Névtere [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)