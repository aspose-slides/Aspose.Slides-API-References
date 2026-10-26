---
title: CustomLineCap()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye una nueva instancia de la clase CustomLineCap que representa un extremo de línea definido por el usuario con las propiedades especificadas.
type: docs
weight: 1
url: /es/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) constructor

Construye una nueva instancia de la clase [CustomLineCap](../) que representa un extremo de línea definido por el usuario con las propiedades especificadas.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Especifica un relleno para el extremo personalizado |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Especifica un contorno del extremo personalizado |
| baseCap | [LineCap](../../linecap/) | El extremo de línea base a partir del cual se crea el extremo personalizado |
| baseInset | **float** | Especifica la distancia entre la línea y el extremo |

## Ver también

* Enum [LineCap](../../linecap/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../../graphicspath/)
* Class [CustomLineCap](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)