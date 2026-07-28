---
title: GraphicsPath()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy új példányt a GraphicsPath osztályból a megadott kitöltési móddal.
type: docs
weight: 1
url: /hu/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) konstruktor


Létrehozza a(z) [GraphicsPath](../) osztály egy új példányát a megadott kitöltési móddal.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | Megadja, hogyan legyen kitöltve a létrehozandó objektum által ábrázolt zárt útvonal belső része |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) konstruktor


Létrehozza a(z) [GraphicsPath](../) objektum egy új példányát, amely a megadott útvonalat reprezentálja.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Egy tömb, amely a létrehozandó objektum által ábrázolt útvonalat meghatározó pontokat tartalmaz |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Egy tömb, amely a **pts** tömbben lévő megfelelő pontok típusait meghatározó értékeket tartalmaz |
| fillMode | [FillMode](../../fillmode/) | Megadja, hogyan legyen kitöltve a létrehozandó objektum által ábrázolt zárt útvonal belső része |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) konstruktor


Létrehozza a(z) [GraphicsPath](../) objektum egy új példányát, amely a megadott útvonalat reprezentálja.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Egy tömb, amely a létrehozandó objektum által ábrázolt útvonalat meghatározó pontokat tartalmaz |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Egy tömb, amely a **pts** tömbben lévő megfelelő pontok típusait meghatározó értékeket tartalmaz |
| fillMode | [FillMode](../../fillmode/) | Megadja, hogyan legyen kitöltve a létrehozandó objektum által ábrázolt zárt útvonal belső része |

## GraphicsPath::GraphicsPath(const SkPath\&) konstruktor




```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## Lásd még

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [GraphicsPath](../)
* Osztály [Point](../../../system.drawing/point/)
* Osztály [PointF](../../../system.drawing/pointf/)
* Névtere [System::Drawing::Drawing2D](../../)
* Könyvtár [Aspose.Slides](../../../)