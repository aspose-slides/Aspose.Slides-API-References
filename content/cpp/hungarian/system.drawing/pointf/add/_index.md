---
title: Add()
second_title: Aspose.Slides for C++ API-hivatkozás
description: Hozzáadja a megadott SizeF objektum szélesség- és magasságértékeit a megadott PointF objektum X és Y koordinátáinak értékeihez megfelelően.
type: docs
weight: 144
url: /hu/system.drawing/pointf/add/
---
## PointF::Add(const PointF\&, const SizeF\&) metódus

Hozzáadja a megadott [SizeF](../../sizef/) objektum szélesség- és magasságértékeit a megadott [PointF](../) objektum X és Y koordinátáinak értékeihez megfelelően.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | const [PointF](../)\& | A point áthelyezéshez |
| size | const [SizeF](../../sizef/)\& | A [SizeF](../../sizef/) objektum, amely meghatározza az értékeket, amelyeket a **point** koordinátaértékeihez kell hozzáadni |

### Visszatérési érték

Egy új [PointF](../) objektum, amelynek X koordinátája egyenlő a **point** X koordinátájának és a **size** szélességének összegével, Y koordinátája pedig egyenlő a **point** Y koordinátájának és a **size** magasságának összegével.

## PointF::Add(const PointF\&, const Size\&) metódus

Hozzáadja a megadott [Size](../../size/) objektum szélesség- és magasságértékeit a megadott [PointF](../) objektum X és Y koordinátáinak értékeihez megfelelően.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | const [PointF](../)\& | A point áthelyezéshez |
| size | const [Size](../../size/)\& | A [Size](../../size/) objektum, amely meghatározza az értékeket, amelyeket a **point** koordinátaértékeihez kell hozzáadni |

### Visszatérési érték

Egy új [PointF](../) objektum, amelynek X koordinátája egyenlő a **point** X koordinátájának és a **size** szélességének összegével, Y koordinátája pedig egyenlő a **point** Y koordinátájának és a **size** magasságának összegével.

## Lásd még

* Osztály [PointF](../)
* Osztály [SizeF](../../sizef/)
* Osztály [Size](../../size/)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)