---
title: SetClip()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastaví ořezovou oblast kreslící plochy reprezentované aktuálním objektem Graphics na výsledek specifikované operace, která kombinuje aktuální ořezovou oblast a zadanou oblast.
type: docs
weight: 690
url: /cs/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) method


Nastaví ořezovou oblast kreslící plochy reprezentované aktuálním objektem [Graphics](../) na výsledek specifikované operace, která spojuje aktuální ořezovou oblast a zadanou oblast.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) method


Nastaví ořezovou oblast kreslící plochy reprezentované aktuálním objektem [Graphics](../) na výsledek specifikované operace, která spojuje aktuální ořezovou oblast a zadanou oblast.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) method


Nastaví ořezovou oblast kreslící plochy reprezentované aktuálním objektem [Graphics](../) na výsledek specifikované operace, která spojuje aktuální ořezovou oblast a zadanou oblast.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) method


NEIMPLEMENTOVÁNO.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) method


Nastaví ořezovou oblast kreslící plochy reprezentované aktuálním objektem [Graphics](../) na výsledek specifikované operace, která spojuje aktuální ořezovou oblast a oblast specifikovanou grafickou cestou.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Viz také

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)