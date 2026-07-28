---
title: RectangleF()
second_title: Aspose.Slides C++ API Referenciája
description: Létrehoz egy új RectangleF objektumot, amely egy olyan téglalapot képvisel, amelynek X és Y koordinátái, valamint szélessége és magassága 0-ra van állítva.
type: docs
weight: 1
url: /hu/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() konstruktor

Létrehoz egy új [RectangleF](../) objektumot, amely egy olyan téglalapot képvisel, amelynek X és Y koordinátái, valamint szélessége és magassága 0-ra van állítva.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) konstruktor

Létrehoz egy új [RectangleF](../) objektumot, amely egy olyan téglalapot képvisel, amelynek bal felső sarkának megadott koordinátái, valamint szélessége és magassága vannak.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | A téglalap bal felső sarkának X koordinátájának értéke |
| y | **float** | A téglalap bal felső sarkának Y koordinátájának értéke |
| width | **float** | A téglalap szélessége |
| height | **float** | A téglalap magassága |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) konstruktor

Létrehoz egy új [RectangleF](../) objektumot, amely egy olyan téglalapot képvisel, amelynek bal felső sarkának koordinátái [PointF](../../pointf/) osztályú példányként, szélessége és magassága [SizeF](../../sizef/) osztályú példányként vannak megadva.

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | A téglalap bal felső sarkának helyét adja meg |
| size | const [SizeF](../../sizef/)\& | A téglalap szélességét és magasságát adja meg |

## RectangleF::RectangleF(const Rectangle\&) konstruktor

Létrehoz egy új [RectangleF](../) objektumot, amely egy olyan téglalapot képvisel, amely megegyezik a megadott téglalappal.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Egy [Rectangle](../../rectangle/) osztályú példány, amely megadja a téglalap pozícióját és méretét, amelyet a létrehozandó objektum képvisel |

## Lásd még

* Osztály [RectangleF](../)
* Osztály [PointF](../../pointf/)
* Osztály [SizeF](../../sizef/)
* Osztály [Rectangle](../../rectangle/)
* Névterület [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)