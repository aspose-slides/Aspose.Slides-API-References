---
title: ShapeElement
second_title: Справочник API Aspose.Slides для Java
description: Представляет часть фигуры с одинаковыми свойствами контура и заливки.
type: docs
url: /ru/com.aspose.slides/shapeelement/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Представляет часть фигуры с одинаковыми свойствами контура и заливки.
## Методы

| Метод | Описание |
| --- | --- |
| [getParentShape()](#getParentShape--) | Возвращает Shape_PPT, для которого был создан элемент. |
| [getPathPoints()](#getPathPoints--) | Получает массив точек, определяющих геометрию пути элемента. |
| [getPathTypes()](#getPathTypes--) | Получает массив байтовых значений, указывающих тип каждой точки в пути элемента. |
| [getFillSource()](#getFillSource--) | Возвращает информацию о том, как заполнять элемент. |
| [getStrokeSource()](#getStrokeSource--) | Возвращает информацию о том, как обводить элемент. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Возвращает Shape_PPT, для которого был создан элемент. Только для чтения [Shape](../../com.aspose.slides/shape).

**Возвращает:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```

Получает массив точек, определяющих геометрию пути элемента.

**Возвращает:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Получает массив байтовых значений, указывающих тип каждой точки в пути элемента.

**0** Указывает, что точка является началом фигуры.

**1** Указывает, что точка является одной из двух конечных точек линии.

**3** Указывает, что точка является конечной или контрольной точкой кубической сплайновой кривой Безье.

**7** Маскирует все биты, кроме трех младших, которые указывают тип точки.

**16** Указывает, что соответствующий сегмент пунктирный.

**32** Указывает, что точка является маркером.

**128** Указывает, что точка является последней в замкнутом подпути (фигура).

**129** Указывает, что точка данных является одновременно конечной точкой отрезка линии и последней точкой замкнутого подпути.

**Возвращает:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Возвращает информацию о том, как заполнять элемент. Только для чтения [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Возвращает:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Возвращает информацию о том, как обводить элемент. Только для чтения [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Возвращает:**
byte