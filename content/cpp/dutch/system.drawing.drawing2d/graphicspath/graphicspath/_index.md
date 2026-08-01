---
title: GraphicsPath()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar van de GraphicsPath-klasse met de opgegeven vulmodus.
type: docs
weight: 1
url: /nl/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) constructor

Construeert een nieuw exemplaar van de [GraphicsPath](../)-klasse met de opgegeven vulmodus.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | Specificeert hoe het interieur van het gesloten pad dat door het te creëren object wordt weergegeven, moet worden gevuld |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructor

Construeert een nieuw exemplaar van het [GraphicsPath](../)-object dat het opgegeven pad vertegenwoordigt.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Een array die de punten bevat die het pad specificeren dat door het te creëren object wordt weergegeven |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Een array die de waarden bevat die de types van de overeenkomstige punten in de **pts**-array specificeren |
| fillMode | [FillMode](../../fillmode/) | Specificeert hoe het interieur van het gesloten pad dat door het te creëren object wordt weergegeven, moet worden gevuld |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructor

Construeert een nieuw exemplaar van het [GraphicsPath](../)-object dat het opgegeven pad vertegenwoordigt.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Een array die de punten bevat die het pad specificeren dat door het te creëren object wordt weergegeven |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Een array die de waarden bevat die de types van de overeenkomstige punten in de **pts**-array specificeren |
| fillMode | [FillMode](../../fillmode/) | Specificeert hoe het interieur van het gesloten pad dat door het te creëren object wordt weergegeven, moet worden gevuld |

## GraphicsPath::GraphicsPath(const SkPath\&) constructor

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## Zie ook

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [GraphicsPath](../)
* Class [Point](../../../system.drawing/point/)
* Class [PointF](../../../system.drawing/pointf/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)