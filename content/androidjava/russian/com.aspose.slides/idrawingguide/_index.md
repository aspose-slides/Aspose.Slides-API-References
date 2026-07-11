---
title: IDrawingGuide
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an adjustable drawing guide.
type: docs
url: /ru/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Представляет регулируемую направляющую.
## Methods

| Method | Description |
| --- | --- |
| [getOrientation()](#getOrientation--) | Возвращает или задает ориентацию направляющей. |
| [setOrientation(byte value)](#setOrientation-byte-) | Возвращает или задает ориентацию направляющей. |
| [getPosition()](#getPosition--) | Возвращает или задает положение направляющей в пунктах от верхнего, левого угла слайда. |
| [setPosition(float value)](#setPosition-float-) | Возвращает или задает положение направляющей в пунктах от верхнего, левого угла слайда. |
| [getColor()](#getColor--) | Возвращает или задает цвет направляющей. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Возвращает или задает цвет направляющей. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```


Возвращает или задает ориентацию направляющей. Чтение/запись [Orientation](../../com.aspose.slides/orientation).

**Returns:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```


Возвращает или задает ориентацию направляющей. Чтение/запись [Orientation](../../com.aspose.slides/orientation).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


Возвращает или задает положение направляющей в пунктах от верхнего, левого угла слайда. Чтение/запись float.

--------------------

Типичное значение находится в диапазоне от нуля до высоты слайда для горизонтальной направляющей и от нуля до ширины слайда для вертикальной направляющей.

**Returns:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


Возвращает или задает положение направляющей в пунктах от верхнего, левого угла слайда. Чтение/запись float.

--------------------

Типичное значение находится в диапазоне от нуля до высоты слайда для горизонтальной направляющей и от нуля до ширины слайда для вертикальной направляющей.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```


Возвращает или задает цвет направляющей. Чтение/запись java.lang.Integer.

**Returns:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```


Возвращает или задает цвет направляющей. Чтение/запись java.lang.Integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |