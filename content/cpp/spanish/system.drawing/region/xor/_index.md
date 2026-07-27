---
title: Xor()
second_title: Referencia de API de Aspose.Slides para C++
description: Reemplaza la región representada por el objeto actual con las porciones de esta región y la región definida por el rectángulo especificado que no se intersectan.
type: docs
weight: 144
url: /es/system.drawing/region/xor/
---
## Region::Xor(const RectangleF\&) método

Reemplaza la región representada por el objeto actual con las porciones de esta región y la región definida por el rectángulo especificado que no se intersectan.

```cpp
void System::Drawing::Region::Xor(const RectangleF &rect)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Un rectángulo que define una región para aplicar XOR con la región representada por el objeto actual |

## Region::Xor(const Rectangle\&) método

Reemplaza la región representada por el objeto actual con las porciones de esta región y la región definida por el rectángulo especificado que no se intersectan.

```cpp
void System::Drawing::Region::Xor(const Rectangle &rect)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rectángulo que define una región para aplicar XOR con la región representada por el objeto actual |

## Region::Xor(const SharedPtr\<Drawing2D::GraphicsPath\>\&) método

Reemplaza la región representada por el objeto actual con las porciones de esta región y la ruta definida por el camino especificado que no se intersectan.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Un camino que define una región para aplicar XOR con la región representada por el objeto actual |

## Region::Xor(const SharedPtr\<Region\>\&) método

Reemplaza la región representada por el objeto actual con las porciones de esta región y la región especificada que no se intersectan.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Region> &region)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Una región para aplicar XOR con la región representada por el objeto actual |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [RectangleF](../../rectanglef/)
* Clase [Region](../)
* Clase [Rectangle](../../rectangle/)
* Clase [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)