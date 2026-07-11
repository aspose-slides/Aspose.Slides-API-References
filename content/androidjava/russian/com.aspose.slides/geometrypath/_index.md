---
title: GeometryPath
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет геометрический путь GeometryShape
type: docs
url: /ru/com.aspose.slides/geometrypath/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Представляет геометрический путь GeometryShape
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Создает экземпляр GeometryPath |
## Методы

| Метод | Описание |
| --- | --- |
| [getPathData()](#getPathData--) | Возвращает геометрический путь GeometryShape в виде массива сегментов пути. |
| [removeAt(int index)](#removeAt-int-) | Удаляет сегмент в указанном индексе геометрического пути. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Добавляет линию в конец пути |
| [lineTo(float x, float y)](#lineTo-float-float-) | Добавляет линию в конец пути |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Добавляет линию в указанное место пути |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Добавляет линию в указанное место пути |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Добавляет кубическую Безье-кривую в конец пути |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Добавляет кубическую Безье-кривую в конец пути |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Добавляет кубическую Безье-кривую в указанное место пути |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Добавляет кубическую Безье-кривую в указанное место пути |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Добавляет квадратичную Безье-кривую в конец пути |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Добавляет квадратичную Безье-кривую в конец пути |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Добавляет квадратичную Безье-кривую в указанное место пути |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Добавляет квадратичную Безье-кривую в указанное место пути |
| [closeFigure()](#closeFigure--) | Замыкает текущую фигуру этого пути |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Устанавливает позицию следующей точки. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Устанавливает позицию следующей точки. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Добавляет указанный дуговой сегмент к пути. |
| [getFillMode()](#getFillMode--) | Устанавливает режим заливки |
| [setFillMode(byte value)](#setFillMode-byte-) | Устанавливает режим заливки |
| [getStroke()](#getStroke--) | Устанавливает параметры обводки |
| [setStroke(boolean value)](#setStroke-boolean-) | Устанавливает параметры обводки |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

Создает экземпляр GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

Возвращает геометрический путь GeometryShape в виде массива сегментов пути.

**Возвращаемое значение:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет сегмент в указанном индексе геометрического пути.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс сегмента пути, который следует удалить. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```

Добавляет линию в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | android.graphics.PointF | Конечная точка линии |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

Добавляет линию в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X конечной точки линии |
| y | float | Координата Y конечной точки линии |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```

Добавляет линию в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | android.graphics.PointF | Конечная точка |
| index | long | Индекс сегмента в PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Добавляет линию в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X точки |
| y | float | Координата Y точки |
| index | long | Индекс сегмента в PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

Добавляет кубическую Безье-кривую в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | android.graphics.PointF | Первая управляющая точка |
| point2 | android.graphics.PointF | Вторая управляющая точка |
| point3 | android.graphics.PointF | Конечная точка |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Добавляет кубическую Безье-кривую в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x1 | float | Координата X первой управляющей точки |
| y1 | float | Координата Y первой управляющей точки |
| x2 | float | Координата X второй управляющей точки |
| y2 | float | Ко koordinата Y второй управляющей точки |
| x3 | float | Координата X конечной точки |
| y3 | float | Координата Y конечной точки |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Добавляет кубическую Безье-кривую в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | android.graphics.PointF | Первая управляющая точка |
| point2 | android.graphics.PointF | Вторая управляющая точка |
| point3 | android.graphics.PointF | Конечная точка |
| index | long | Индекс сегмента в PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Добавляет кубическую Безье-кривую в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x1 | float | Координата X первой управляющей точки |
| y1 | float | Координата Y первой управляющей точки |
| x2 | float | Координата X второй управляющей точки |
| y2 | float | Координата Y второй управляющей точки |
| x3 | float | Координата X конечной точки |
| y3 | float | Координата Y конечной точки |
| index | long | Индекс сегмента в PathData |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```

Добавляет квадратичную Безье-кривую в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | android.graphics.PointF | Управляющая точка |
| point2 | android.graphics.PointF | Конечная точка |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Добавляет квадратичную Безье-кривую в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x1 | float | Координата X управляющей точки |
| y1 | float | Координата Y управляющей точки |
| x2 | float | Координата X конечной точки |
| y2 | float | Координата Y конечной точки |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Добавляет квадратичную Безье-кривую в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | android.graphics.PointF | Управляющая точка |
| point2 | android.graphics.PointF | Конечная точка |
| index | long | Индекс сегмента в PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Добавляет квадратичную Безье-кривую в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x1 | float | Координата X управляющей точки |
| y1 | float | Координата Y управляющей точки |
| x2 | float | Координата X конечной точки |
| y2 | float | Координата Y конечной точки |
| index | long | Индекс сегмента в PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

Замыкает текущую фигуру этого пути

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```

Устанавливает позицию следующей точки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | android.graphics.PointF | Позиция точки |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

Устанавливает позицию следующей точки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X точки |
| y | float | Координата Y точки |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Добавляет указанный дуговой сегмент к пути.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | float | Ширина прямоугольника |
| heigth | float | Высота прямоугольника |
| startAngle | float | Начальный угол |
| sweepAngle | float | Угол sweep |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

Устанавливает режим заливки

**Возвращаемое значение:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

Устанавливает режим заливки

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

Устанавливает параметры обводки

**Возвращаемое значение:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

Устанавливает параметры обводки

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |