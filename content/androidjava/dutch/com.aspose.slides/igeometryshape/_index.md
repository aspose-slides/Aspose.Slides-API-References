---
title: IGeometryShape
second_title: Aspose.Slides voor Android via Java API-referentie
description: Representeert de bovenliggende klasse voor alle geometrische vormen.
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
| [getGeometryPaths()](#getGeometryPaths--) | Geeft een kopie van het pad van de geometrische vorm terug. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Werk de vormgeometrie bij vanuit [IGeometryPath](../../com.aspose.slides/igeometrypath) object. |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Werk de vormgeometrie bij vanaf een array van [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Geeft het stijlobject van de vorm terug. |
| [getShapeType()](#getShapeType--) | Geeft het vooraf ingestelde type van de geometrie terug of stelt het in. |
| [setShapeType(int value)](#setShapeType-int-) | Geeft het vooraf ingestelde type van de geometrie terug of stelt het in. |
| [getAdjustments()](#getAdjustments--) | Geeft een verzameling van de aanpassingswaarden van de vorm terug. |
| [createShapeElements()](#createShapeElements--) | Maakt en geeft een array van de elementen van de vorm terug. |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```


Geeft een kopie van het pad van de geometrische vorm terug. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm.

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

**Retour:**  
com.aspose.slides.IGeometryPath[] - Array of [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```


Werk de vormgeometrie bij vanuit [IGeometryPath](../../com.aspose.slides/igeometrypath) object. Coördinaten moeten relatief ten opzichte van de linkerbovenhoek van de vorm zijn. Verandert het type van de vorm (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) naar [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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


Werk de vormgeometrie bij vanaf een array van [IGeometryPath](../../com.aspose.slides/igeometrypath). Coördinaten moeten relatief ten opzichte van de linkerbovenhoek van de vorm zijn. Verandert het type van de vorm (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) naar [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Array geometry paths |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```


Geeft het stijlobject van de vorm terug. Alleen-lezen [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Retour:**  
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```


Geeft het vooraf ingestelde type van de geometrie terug of stelt het in. Opmerking: bij het wijzigen van de waarde worden alle aanpassingswaarden teruggezet naar hun standaardwaarden. Lezen/schrijven [ShapeType](../../com.aspose.slides/shapetype).

**Retour:**  
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```


Geeft het vooraf ingestelde type van de geometrie terug of stelt het in. Opmerking: bij het wijzigen van de waarde worden alle aanpassingswaarden teruggezet naar hun standaardwaarden. Lezen/schrijven [ShapeType](../../com.aspose.slides/shapetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```


Geeft een verzameling van de aanpassingswaarden van de vorm terug. Alleen-lezen [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Retour:**  
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```


Maakt een array van de elementen van de vorm en geeft deze terug.

**Retour:**  
com.aspose.slides.IShapeElement[] - Array of [IShapeElement](../../com.aspose.slides/ishapeelement)