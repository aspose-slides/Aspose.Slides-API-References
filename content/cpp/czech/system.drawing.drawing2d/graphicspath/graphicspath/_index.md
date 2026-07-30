---
title: GraphicsPath()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří novou instanci třídy GraphicsPath s určeným režimem výplně.
type: docs
weight: 1
url: /cs/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) constructor


Vytvoří novou instanci třídy [GraphicsPath](../) s určeným režimem výplně.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | Určuje, jak má být vyplněn vnitřek uzavřené cesty reprezentované vytvářeným objektem |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructor


Vytvoří novou instanci objektu [GraphicsPath](../), který představuje zadanou cestu.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Pole obsahující body, které určují cestu, jež má být reprezentována vytvářeným objektem |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole obsahující hodnoty, které určují typy odpovídajících bodů v poli **pts** |
| fillMode | [FillMode](../../fillmode/) | Určuje, jak má být vyplněn vnitřek uzavřené cesty reprezentované vytvářeným objektem |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructor


Vytvoří novou instanci objektu [GraphicsPath](../), který představuje zadanou cestu.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Pole obsahující body, které určují cestu, jež má být reprezentována vytvářeným objektem |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole obsahující hodnoty, které určují typy odpovídajících bodů v poli **pts** |
| fillMode | [FillMode](../../fillmode/) | Určuje, jak má být vyplněn vnitřek uzavřené cesty reprezentované vytvářeným objektem |

## GraphicsPath::GraphicsPath(const SkPath\&) constructor




```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## Viz také

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [GraphicsPath](../)
* Třída [Point](../../../system.drawing/point/)
* Třída [PointF](../../../system.drawing/pointf/)
* Jmenný prostor [System::Drawing::Drawing2D](../../)
* Knihovna [Aspose.Slides](../../../)