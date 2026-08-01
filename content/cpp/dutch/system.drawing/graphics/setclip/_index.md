---
title: SetClip()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt het knipgebied van het tekenoppervlak dat wordt vertegenwoordigd door het huidige Graphics object in op het resultaat van de opgegeven bewerking die het huidige knipgebied en de opgegeven regio combineert.
type: docs
weight: 690
url: /nl/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) methode


Stelt het knipgebied van het tekenoppervlak dat wordt vertegenwoordigd door het huidige [Graphics](../) object in op het resultaat van de opgegeven bewerking die het huidige knipgebied en de opgegeven regio combineert.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | Specificeert een regio om te combineren |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specificeert de combineeroperatie |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) methode


Stelt het knipgebied van het tekenoppervlak dat wordt vertegenwoordigd door het huidige [Graphics](../) object in op het resultaat van de opgegeven bewerking die het huidige knipgebied en de opgegeven regio combineert.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Specificeert een regio om te combineren |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specificeert de combineeroperatie |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) methode


Stelt het knipgebied van het tekenoppervlak dat wordt vertegenwoordigd door het huidige [Graphics](../) object in op het resultaat van de opgegeven bewerking die het huidige knipgebied en de opgegeven regio combineert.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Specificeert een regio om te combineren |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specificeert de combineeroperatie |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) methode


NIET GEREALISEERD.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) methode


Stelt het knipgebied van het tekenoppervlak dat wordt vertegenwoordigd door het huidige [Graphics](../) object in op het resultaat van de opgegeven bewerking die het huidige knipgebied en de regio die is opgegeven door een graphics-pad combineert.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Specificeert een regio om te combineren |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specificeert de combineeroperatie |

## Zie ook

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Region](../../region/)
* Klasse [Graphics](../)
* Klasse [Rectangle](../../rectangle/)
* Klasse [RectangleF](../../rectanglef/)
* Klasse [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Naamruimte [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)