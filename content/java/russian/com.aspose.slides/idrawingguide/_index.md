---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: Represents an adjustable drawing guide.
type: docs
url: /ru/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Представляет регулируемую направляющую для рисования.
## Методы

| Метод | Описание |
| --- | --- |
| [getOrientation()](#getOrientation--) | Получает или задаёт ориентацию направляющей для рисования. |
| [setOrientation(byte value)](#setOrientation-byte-) | Получает или задаёт ориентацию направляющей для рисования. |
| [getPosition()](#getPosition--) | Получает или задаёт позицию направляющей для рисования в пунктах от верхнего левого угла слайда. |
| [setPosition(float value)](#setPosition-float-) | Получает или задаёт позицию направляющей для рисования в пунктах от верхнего левого угла слайда. |
| [getColor()](#getColor--) | Получает или задаёт цвет направляющей для рисования. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Получает или задаёт цвет направляющей для рисования. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

Получает или задаёт ориентацию направляющей для рисования. Чтение/запись [Orientation](../../com.aspose.slides/orientation).

**Возвращаемое значение:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

Получает или задаёт ориентацию направляющей для рисования. Чтение/запись [Orientation](../../com.aspose.slides/orientation).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

Получает или задаёт позицию направляющей для рисования в пунктах от верхнего левого угла слайда. Чтение/запись float.

--------------------

Обычный диапазон значений — от нуля до высоты слайда для горизонтальной направляющей и от нуля до ширины слайда для вертикальной направляющей.

**Возвращаемое значение:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

Получает или задаёт позицию направляющей для рисования в пунктах от верхнего левого угла слайда. Чтение/запись float.

--------------------

Обычный диапазон значений — от нуля до высоты слайда для горизонтальной направляющей и от нуля до ширины слайда для вертикальной направляющей.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

Получает или задаёт цвет направляющей для рисования. Чтение/запись java.awt.Color.

**Возвращаемое значение:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Получает или задаёт цвет направляющей для рисования. Чтение/запись java.awt.Color.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.Color |  |