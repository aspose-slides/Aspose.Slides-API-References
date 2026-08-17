---
title: IMathGroupingCharacter
second_title: Aspose.Slides для Java: справочник API
description: Указывает символ группировки над или под выражением, обычно для выделения взаимосвязи элементов
type: docs
url: /ru/com.aspose.slides/imathgroupingcharacter/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Указывает символ группировки над или под выражением, обычно для выделения взаимосвязи элементов

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Методы

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Базовый аргумент |
| [getCharacter()](#getCharacter--) | Символ группировки Значение по умолчанию: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Символ группировки Значение по умолчанию: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Позиция символа группировки. |
| [setPosition(int value)](#setPosition-int-) | Позиция символа группировки. |
| [getVerticalJustification()](#getVerticalJustification--) | Вертикальное выравнивание символа группировки. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Вертикальное выравнивание символа группировки. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Базовый аргумент

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Символ группировки Значение по умолчанию: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Нижняя скобка
> ```

**Возвращаемое значение:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Символ группировки Значение по умолчанию: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Нижняя скобка
> ```


**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Позиция символа группировки. По умолчанию: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Возвращаемое значение:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Позиция символа группировки. По умолчанию: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```

Вертикальное выравнивание символа группы. Указывает выравнивание объекта относительно базовой линии. Например, когда символ группы находится над объектом, VerticalJustification со значением Top означает, что верхняя часть объекта падает на базовую линию; когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии. По умолчанию: Bottom для Position=Top и Top для Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Возвращаемое значение:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

Вертикальное выравнивание символа группы. Указывает выравнивание объекта относительно базовой линии. Например, когда символ группы находится над объектом, VerticalJustification со значением Top означает, что верхняя часть объекта падает на базовую линию; когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии. По умолчанию: Bottom для Position=Top и Top для Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |