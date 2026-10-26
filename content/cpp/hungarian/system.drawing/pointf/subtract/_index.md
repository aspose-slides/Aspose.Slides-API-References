---
title: Subtract()
second_title: Aspose.Slides C++ API Referenciája
description: Kivonja a megadott SizeF objektum szélesség- és magasságértékeit a megadott PointF objektum X és Y koordinátaértékeiből megfelelően.
type: docs
weight: 157
url: /hu/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) metódus


Kivonja a megadott [SizeF](../../sizef/) objektum szélesség- és magasságértékeit a megadott [PointF](../) objektum X és Y koordinátaértékeiből megfelelően.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | const [PointF](../)\& | A pont, amelyet át kell helyezni |
| size | const [SizeF](../../sizef/)\& | A [SizeF](../../sizef/) objektum, amely megadja az értékeket, amelyeket a **point** koordinátaértékeiből kell levonni |

### Visszatérési érték

Egy új [PointF](../) objektum, amelynek X koordinátaértéke megegyezik a **size** szélesség-értékének **point** X koordinátaértékéből történő kivonásának eredményével, és Y koordinátaértéke megegyezik a **size** magasság-értékének **point** Y koordinátaértékéből történő kivonásának eredményével.

## PointF::Subtract(const PointF\&, const Size\&) metódus


Kivonja a megadott [Size](../../size/) objektum szélesség- és magasságértékeit a megadott [PointF](../) objektum X és Y koordinátaértékeiből megfelelően.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | const [PointF](../)\& | A pont, amelyet át kell helyezni |
| size | const [Size](../../size/)\& | A [Size](../../size/) objektum, amely megadja az értékeket, amelyeket a **point** koordinátaértékeiből kell levonni |

### Visszatérési érték

Egy új [PointF](../) objektum, amelynek X koordinátaértéke megegyezik a **size** szélesség-értékének **point** X koordinátaértékéből történő kivonásának eredményével, és Y koordinátaértéke megegyezik a **size** magasság-értékének **point** Y koordinátaértékéből történő kivonásának eredményével.

## Lásd még

* Osztály [PointF](../)
* Osztály [SizeF](../../sizef/)
* Osztály [Size](../../size/)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)