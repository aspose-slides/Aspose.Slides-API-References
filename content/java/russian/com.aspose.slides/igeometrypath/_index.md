---
title: IGeometryPath
second_title: Aspose.Slides for Java API Reference
description: Представляет геометрический путь GeometryShape
type: docs
url: /ru/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

Представляет геометрический путь GeometryShape
## Методы

| Метод | Описание |
| --- | --- |
| [getPathData()](#getPathData--) | Возвращает геометрический путь GeometryShape в виде массива сегментов пути. |
| [removeAt(int index)](#removeAt-int-) | Удаляет сегмент в указанном индексе геометрического пути. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Добавляет линию в конец пути |
| [lineTo(float x, float y)](#lineTo-float-float-) | Добавляет линию в конец пути |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Добавляет линию в указанное место пути |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Добавляет линию в указанное место пути |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Добавляет кубическую кривую Безье в конец пути |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Добавляет кубическую кривую Безье в конец пути |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Добавляет кубическую кривую Безье в указанное место пути |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Добавляет кубическую кривую Безье в указанное место пути |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Добавляет квадратичную кривую Безье в конец пути |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Добавляет квадратичную кривую Безье в конец пути |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Добавляет квадратичную кривую Безье в указанное место пути |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Добавляет квадратичную кривую Безье в указанное место пути |
| [closeFigure()](#closeFigure--) | Закрывает текущую фигуру этого пути |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Устанавливает позицию следующей точки. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Устанавливает позицию следующей точки. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Добавляет указанную дугу к пути. |
| [getFillMode()](#getFillMode--) | Устанавливает режим заливки |
| [setFillMode(byte value)](#setFillMode-byte-) | Устанавливает режим заливки |
| [getStroke()](#getStroke--) | Устанавливает свойства обводки |
| [setStroke(boolean value)](#setStroke-boolean-) | Устанавливает свойства обводки |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```


Возвращает геометрический путь GeometryShape в виде массива сегментов пути.

**Возвращаемое значение:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Удаляет сегмент в указанном индексе геометрического пути.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс сегмента геометрического пути, который должен быть удалён. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```


Добавляет линию в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Конечная точка линии |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```


Добавляет линию в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X конечной точки линии |
| y | float | Координата Y конечной точки линии |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```


Добавляет линию в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Конечная точка |
| index | long | Индекс сегмента в PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```


Добавляет линию в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X точки |
| y | float | Координата Y точки |
| index | long | Индекс сегмента в PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```


Добавляет кубическую кривую Безье в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Первая контрольная точка |
| point2 | java.awt.geom.Point2D.Float | Вторая контрольная точка |
| point3 | java.awt.geom.Point2D.Float | Конечная точка |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Добавляет кубическую кривую Безье в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x1 | float | Координата X первой контрольной точки |
| y1 | float | Координата Y первой контрольной точки |
| x2 | float | Координата X второй контрольной точки |
| y2 | float | Координата Y второй контрольной точки |
| x3 | float | Координата X конечной точки |
| y3 | float | Координата Y конечной точки |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```


Добавляет кубическую кривую Безье в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Первая контрольная точка |
| point2 | java.awt.geom.Point2D.Float | Вторая контрольная точка |
| point3 | java.awt.geom.Point2D.Float | Конечная точка |
| index | long | Индекс сегмента в PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Добавляет кубическую кривую Безье в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x1 | float | Координата X первой контрольной точки |
| y1 | float | Координата Y первой контрольной точки |
| x2 | float | Координата X второй контрольной точки |
| y2 | float | Координата Y второй контрольной точки |
| x3 | float | Координата X конечной точки |
| y3 | float | Координата Y конечной точки |
| index | long | Индекс сегмента в PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```


Добавляет квадратичную кривую Безье в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Контрольная точка |
| point2 | java.awt.geom.Point2D.Float | Конечная точка |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Добавляет квадратичную кривую Безье в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x1 | float | Координата X контрольной точки |
| y1 | float | Координата Y контрольной точки |
| x2 | float | Координата X конечной точки |
| y2 | float | Координата Y конечной точки |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```


Добавляет квадратичную кривую Безье в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Контрольная точка |
| point2 | java.awt.geom.Point2D.Float | Конечная точка |
| index | long | Индекс сегмента в PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Добавляет квадратичную кривую Безье в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x1 | float | Координата X контрольной точки |
| y1 | float | Координата Y контрольной точки |
| x2 | float | Координата X конечной точки |
| y2 | float | Координата Y конечной точки |
| index | long | Индекс сегмента в PathData |

### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```


Закрывает текущую фигуру этого пути

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```


Устанавливает позицию следующей точки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Позиция точки |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```


Устанавливает позицию следующей точки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X точки |
| y | float | Координата Y точки |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


Добавляет указанную дугу к пути.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | float | Ширина прямоугольника |
| heigth | float | Высота прямоугольника |
| startAngle | float | Начальный угол. |
| sweepAngle | float | Угол охвата. |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```


Устанавливает режим заливки

**Возвращаемое значение:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```


Устанавливает режим заливки

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```


Устанавливает свойства обводки

**Возвращаемое значение:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```


Устанавливает свойства обводки

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |   |