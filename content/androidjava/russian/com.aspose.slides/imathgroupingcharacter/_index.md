---
title: IMathGroupingCharacter
second_title: Aspose.Slides для Android через справочник Java API
description: Указывает символ группировки над или под выражением, обычно чтобы подчеркнуть взаимосвязь между элементами
type: docs
url: /ru/com.aspose.slides/imathgroupingcharacter/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Указывает символ группировки над или под выражением, обычно чтобы подчеркнуть взаимосвязь между элементами

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Базовый аргумент |
| [getCharacter()](#getCharacter--) | Символ группировки Значение по умолчанию: U+23DF (Нижняя фигурная скобка) |
| [setCharacter(char value)](#setCharacter-char-) | Символ группировки Значение по умолчанию: U+23DF (Нижняя фигурная скобка) |
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


**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


Символ группировки Значение по умолчанию: U+23DF (Нижняя фигурная скобка)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Нижняя скобка
> ```


**Возвращает:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


Символ группировки Значение по умолчанию: U+23DF (Нижняя фигурная скобка)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Нижняя скобка
> ```

**Параметры:**
| Параметр | Тип | Описание |
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

**Возвращает:**
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```


Вертикальное выравнивание символа группировки. Указывает выравнивание объекта относительно базовой линии. Например, когда символ группировки находится над объектом, VerticalJustification со значением Top означает, что верхняя часть объекта находится на базовой линии; когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии. По умолчанию: Bottom для Position=Top и Top для Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Возвращает:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```


Вертикальное выравнивание символа группировки. Указывает выравнивание объекта относительно базовой линии. Например, когда символ группировки находится над объектом, VerticalJustification со значением Top означает, что верхняя часть объекта находится на базовой линии; когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии. По умолчанию: Bottom для Position=Top и Top для Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |