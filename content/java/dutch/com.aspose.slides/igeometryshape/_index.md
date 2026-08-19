---
title: IGeometryShape
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de bovenliggende klasse voor alle geometrische vormen voor.
type: docs
url: /nl/com.aspose.slides/igeometryshape/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

Stelt de bovenliggende klasse voor alle geometrische vormen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Retourneert een kopie van het pad van de geometrische vorm. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Werkt de geometrie van de vorm bij vanuit een [IGeometryPath](../../com.aspose.slides/igeometrypath) object. |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Werkt de geometrie van de vorm bij vanuit een array van [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Retourneert het stijlobject van de vorm. |
| [getShapeType()](#getShapeType--) | Retourneert of stelt het vooraf ingestelde geometrietype in. |
| [setShapeType(int value)](#setShapeType-int-) | Retourneert of stelt het vooraf ingestelde geometrietype in. |
| [getAdjustments()](#getAdjustments--) | Retourneert een verzameling van de aanpassingswaarden van de vorm. |
| [createShapeElements()](#createShapeElements--) | Maakt en retourneert een array van de elementen van de vorm. |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```

Retourneert een kopie van het pad van de geometrische vorm. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm.

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

**Retourneert:**
com.aspose.slides.IGeometryPath[] - Array van [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```

Werkt de geometrie van de vorm bij vanuit een [IGeometryPath](../../com.aspose.slides/igeometrypath) object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm. Wijzigt het type van de vorm (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) naar [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Geometriepad |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```

Werkt de geometrie van de vorm bij vanuit een array van [IGeometryPath](../../com.aspose.slides/igeometrypath). Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm. Wijzigt het type van de vorm (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) naar [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Array van geometriepaden |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```

Retourneert het stijlobject van de vorm. Alleen-lezen [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Retourneert:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```

Retourneert of stelt het vooraf ingestelde geometrietype in. Opmerking: bij het wijzigen van de waarde worden alle aanpassingswaarden teruggezet naar hun standaardwaarden. Lezen/Schrijven [ShapeType](../../com.aspose.slides/shapetype).

**Retourneert:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```

Retourneert of stelt het vooraf ingestelde geometrietype in. Opmerking: bij het wijzigen van de waarde worden alle aanpassingswaarden teruggezet naar hun standaardwaarden. Lezen/Schrijven [ShapeType](../../com.aspose.slides/shapetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```

Retourneert een verzameling van de aanpassingswaarden van de vorm. Alleen-lezen [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Retourneert:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```

Maakt en retourneert een array van de elementen van de vorm.

**Retourneert:**
com.aspose.slides.IShapeElement[] - Array van [IShapeElement](../../com.aspose.slides/ishapeelement)