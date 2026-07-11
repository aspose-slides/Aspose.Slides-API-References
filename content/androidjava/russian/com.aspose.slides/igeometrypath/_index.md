---
title: IGeometryPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /ru/com.aspose.slides/igeometrypath/
---
```
public interface IGeometryPath
```

Представляет геометрический путь GeometryShape
## Методы

| Метод | Описание |
| --- | --- |
| [getPathData()](#getPathData--) | Возвращает геометрический путь GeometryShape в виде массива сегментов пути. |
| [removeAt(int index)](#removeAt-int-) | Удаляет сегмент в указанном индексе геометрического пути. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Добавляет линию в конец пути |
| [lineTo(float x, float y)](#lineTo-float-float-) | Добавляет линию в конец пути |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Добавляет линию в указанное место пути |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Добавляет линию в указанное место пути |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Добавляет кубическую кривую Безье в конец пути |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Добавляет кубическую кривую Безье в конец пути |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Добавляет кубическую кривую Безье в указанное место пути |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Добавляет кубическую кривую Безье в указанное место пути |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Добавляет квадратичную кривую Безье в конец пути |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Добавляет квадратичную кривую Безье в конец пути |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Добавляет квадратичную кривую Безье в указанное место пути |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Добавляет квадратичную кривую Безье в указанное место пути |
| [closeFigure()](#closeFigure--) | Закрывает текущую фигуру этого пути |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Устанавливает позицию следующей точки. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Устанавливает позицию следующей точки. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Добавляет указанную дугу к пути. |
| [getFillMode()](#getFillMode--) | Устанавливает режим заливки |
| [setFillMode(byte value)](#setFillMode-byte-) | Устанавливает режим заливки |
| [getStroke()](#getStroke--) | Устанавливает параметры обводки |
| [setStroke(boolean value)](#setStroke-boolean-) | Устанавливает параметры обводки |
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
| index | int | Индекс сегмента геометрического пути, который следует удалить. |
### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```

Добавляет линию в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | android.graphics.PointF | Конечная точка линии |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

Добавляет линию в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | X-координата конечной точки линии |
| y | float | Y-координата конечной точки линии |
### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```

Добавляет линию в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | android.graphics.PointF | Конечная точка |
| index | long | Индекс сегмента в PathData |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

Добавляет линию в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | X-координата точки |
| y | float | Y-координата точки |
| index | long | Индекс сегмента в PathData |
### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

Добавляет кубическую кривую Безье в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | android.graphics.PointF | Первая контрольная точка |
| point2 | android.graphics.PointF | Вторая контрольная точка |
| point3 | android.graphics.PointF | Конечная точка |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Добавляет кубическую кривую Безье в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x1 | float | X-координата первой контрольной точки |
| y1 | float | Y-координата первой контрольной точки |
| x2 | float | X-координата второй контрольной точки |
| y2 | float | Y-координата второй контрольной точки |
| x3 | float | X-координата конечной точки |
| y3 | float | Y-координата конечной точки |
### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Добавляет кубическую кривую Безье в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | android.graphics.PointF | Первая контрольная точка |
| point2 | android.graphics.PointF | Вторая контрольная точка |
| point3 | android.graphics.PointF | Конечная точка |
| index | long | Индекс сегмента в PathData |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Добавляет кубическую кривую Безье в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x1 | float | X-координата первой контрольной точки |
| y1 | float | Y-координата первой контрольной точки |
| x2 | float | X-координата второй контрольной точки |
| y2 | float | Y-координата второй контрольной точки |
| x3 | float | X-координата конечной точки |
| y3 | float | Y-координата конечной точки |
| index | long | Индекс сегмента в PathData |
### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```

Добавляет квадратичную кривую Безье в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | android.graphics.PointF | Контрольная точка |
| point2 | android.graphics.PointF | Конечная точка |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Добавляет квадратичную кривую Безье в конец пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x1 | float | X-координата контрольной точки |
| y1 | float | Y-координата контрольной точки |
| x2 | float | X-координата конечной точки |
| y2 | float | Y-координата конечной точки |
### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Добавляет квадратичную кривую Безье в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | android.graphics.PointF | Контрольная точка |
| point2 | android.graphics.PointF | Конечная точка |
| index | long | Индекс сегмента в PathData |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Добавляет квадратичную кривую Безье в указанное место пути

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x1 | float | X-координата контрольной точки |
| y1 | float | Y-координата контрольной точки |
| x2 | float | X-координата конечной точки |
| y2 | float | Y-координата конечной точки |
| index | long | Индекс сегмента в PathData |
### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

Закрывает текущую фигуру этого пути
### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```

Устанавливает позицию следующей точки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | android.graphics.PointF | Позиция точки |
### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

Устанавливает позицию следующей точки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | X-координата точки |
| y | float | Y Координата точки |
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
| sweepAngle | float | Угол охвата |
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

Устанавливает параметры обводки

**Возвращаемое значение:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

Устанавливает параметры обводки

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |