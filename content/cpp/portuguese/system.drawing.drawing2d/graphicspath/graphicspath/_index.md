---
title: GraphicsPath()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância da classe GraphicsPath com o modo de preenchimento especificado.
type: docs
weight: 1
url: /pt/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) construtor


Constrói uma nova instância da classe [GraphicsPath](../) com o modo de preenchimento especificado.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | Especifica como o interior do caminho fechado representado pelo objeto que está sendo criado deve ser preenchido |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) construtor


Constrói uma nova instância do objeto [GraphicsPath](../) que representa o caminho especificado.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Um array contendo os pontos que especificam o caminho a ser representado pelo objeto que está sendo criado |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Um array contendo os valores que especificam os tipos dos pontos correspondentes no array **pts** |
| fillMode | [FillMode](../../fillmode/) | Especifica como o interior do caminho fechado representado pelo objeto que está sendo criado deve ser preenchido |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) construtor


Constrói uma nova instância do objeto [GraphicsPath](../) que representa o caminho especificado.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Um array contendo os pontos que especificam o caminho a ser representado pelo objeto que está sendo criado |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Um array contendo os valores que especificam os tipos dos pontos correspondentes no array **pts** |
| fillMode | [FillMode](../../fillmode/) | Especifica como o interior do caminho fechado representado pelo objeto que está sendo criado deve ser preenchido |

## GraphicsPath::GraphicsPath(const SkPath\&) construtor




```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## Veja Também

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [GraphicsPath](../)
* Class [Point](../../../system.drawing/point/)
* Class [PointF](../../../system.drawing/pointf/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)