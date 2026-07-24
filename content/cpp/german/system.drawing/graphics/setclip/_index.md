---
title: SetClip()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt die Clipping-Region der Zeichenfläche, die durch das aktuelle Graphics-Objekt dargestellt wird, auf das Ergebnis der angegebenen Operation fest, die die aktuelle Clip-Region und die angegebene Region kombiniert.
type: docs
weight: 690
url: /de/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) Methode

Legt die Clipping-Region der Zeichenfläche, die durch das aktuelle [Graphics](../)-Objekt repräsentiert wird, auf das Ergebnis der angegebenen Operation fest, die die aktuelle Clip-Region und die angegebene Region kombiniert.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) Methode

Legt die Clipping-Region der Zeichenfläche, die durch das aktuelle [Graphics](../)-Objekt repräsentiert wird, auf das Ergebnis der angegebenen Operation fest, die die aktuelle Clip-Region und die angegebene Region kombiniert.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) Methode

Legt die Clipping-Region der Zeichenfläche, die durch das aktuelle [Graphics](../)-Objekt repräsentiert wird, auf das Ergebnis der angegebenen Operation fest, die die aktuelle Clip-Region und die angegebene Region kombiniert.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) Methode

NICHT IMPLEMENTIERT.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) Methode

Legt die Clipping-Region der Zeichenfläche, die durch das aktuelle [Graphics](../)-Objekt repräsentiert wird, auf das Ergebnis der angegebenen Operation fest, die die aktuelle Clip-Region und die durch einen Grafikpfad angegebene Region kombiniert.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Siehe auch

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Region](../../region/)
* Klasse [Graphics](../)
* Klasse [Rectangle](../../rectangle/)
* Klasse [RectangleF](../../rectanglef/)
* Klasse [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namensraum [System::Drawing](../../)
* Library [Aspose.Slides](../../../)