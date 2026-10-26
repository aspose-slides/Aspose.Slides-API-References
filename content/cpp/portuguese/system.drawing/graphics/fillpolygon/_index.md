---
title: FillPolygon()
second_title: Referência da API Aspose.Slides para C++
description: Preenche o interior do polígono especificado usando o pincel especificado.
type: docs
weight: 417
url: /pt/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) método

Preenche o interior do polígono especificado usando o pincel especificado.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) objeto que especifica os parâmetros do preenchimento |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Um array contendo os pontos que definem o polígono |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | O modo de preenchimento |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) método

Preenche o interior do polígono especificado usando o pincel especificado.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) objeto que especifica os parâmetros do preenchimento |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Um array contendo os pontos que definem o polígono |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | O modo de preenchimento |

## Veja também

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Brush](../../brush/)
* Classe [Point](../../point/)
* Classe [Graphics](../)
* Classe [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)