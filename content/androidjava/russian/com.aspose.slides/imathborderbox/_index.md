---
title: IMathBorderBox
second_title: Aspose.Slides для Android через справочник Java API
description: Рисует прямоугольную или другую границу вокруг IMathElement.
type: docs
url: /ru/com.aspose.slides/imathborderbox/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Отрисовывает прямоугольную или другую границу вокруг IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Базовый аргумент |
| [getHideTop()](#getHideTop--) | Скрыть верхний край (default is false) - указывает скрытое или отображаемое состояние верхнего края рамки. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Скрыть верхний край (default is false) - указывает скрытое или отображаемое состояние верхнего края рамки. |
| [getHideBottom()](#getHideBottom--) | Скрыть нижний край (default is false) - указывает скрытое или отображаемое состояние нижнего края рамки. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Скрыть нижний край (default is false) - указывает скрытое или отображаемое состояние нижнего края рамки. |
| [getHideLeft()](#getHideLeft--) | Скрыть левый край (default is false) - указывает скрытое или отображаемое состояние левого края рамки. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Скрыть левый край (default is false) - указывает скрытое или отображаемое состояние левого края рамки. |
| [getHideRight()](#getHideRight--) | Скрыть правый край (default is false) - указывает скрытое или отображаемое состояние правого края рамки. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Скрыть правый край (default is false) - указывает скрытое или отображаемое состояние правого края рамки. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Зачёркнутый горизонтальный (default is false) - указывает скрытое или отображаемое состояние горизонтальной линии зачеркивания. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Зачёркнутый горизонтальный (default is false) - указывает скрытое или отображаемое состояние горизонтальной линии зачеркивания. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Зачёркнутый вертикальный (default is false) - указывает скрытое или отображаемое состояние вертикальной линии зачеркивания. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Зачёркнутый вертикальный (default is false) - указывает скрытое или отображаемое состояние вертикальной линии зачеркивания. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Зачёркнутый от нижнего левого к верхнему правому (default is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Зачёркнутый от нижнего левого к верхнему правому (default is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Зачёркнутый от верхнего левого к нижнему правому (default is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Зачёркнутый от верхнего левого к нижнему правому (default is false). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Базовый аргумент

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```


Скрыть верхний край (default is false) - указывает скрытое или отображаемое состояние верхнего края рамки.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Возвращаемое значение:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```


Скрыть верхний край (default is false) - указывает скрытое или отображаемое состояние верхнего края рамки.

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```


Скрыть нижний край (default is false) - указывает скрытое или отображаемое состояние нижнего края рамки.

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Возвращаемое значение:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```


Скрыть нижний край (default is false) - указывает скрытое или отображаемое состояние нижнего края рамки.

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```


Скрыть левый край (default is false) - указывает скрытое или отображаемое состояние левого края рамки.

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Возвращаемое значение:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```


Скрыть левый край (default is false) - указывает скрытое или отображаемое состояние левого края рамки.

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```


Скрыть правый край (default is false) - указывает скрытое или отображаемое состояние правого края рамки.

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Возвращаемое значение:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```


Скрыть правый край (default is false) - указывает скрытое или отображаемое состояние правого края рамки.

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```


Зачёркнутый горизонтальный (default is false) - указывает скрытое или отображаемое состояние горизонтальной линии зачеркивания.

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Возвращаемое значение:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```


Зачёркнутый горизонтальный (default is false) - указывает скрытое или отображаемое состояние горизонтальной линии зачеркивания.

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```


Зачёркнутый вертикальный (default is false) - указывает скрытое или отображаемое состояние вертикальной линии зачеркивания.

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Возвращаемое значение:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```


Зачёркнутый вертикальный (default is false) - указывает скрытое или отображаемое состояние вертикальной линии зачеркивания.

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```


Зачёркнутый от нижнего левого к верхнему правому (default is false).

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Возвращаемое значение:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```


Зачёркнутый от нижнего левого к верхнему правому (default is false). Указывает скрытое или отображаемое состояние диагональной линии зачеркивания от нижнего левого угла к верхнему правому углу рамки.

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```


Зачёркнутый от верхнего левого к нижнему правому (default is false). Указывает скрытое или отображаемое состояние диагональной линии зачеркивания от верхнего левого угла к нижнему правому углу рамки.

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Возвращаемое значение:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```


Зачёркнутый от верхнего левого к нижнему правому (default is false). Указывает скрытое или отображаемое состояние диагональной линии зачеркивания от верхнего левого угла к нижнему правому углу рамки.

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |