---
title: IMathBorderBox
second_title: Aspose.Slides для Java – справочник API
description: Рисует прямоугольную или другую границу вокруг IMathElement.
type: docs
url: /ru/com.aspose.slides/imathborderbox/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Рисует прямоугольную или другую границу вокруг IMathElement.

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
| [getHideTop()](#getHideTop--) | Скрывать верхний край (по умолчанию false) — указывает скрытое или отображаемое состояние верхнего края рамки. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Скрывать верхний край (по умолчанию false) — указывает скрытое или отображаемое состояние верхнего края рамки. |
| [getHideBottom()](#getHideBottom--) | Скрывать нижний край (по умолчанию false) — указывает скрытое или отображаемое состояние нижнего края рамки. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Скрывать нижний край (по умолчанию false) — указывает скрытое или отображаемое состояние нижнего края рамки. |
| [getHideLeft()](#getHideLeft--) | Скрывать левый край (по умолчанию false) — указывает скрытое или отображаемое состояние левого края рамки. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Скрывать левый край (по уманию false) — указывает скрытое или отображаемое состояние левого края рамки. |
| [getHideRight()](#getHideRight--) | Скрывать правый край (по умолчанию false) — указывает скрытое или отображаемое состояние правого края рамки. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Скрывать правый край (по умолчанию false) — указывает скрытое или отображаемое состояние правого края рамки. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Зачёркивание по горизонтали (по умолчанию false) — указывает скрытое или отображаемое состояние горизонтальной линии зачеркивания. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Зачёркивание по горизонтали (по умолчанию false) — указывает скрытое или отображаемое состояние горизонтальной линии зачеркивания. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Зачёркивание по вертикали (по умолчанию false) — указывает скрытое или отображаемое состояние вертикальной линии зачеркивания. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Зачёркивание по вертикали (по умолчанию false) — указывает скрытое или отображаемое состояние вертикальной линии зачеркивания. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Зачёркивание от нижнего левого к верхнему правому (по умолчанию false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Зачёркивание от нижнего левого к верхнему правому (по умолчанию false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Зачёркивание от верхнего левого к нижнему правому (по умолчанию false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Зачёркивание от верхнего левого к нижнему правому (по умолчанию false). |

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

Скрывать верхний край (по умолчанию false) — указывает скрытое или отображаемое состояние верхнего края рамки.

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

Скрывать верхний край (по умолчанию false) — указывает скрытое или отображаемое состояние верхнего края рамки.

--------------------

> ```
> Example:
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

Скрывать нижний край (по умолчанию false) — указывает скрытое или отображаемое состояние нижнего края рамки.

--------------------

> ```
> Example:
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

Скрывать нижний край (по умолчанию false) — указывает скрытое или отображаемое состояние нижнего края рамки.

--------------------

> ```
> Example:
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

Скрывать левый край (по умолчанию false) — указывает скрытое или отображаемое состояние левого края рамки.

--------------------

> ```
> Example:
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

Скрывать левый край (по умолчанию false) — указывает скрытое или отображаемое состояние левого края рамки.

--------------------

> ```
> Example:
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

Скрывать правый край (по умолчанию false) — указывает скрытое или отображаемое состояние правого края рамки.

--------------------

> ```
> Example:
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

Скрывать правый край (по умолчанию false) — указывает скрытое или отображаемое состояние правого края рамки.

--------------------

> ```
> Example:
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

Зачёркивание по горизонтали (по умолчанию false) — указывает скрытое или отображаемое состояние горизонтальной линии зачеркивания.

--------------------

> ```
> Example:
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

Зачёркивание по горизонтали (по умолчанию false) — указывает скрытое или отображаемое состояние горизонтальной линии зачеркивания.

--------------------

> ```
> Example:
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

Зачёркивание по вертикали (по умолчанию false) — указывает скрытое или отображаемое состояние вертикальной линии зачеркивания.

--------------------

> ```
> Example:
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

Зачёркивание по вертикали (по умолчанию false) — указывает скрытое или отображаемое состояние вертикальной линии зачеркивания.

--------------------

> ```
> Example:
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

Зачёркивание от нижнего левого к верхнему правому (по умолчанию false). Указывает скрытое или отображаемое состояние диагональной линии зачеркивания от нижнего левого угла к верхнему правому углу рамки.

--------------------

> ```
> Example:
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

Зачёркивание от нижнего левого к верхнему правому (по умолчанию false). Указывает скрытое или отображаемое состояние диагональной линии зачеркивания от нижнего левого угла к верхнему правому углу рамки.

--------------------

> ```
> Example:
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

Зачёркивание от верхнего левого к нижнему правому (по умолчанию false). Указывает скрытое или отображаемое состояние диагональной линии зачеркивания от верхнего левого угла к нижнему правому углу рамки.

--------------------

> ```
> Example:
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

Зачёркивание от верхнего левого к нижнему правому (по умолчанию false). Указывает скрытое или отображаемое состояние диагональной линии зачеркивания от верхнего левого угла к нижнему правому углу рамки.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |