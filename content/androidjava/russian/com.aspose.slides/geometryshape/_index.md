---
title: GeometryShape
second_title: Aspose.Slides для Android через справку API Java
description: Представляет базовый класс для всех геометрических фигур.
type: docs
url: /ru/com.aspose.slides/geometryshape/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Все реализованные интерфейсы:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

Представляет базовый класс для всех геометрических фигур.
## Методы

| Метод | Описание |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Возвращает копию пути геометрической фигуры. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Обновляет геометрию фигуры из объекта [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Обновляет геометрию фигуры из массива [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Возвращает объект стиля фигуры. |
| [getShapeType()](#getShapeType--) | Возвращает или задаёт тип предустановки геометрии. |
| [setShapeType(int value)](#setShapeType-int-) | Возвращает или задаёт тип предустановки геометрии. |
| [getAdjustments()](#getAdjustments--) | Возвращает коллекцию значений коррекции фигуры. |
| [createShapeElements()](#createShapeElements--) | Создаёт и возвращает массив элементов фигуры. |
### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```

Возвращает копию пути геометрической фигуры. Координаты относительно левого верхнего угла фигуры.

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


**Возвращаемое значение:**
com.aspose.slides.IGeometryPath[] - Массив [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```

Обновляет геометрию фигуры из объекта [IGeometryPath](../../com.aspose.slides/igeometrypath). Координаты должны быть относительно левого верхнего угла фигуры. Изменяет тип фигуры (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) на [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Путь геометрии |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```

Обновляет геометрию фигуры из массива [IGeometryPath](../../com.aspose.slides/igeometrypath). Координаты должны быть относительно левого верхнего угла фигуры. Изменяет тип фигуры (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) на [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Массив путей геометрии |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```

Возвращает объект стиля фигуры. Только для чтения [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Возвращаемое значение:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Возвращает или задаёт тип предустановки геометрии. Примечание: при изменении значения все значения коррекции будут сброшены к значениям по умолчанию. Чтение/запись [ShapeType](../../com.aspose.slides/shapetype).

**Возвращаемое значение:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Возвращает или задаёт тип предустановки геометрии. Примечание: при изменении значения все значения коррекции будут сброшены к значениям по умолчанию. Чтение/запись [ShapeType](../../com.aspose.slides/shapetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```

Возвращает коллекцию значений коррекции фигуры. Только для чтения [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Возвращаемое значение:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```

Создаёт и возвращает массив элементов фигуры.

**Возвращаемое значение:**
com.aspose.slides.IShapeElement[] - Массив [ShapeElement](../../com.aspose.slides/shapeelement)