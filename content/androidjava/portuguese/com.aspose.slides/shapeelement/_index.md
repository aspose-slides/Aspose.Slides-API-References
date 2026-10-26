---
title: ShapeElement
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma parte da forma com as mesmas propriedades de contorno e preenchimento.
type: docs
url: /pt/com.aspose.slides/shapeelement/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Representa uma parte da forma com as mesmas propriedades de contorno e preenchimento.
## Métodos

| Método | Descrição |
| --- | --- |
| [getParentShape()](#getParentShape--) | Retorna um Shape\_PPT para o qual o elemento foi criado. |
| [getPathPoints()](#getPathPoints--) | Obtém uma matriz de pontos que definem a geometria do caminho do elemento. |
| [getPathTypes()](#getPathTypes--) | Obtém uma matriz de valores byte que especificam o tipo de cada ponto no caminho do elemento. |
| [getFillSource()](#getFillSource--) | Retorna informações sobre como preencher um elemento. |
| [getStrokeSource()](#getStrokeSource--) | Retorna informações sobre como traçar um elemento. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Retorna um Shape\_PPT para o qual o elemento foi criado. Somente leitura [Shape](../../com.aspose.slides/shape).

**Retorna:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```

Obtém uma matriz de pontos que definem a geometria do caminho do elemento.

**Retorna:**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Obtém uma matriz de valores byte que especificam o tipo de cada ponto no caminho do elemento.

**0** Indica que o ponto é o início de uma figura.

**1** Indica que o ponto é um dos dois extremos de uma linha.

**3** Indica que o ponto é um ponto final ou de controle de uma spline cúbica de Bézier.

**7** Masca todos os bits, exceto os três bits de ordem inferior, que indicam o tipo do ponto.

**16** Especifica que o segmento correspondente é tracejado.

**32** Especifica que o ponto é um marcador.

**128** Especifica que o ponto é o último ponto em um subcaminho fechado (figura).

**129** Indica um ponto de dados que é tanto um extremo de segmento de linha quanto o último ponto de um subcaminho fechado.

**Retorna:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Retorna informações sobre como preencher um elemento. Somente leitura [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Retorna:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Retorna informações sobre como traçar um elemento. Somente leitura [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Retorna:**
byte