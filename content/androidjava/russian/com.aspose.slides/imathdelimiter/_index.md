---
title: IMathDelimiter
second_title: Aspose.Slides для Android через справочник API Java
description: Определяет объект-разделитель, состоящий из открывающих и закрывающих символов, таких как скобки, фигурные скобки, квадратные скобки и вертикальные черты, а также одного или нескольких математических элементов внутри, разделённых указанным символом.
type: docs
url: /ru/com.aspose.slides/imathdelimiter/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Определяет объект-разделитель, состоящий из открывающих и закрывающих символов (например, скобок, фигурных скобок, квадратных скобок и вертикальных черт), а также одного или нескольких математических элементов внутри, разделённых указанным символом. Примеры: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getArguments()](#getArguments--) | Один или несколько математических элементов, разделённых символами-разделителями |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character указывает начальный, то есть открывающий, символ-разделитель. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character указывает начальный, то есть открывающий, символ-разделитель. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character указывает символ, который разделяет аргументы в объекте-разделителе. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character указывает символ, который разделяет аргументы в объекте-разделителе. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character указывает конечный, то есть закрывающий, символ-разделитель. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character указывает конечный, то есть закрывающий, символ-разделитель. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда true, разделители растут вертикально, чтобы соответствовать высоте их операнда. Значение по умолчанию — true |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда true, разделители растут вертикально, чтобы соответствовать высоте их операнда. Значение по умолчанию — true |
| [getDelimiterShape()](#getDelimiterShape--) | Указывает форму разделителей в объекте-разделителе. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Указывает форму разделителей в объекте-разделителе. |
| [delimit(char separatorCharacter)](#delimit-char-) | Разделяет аргументы, используя указанный символ-разделитель |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Один или несколько математических элементов, разделённых символами-разделителями

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Возвращаемое значение:**  
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```

Delimiter Beginning Character указывает начальный, то есть открывающий, символ-разделитель. Математические разделители — это охватывающие символы, такие как скобки, квадратные скобки и фигурные скобки. Значение по умолчанию: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Возвращаемое значение:**  
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```

Delimiter Beginning Character указывает начальный, то есть открывающий, символ-разделитель. Математические разделители — это охватывающие символы, такие как скобки, квадратные скобки и фигурные скобки. Значение по умолчанию: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

Delimiter Separator Character указывает символ, который разделяет аргументы в объекте-разделителе. Значение по умолчанию: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Возвращаемое значение:**  
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```

Delimiter Separator Character указывает символ, который разделяет аргументы в объекте-разделителе. Значение по умолчанию: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```

Delimiter Ending Character указывает конечный, то есть закрывающий, символ-разделитель. Математические разделители — это охватывающие символы, такие как скобки, квадратные скобки и фигурные скобки. Значение по умолчанию: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Возвращаемое значение:**  
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```

Delimiter Ending Character указывает конечный, то есть закрывающий, символ-разделитель. Математические разделители — это охватывающие символы, такие как скобки, квадратные скобки и фигурные скобки. Значение по умолчанию: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда true, разделители растут вертикально, чтобы соответствовать высоте их операнда. Значение по умолчанию — true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Возвращаемое значение:**  
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда true, разделители растут вертикально, чтобы соответствовать высоте их операнда. Значение по умолчанию — true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

Указывает форму разделителей в объекте-разделителе. Когда MathDelimiterShape.Centered, разделители центрируются относительно математической оси текста и могут быть подогнаны по всей высоте их содержимого. Когда MathDelimiterShape.Match, их высота и форма изменяются так, чтобы точно соответствовать содержимому.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Возвращаемое значение:**  
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```

Указывает форму разделителей в объекте-разделителе. Когда MathDelimiterShape.Centered, разделители центрируются относительно математической оси текста и могут быть подогнаны по всей высоте их содержимого. Когда MathDelimiterShape.Match, их высота и форма изменяются так, чтобы точно соответствовать содержимому.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Разделяет аргументы, используя указанный символ-разделитель

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| separatorCharacter | char | символ-разделитель |

**Возвращаемое значение:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Этот объект после применения символа-разделителя