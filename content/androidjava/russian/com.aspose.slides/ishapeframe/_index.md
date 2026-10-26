---
title: IShapeFrame
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет свойства рамок фигур.
type: docs
url: /ru/com.aspose.slides/ishapeframe/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

Представляет свойства рамки фигуры.
## Методы

| Метод | Описание |
| --- | --- |
| [getX()](#getX--) | Возвращает координату X левого верхнего угла рамки. |
| [getY()](#getY--) | Возвращает координату Y левого верхнего угла рамки. |
| [getWidth()](#getWidth--) | Возвращает ширину рамки. |
| [getHeight()](#getHeight--) | Возвращает высоту рамки. |
| [getRotation()](#getRotation--) | Возвращает количество градусов, на которое рамка вращена вокруг оси Z. |
| [getCenterX()](#getCenterX--) | Возвращает координату X центра рамки. |
| [getCenterY()](#getCenterY--) | Возвращает координату Y центра рамки. |
| [getFlipH()](#getFlipH--) | Определяет, перевернута ли рамка по горизонтали. |
| [getFlipV()](#getFlipV--) | Определяет, перевернута ли рамка по вертикали. |
| [getRectangle()](#getRectangle--) | Возвращает координаты рамки. |
### getX() {#getX--}
```
public abstract float getX()
```


Возвращает координату X левого верхнего угла рамки. Только для чтения float.

**Возвращаемое значение:**
float
### getY() {#getY--}
```
public abstract float getY()
```


Возвращает координату Y левого верхнего угла рамки. Только для чтения float.

**Возвращаемое значение:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```


Возвращает ширину рамки. Только для чтения float.

**Возвращаемое значение:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Возвращает высоту рамки. Только для чтения float.

**Возвращаемое значение:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```


Возвращает количество градусов, на которое рамка вращена вокруг оси Z. Положительное значение указывает на вращение по часовой стрелке; отрицательное — против часовой стрелки. Только для чтения float.

**Возвращаемое значение:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```


Возвращает координату X центра рамки. Только для чтения float.

**Возвращаемое значение:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```


Возвращает координату Y центра рамки. Только для чтения float.

**Возвращаемое значение:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```


Определяет, перевернута ли рамка по горизонтали. Только для чтения [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```


Определяет, перевернута ли рамка по вертикали. Только для чтения [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte
### getRectangle() {#getRectangle--}
```
public abstract RectF getRectangle()
```


Возвращает координаты рамки. Только для чтения android.graphics.RectF.

**Возвращаемое значение:**
android.graphics.RectF