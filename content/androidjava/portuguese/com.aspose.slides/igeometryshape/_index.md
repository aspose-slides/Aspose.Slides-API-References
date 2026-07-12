---
title: IGeometryShape
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa a classe base para todas as formas geométricas.
type: docs
url: /pt/com.aspose.slides/igeometryshape/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

Representa a classe base para todas as formas geométricas.
## Métodos

| Método | Descrição |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Retorna a cópia do caminho da forma geométrica. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Atualiza a geometria da forma a partir do objeto [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Atualiza a geometria da forma a partir de um array de [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Retorna o objeto de estilo da forma. |
| [getShapeType()](#getShapeType--) | Retorna ou define o tipo de preset de geometria. |
| [setShapeType(int value)](#setShapeType-int-) | Retorna ou define o tipo de preset de geometria. |
| [getAdjustments()](#getAdjustments--) | Retorna uma coleção dos valores de ajuste da forma. |
| [createShapeElements()](#createShapeElements--) | Cria e retorna um array dos elementos da forma. |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```

Retorna a cópia do caminho da forma geométrica. As coordenadas são relativas ao canto superior esquerdo da forma.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
com.aspose.slides.IGeometryPath[] - Array de [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```

Atualiza a geometria da forma a partir do objeto [IGeometryPath](../../com.aspose.slides/igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) para [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      GeometryPath geometryPath0 = new GeometryPath();
>      geometryPath0.moveTo(0, 0);
>      geometryPath0.lineTo(shape.getWidth(), 0);
>      geometryPath0.lineTo(shape.getWidth(), shape.getHeight()/3);
>      geometryPath0.lineTo(0, shape.getHeight() / 3);
>      geometryPath0.closeFigure();
>      GeometryPath geometryPath1 = new GeometryPath();
>      geometryPath1.moveTo(0, shape.getHeight()/3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight() / 3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight());
>      geometryPath1.lineTo(0, shape.getHeight());
>      geometryPath1.closeFigure();
>      shape.setGeometryPaths(new GeometryPath[] { geometryPath0, geometryPath1});
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Caminho de geometria |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```

Atualiza a geometria da forma a partir de um array de [IGeometryPath](../../com.aspose.slides/igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) para [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape)pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Array de caminhos de geometria |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```

Retorna o objeto de estilo da forma. Somente leitura [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Retorna:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```

Retorna ou define o tipo de preset de geometria. Observação: ao mudar o valor, todos os valores de ajuste serão redefinidos para seus valores padrão. Leitura/Gravação [ShapeType](../../com.aspose.slides/shapetype).

**Retorna:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```

Retorna ou define o tipo de preset de geometria. Observação: ao mudar o valor, todos os valores de ajuste serão redefinidos para seus valores padrão. Leitura/Gravação [ShapeType](../../com.aspose.slides/shapetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```

Retorna uma coleção dos valores de ajuste da forma. Somente leitura [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Retorna:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```

Cria e retorna um array dos elementos da forma.

**Retorna:**
com.aspose.slides.IShapeElement[] - Array de [IShapeElement](../../com.aspose.slides/ishapeelement)