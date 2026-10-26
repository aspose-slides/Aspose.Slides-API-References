---
title: ShapeElement
second_title: Aspose.Slides для Android через справочник API Java
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
| [getPathPoints()](#getPathPoints--) | Возвращает массив точек, определяющих геометрию пути элемента. |
| [getPathTypes()](#getPathTypes--) | Возвращает массив байтов, указывающих тип каждой точки в пути элемента. |
| [getFillSource()](#getFillSource--) | Возвращает информацию о том, как заполнить элемент. |
| [getStrokeSource()](#getStrokeSource--) | Возвращает информацию о том, как обрисовать элемент. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Возвращает Shape_PPT, для которого был создан элемент. Только для чтения [Shape](../../com.aspose.slides/shape).

**Возвращаемое значение:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```

Возвращает массив точек, определяющих геометрию пути элемента.

**Возвращаемое значение:**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Возвращает массив байтов, указывающих тип каждой точки в пути элемента.

**0** Указывает, что точка является началом фигуры.

**1** Указывает, что точка является одной из двух конечных точек линии.

**3** Указывает, что точка является конечной или контрольной точкой кубического сплайна Безье.

**7** Маскирует все биты, кроме трех младших, которые указывают тип точки.

**16** Указывает, что соответствующий сегмент состоит из пунктирных линий.

**32** Указывает, что точка является маркером.

**128** Указывает, что точка является последней точкой в замкнутом подпути (фигуре).

**129** Указывает, что точка данных одновременно является конечной точкой отрезка линии и последней точкой замкнутого подпутя.

**Возвращаемое значение:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Возвращает информацию о том, как заполнить элемент. Только для чтения [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Возвращаемое значение:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Возвращает информацию о том, как обрисовать элемент. Только для чтения [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Возвращаемое значение:**
byte