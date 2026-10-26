---
title: SetClip()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece la región de recorte de la superficie de dibujo representada por el objeto Graphics actual al resultado de la operación especificada que combina la región de recorte actual y la región especificada.
type: docs
weight: 690
url: /es/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) método

Establece la región de recorte de la superficie de dibujo representada por el objeto [Graphics](../) actual al resultado de la operación especificada que combina la región de recorte actual y la región especificada.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | Especifica una región para combinar |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Especifica la operación de combinación |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) método

Establece la región de recorte de la superficie de dibujo representada por el objeto [Graphics](../) actual al resultado de la operación especificada que combina la región de recorte actual y la región especificada.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Especifica una región para combinar |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Especifica la operación de combinación |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) método

Establece la región de recorte de la superficie de dibujo representada por el objeto [Graphics](../) actual al resultado de la operación especificada que combina la región de recorte actual y la región especificada.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Especifica una región para combinar |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Especifica la operación de combinación |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) método

NO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) método

Establece la región de recorte de la superficie de dibujo representada por el objeto [Graphics](../) actual al resultado de la operación especificada que combina la región de recorte actual y la región especificada por una ruta gráfica.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Especifica una región para combinar |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Especifica la operación de combinación |

## Ver también

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)