---
title: IGeometryShape
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje klasę bazową dla wszystkich kształtów geometrycznych.
type: docs
url: /pl/com.aspose.slides/igeometryshape/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

Reprezentuje klasę bazową dla wszystkich geometrycznych kształtów.
## Metody

| Metoda | Opis |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Zwraca kopię ścieżki geometrycznego kształtu. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Aktualizuje geometrię kształtu z obiektu [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Aktualizuje geometrię kształtu z tablicy [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Zwraca obiekt stylu kształtu. |
| [getShapeType()](#getShapeType--) | Zwraca lub ustawia typ predefiniowanej geometrii. |
| [setShapeType(int value)](#setShapeType-int-) | Zwraca lub ustawia typ predefiniowanej geometrii. |
| [getAdjustments()](#getAdjustments--) | Zwraca kolekcję wartości dopasowań kształtu. |
| [createShapeElements()](#createShapeElements--) | Tworzy i zwraca tablicę elementów kształtu. |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```


Zwraca kopię ścieżki geometrycznego kształtu. Współrzędne są względem lewego górnego rogu kształtu.

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

**Zwraca:**
com.aspose.slides.IGeometryPath[] - Tablica [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```


Aktualizuje geometrię kształtu z obiektu [IGeometryPath](../../com.aspose.slides/igeometrypath). Współrzędne muszą być względem lewego górnego rogu kształtu. Zmienia typ kształtu (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) na [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Ścieżka geometryczna |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```


Aktualizuje geometrię kształtu z tablicy [IGeometryPath](../../com.aspose.slides/igeometrypath). Współrzędne muszą być względem lewego górnego rogu kształtu. Zmienia typ kształtu (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) na [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Tablica ścieżek geometrycznych |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```


Zwraca obiekt stylu kształtu. Tylko do odczytu [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Zwraca:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```


Zwraca lub ustawia typ predefiniowanej geometrii. Uwaga: przy zmianie wartości wszystkie wartości dopasowań zostaną przywrócone do ich domyślnych. Odczyt/zapis [ShapeType](../../com.aspose.slides/shapetype).

**Zwraca:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```


Zwraca lub ustawia typ predefiniowanej geometrii. Uwaga: przy zmianie wartości wszystkie wartości dopasowań zostaną przywrócone do ich domyślnych. Odczyt/zapis [ShapeType](../../com.aspose.slides/shapetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```


Zwraca kolekcję wartości dopasowań kształtu. Tylko do odczytu [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Zwraca:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```


Tworzy i zwraca tablicę elementów kształtu.

**Zwraca:**
com.aspose.slides.IShapeElement[] - Tablica [IShapeElement](../../com.aspose.slides/ishapeelement)