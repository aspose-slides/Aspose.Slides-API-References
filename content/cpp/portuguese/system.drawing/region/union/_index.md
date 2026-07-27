---
title: Union()
second_title: Referência da API Aspose.Slides para C++
description: Substitui a região representada pelo objeto atual pelo resultado da operação de união desta região com uma região definida pelo retângulo especificado.
type: docs
weight: 53
url: /pt/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) método

Substitui a região representada pelo objeto atual pelo resultado da operação de união desta região com uma região definida pelo retângulo especificado.

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Um retângulo que define uma região para unir esta região com |

## Region::Union(const Rectangle\&) método

Substitui a região representada pelo objeto atual pelo resultado da união desta região com uma região definida pelo retângulo especificado.

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Um retângulo que define uma região para unir esta região com |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) método

Substitui a região representada pelo objeto atual pelo resultado da união desta região com uma região definida pelo caminho especificado.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Um caminho que define uma região para unir esta região com |

## Region::Union(const SharedPtr\<Region\>\&) método

Substitui a região representada pelo objeto atual pelo resultado da união desta região com a região especificada.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Uma região para unir esta região com |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RectangleF](../../rectanglef/)
* Classe [Region](../)
* Classe [Rectangle](../../rectangle/)
* Classe [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Espaço de nomes [System::Drawing](../../)
* Library [Aspose.Slides](../../../)