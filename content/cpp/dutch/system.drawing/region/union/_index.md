---
title: Union()
second_title: Aspose.Slides voor C++ API-referentie
description: Vervangt de regio die door het huidige object wordt weergegeven door het resultaat van de union-operatie van deze regio en een regio die wordt gedefinieerd door de opgegeven rechthoek.
type: docs
weight: 53
url: /nl/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) methode


Vervangt de regio die door het huidige object wordt vertegenwoordigd door het resultaat van de union-operatie van deze regio en een regio die wordt gedefinieerd door de opgegeven rechthoek.

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Een rechthoek die een regio definieert om deze regio mee te uniten |

## Region::Union(const Rectangle\&) methode


Vervangt de regio die door het huidige object wordt vertegenwoordigd door het resultaat van de union van deze regio en een regio die wordt gedefinieerd door de opgegeven rechthoek.

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Een rechthoek die een regio definieert om deze regio mee te uniten |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) methode


Vervangt de regio die door het huidige object wordt vertegenwoordigd door het resultaat van de union van deze regio en een regio die wordt gedefinieerd door het opgegeven pad.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Een pad dat een regio definieert om deze regio mee te uniten |

## Region::Union(const SharedPtr\<Region\>\&) methode


Vervangt de regio die door het huidige object wordt vertegenwoordigd door het resultaat van de union van deze regio en de opgegeven regio.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Een regio om deze regio mee te uniten |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RectangleF](../../rectanglef/)
* Klasse [Region](../)
* Klasse [Rectangle](../../rectangle/)
* Klasse [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Naamruimte [System::Drawing](../../)
* Library [Aspose.Slides](../../../)