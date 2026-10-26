---
title: SetClip()
second_title: Referência da API Aspose.Slides para C++
description: Define a região de recorte da superfície de desenho representada pelo objeto Graphics atual para o resultado da operação especificada que combina a região de recorte atual e a região especificada.
type: docs
weight: 690
url: /pt/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) método

Define a região de recorte da superfície de desenho representada pelo objeto [Graphics](../) atual para o resultado da operação especificada que combina a região de recorte atual e a região especificada.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | Especifica uma região a ser combinada |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Especifica a operação de combinação |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) método

Define a região de recorte da superfície de desenho representada pelo objeto [Graphics](../) atual para o resultado da operação especificada que combina a região de recorte atual e a região especificada.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Especifica uma região a ser combinada |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Especifica a operação de combinação |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) método

Define a região de recorte da superfície de desenho representada pelo objeto [Graphics](../) atual para o resultado da operação especificada que combina a região de recorte atual e a região especificada.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Especifica uma região a ser combinada |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Especifica a operação de combinação |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) método

NÃO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) método

Define a região de recorte da superfície de desenho representada pelo objeto [Graphics](../) atual para o resultado da operação especificada que combina a região de recorte atual e a região especificada por um caminho gráfico.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Especifica uma região a ser combinada |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Especifica a operação de combinação |

## Veja Também

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)