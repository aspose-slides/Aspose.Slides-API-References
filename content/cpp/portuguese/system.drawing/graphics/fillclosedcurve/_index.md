---
title: FillClosedCurve()
second_title: Referência da API Aspose.Slides para C++
description: Desenha uma spline fechada usando o pincel especificado.
type: docs
weight: 807
url: /pt/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) método


Desenha uma spline fechada usando o pincel especificado.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Um pincel a ser usado ao desenhar a spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) de pontos que determina a spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |
| tension | **float** | Valor que especifica a tensão da spline |

## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) método


Desenha uma spline fechada usando o pincel especificado.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Um pincel a ser usado ao desenhar a spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) de pontos que determina a spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |
| tension | **float** | Valor que especifica a tensão da spline |

## Veja Também

* Enumeração [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Definição de tipo [SharedPtr](../../../system/sharedptr/)
* Definição de tipo [ArrayPtr](../../../system/arrayptr/)
* Classe [Brush](../../brush/)
* Classe [PointF](../../pointf/)
* Classe [Graphics](../)
* Classe [Point](../../point/)
* Espaço de nomes [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)