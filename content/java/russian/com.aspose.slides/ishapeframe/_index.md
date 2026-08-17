---
title: IShapeFrame
second_title: Aspose.Slides для Java справочник API
description: Представляет свойства рамок фигуры.
type: docs
url: /ru/com.aspose.slides/ishapeframe/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

Представляет свойства рамки фигуры.
## Методы

| Method | Description |
| --- | --- |
| [getX()](#getX--) | Возвращает координату X верхнего левого угла рамки. |
| [getY()](#getY--) | Возвращает координату Y верхнего левого угла рамки. |
| [getWidth()](#getWidth--) | Возвращает ширину рамки. |
| [getHeight()](#getHeight--) | Возвращает высоту рамки. |
| [getRotation()](#getRotation--) | Возвращает количество градусов, на которое рамка повернута вокруг оси z. |
| [getCenterX()](#getCenterX--) | Возвращает координату X центра рамки. |
| [getCenterY()](#getCenterY--) | Возвращает координату Y центра рамки. |
| [getFlipH()](#getFlipH--) | Определяет, перевёрнута ли рамка горизонтально. |
| [getFlipV()](#getFlipV--) | Определяет, перевёрнута ли рамка вертикально. |
| [getRectangle()](#getRectangle--) | Возвращает координаты рамки. |
### getX() {#getX--}
```
public abstract float getX()
```


Возвращает координату X верхнего левого угла рамки. Только для чтения float.

**Возвращает:**
float
### getY() {#getY--}
```
public abstract float getY()
```


Возвращает координату Y верхнего левого угла рамки. Только для чтения float.

**Возвращает:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```


Возвращает ширину рамки. Только для чтения float.

**Возвращает:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Возвращает высоту рамки. Только для чтения float.

**Возвращает:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```


Возвращает количество градусов, на которое рамка повернута вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное — против часовой стрелки. Только для чтения float.

**Возвращает:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```


Возвращает координату X центра рамки. Только для чтения float.

**Возвращает:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```


Возвращает координату Y центра рамки. Только для чтения float.

**Возвращает:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```


Определяет, перевёрнута ли рамка горизонтально. Только для чтения [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```


Определяет, перевёрнута ли рамка вертикально. Только для чтения [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### getRectangle() {#getRectangle--}
```
public abstract Rectangle2D.Float getRectangle()
```


Возвращает координаты рамки. Только для чтения java.awt.geom.Rectangle2D.Float.

**Возвращает:**
java.awt.geom.Rectangle2D.Float