---
title: GraphicsPath()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruiert eine neue Instanz der GraphicsPath Klasse mit dem angegebenen Füllmodus.
type: docs
weight: 1
url: /de/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) Konstruktor

Konstruiert eine neue Instanz der [GraphicsPath](../) Klasse mit dem angegebenen Füllmodus.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | Gibt an, wie das Innere des vom zu erstellenden Objekt dargestellten geschlossenen Pfads gefüllt werden soll |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) Konstruktor

Konstruiert eine neue Instanz des [GraphicsPath](../) Objekts, das den angegebenen Pfad darstellt.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Ein Array, das die Punkte enthält, die den vom zu erstellenden Objekt darzustellenden Pfad angeben |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ein Array, das die Werte enthält, die die Typen der entsprechenden Punkte im **pts**-Array angeben |
| fillMode | [FillMode](../../fillmode/) | Gibt an, wie das Innere des vom zu erstellenden Objekt dargestellten geschlossenen Pfads gefüllt werden soll |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) Konstruktor

Konstruiert eine neue Instanz des [GraphicsPath](../) Objekts, das den angegebenen Pfad darstellt.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Ein Array, das die Punkte enthält, die den vom zu erstellenden Objekt darzustellenden Pfad angeben |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ein Array, das die Werte enthält, die die Typen der entsprechenden Punkte im **pts**-Array angeben |
| fillMode | [FillMode](../../fillmode/) | Gibt an, wie das Innere des vom zu erstellenden Objekt dargestellten geschlossenen Pfads gefüllt werden soll |

## GraphicsPath::GraphicsPath(const SkPath\&) Konstruktor

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## Siehe auch

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [GraphicsPath](../)
* Klasse [Point](../../../system.drawing/point/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)