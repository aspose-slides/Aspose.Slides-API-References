---
title: MathBorderBox
second_title: Aspose.Slides для Android через справочник Java API
description: Рисует прямоугольную или другую рамку вокруг IMathElement.
type: docs
url: /ru/com.aspose.slides/mathborderbox/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Рисует прямоугольную или другую рамку вокруг IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Создаёт элемент MathBorderBox с прямоугольной рамкой |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Создаёт элемент MathBorderBox |
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Базовый аргумент |
| [getHideTop()](#getHideTop--) | Скрыть верхний край (по умолчанию false) - указывает скрытое или показанное состояние верхнего края рамки. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Скрыть верхний край (по умолчанию false) - указывает скрытое или показанное состояние верхнего края рамки. |
| [getHideBottom()](#getHideBottom--) | Скрыть нижний край (по умолчанию false) - указывает скрытое или показанное состояние нижнего края рамки. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Скрыть нижний край (по умолчанию false) - указывает скрытое или показанное состояние нижнего края рамки. |
| [getHideLeft()](#getHideLeft--) | Скрыть левый край (по умолчанию false) - указывает скрытое или показанное состояние левого края рамки. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Скрыть левый край (по умолчанию false) - указывает скрытое или показанное состояние левого края рамки. |
| [getHideRight()](#getHideRight--) | Скрыть правый край (по умолчанию false) - указывает скрытое или показанное состояние правого края рамки. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Скрыть правый край (по умолчанию false) - указывает скрытое или показанное состояние правого края рамки. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Перечёркивание по горизонтали (по умолчанию false) - указывает скрытое или показанное состояние горизонтальной линии перечёркивания. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Перечёркивание по горизонтали (по умолчанию false) - указывает скрытое или показанное состояние горизонтальной линии перечёркивания. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Перечёркивание по вертикали (по умолчанию false) - указывает скрытое или показанное состояние вертикальной линии перечёркивания. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Перечёркивание по вертикали (по умание false) - указывает скрытое или показанное состояние вертикальной линии перечёркивания. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Перечёркивание снизу слева вверх справа (по умолчанию false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Перечёркивание снизу слева вверх справа (по умолчанию false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Перечёркивание сверху слева вниз справа (по умолчанию false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Перечёркивание сверху слева вниз справа (по умолчанию false). |
| [getChildren()](#getChildren--) | Получить дочерние элементы |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Свойства управляющих символов |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```


Создаёт элемент MathBorderBox с прямоугольной рамкой

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Базовый элемент, к которому применяется рамка. Может быть null. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Создаёт элемент MathBorderBox

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Базовый элемент, к которому применяется рамка |
| hideTop | boolean | Скрыть верхний край |
| hideBottom | boolean | Скрыть нижний край |
| hideLeft | boolean | Скрыть левый край |
| hideRight | boolean | Скрыть правый край |
| strikethroughHorizontal | boolean | Перечёркивание по горизонтали |
| strikethroughVertical | boolean | Перечёркивание по вертикали |
| strikethroughBottomLeftToTopRight | boolean | Перечёркивание снизу слева вверх справа |
| strikethroughTopLeftToBottomRight | boolean | Перечёркивание сверху слева вниз справа |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Базовый аргумент

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```


Скрыть верхний край (по умолчанию false) - указывает скрытое или показанное состояние верхнего края рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Возвращаемое значение:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```


Скрыть верхний край (по умолчанию false) - указывает скрытое или показанное состояние верхнего края рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```


Скрыть нижний край (по умолчанию false) - указывает скрытое или показанное состояние нижнего края рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Возвращаемое значение:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```


Скрыть нижний край (по умолчанию false) - указывает скрытое или показанное состояние нижнего края рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```


Скрыть левый край (по умолчанию false) - указывает скрытое или показанное состояние левого края рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Возвращаемое значение:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```


Скрыть левый край (по умолчанию false) - указывает скрытое или показанное состояние левого края рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```


Скрыть правый край (по умолчанию false) - указывает скрытое или показанное состояние правого края рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Возвращаемое значение:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```


Скрыть правый край (по умание false) - указывает скрытое или показанное состояние правого края рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```


Перечёркивание по горизонтали (по умолчанию false) - указывает скрытое или показанное состояние горизонтальной линии перечёркивания.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Возвращаемое значение:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```


Перечёркивание по горизонтали (по умолчанию false) - указывает скрытое или показанное состояние горизонтальной линии перечёркивания.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```


Перечёркивание по вертикали (по умолчанию false) - указывает скрытое или показанное состояние вертикальной линии перечёркивания.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Возвращаемое значение:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```


Перечёркивание по вертикали (по умолчанию false) - указывает скрытое или показанное состояние вертикальной линии перечёркивания.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```


Перечёркивание снизу слева вверх справа (по умолчанию false). Указывает скрытое или показанное состояние перечёркивающей диагональной линии от нижнего левого угла к верхнему правому углу рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Возвращаемое значение:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```


Перечёркивание снизу слева вверх справа (по умолчанию false). Указывает скрытое или показанное состояние перечёркивающей диагональной линии от нижнего левого угла к верхнему правому углу рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```


Перечёркивание сверху слева вниз справа (по умолчанию false). Указывает скрытое или показанное состояние перечёркивающей диагональной линии от верхнего левого угла к нижнему правому углу рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Возвращаемое значение:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```


Перечёркивание сверху слева вниз справа (по умолчанию false). Указывает скрытое или показанное состояние перечёркивающей диагональной линии от верхнего левого угла к нижнему правому углу рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Получить дочерние элементы

**Возвращаемое значение:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Свойства управляющих символов

**Возвращаемое значение:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps