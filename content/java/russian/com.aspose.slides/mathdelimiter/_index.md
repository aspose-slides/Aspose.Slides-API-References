---
title: MathDelimiter
second_title: Справочник API Aspose.Slides для Java
description: Определяет объект разделителя, состоящий из открывающих и закрывающих символов, таких как скобки, фигурные скобки, квадратные скобки и вертикальные черты, а также одного или нескольких математических элементов внутри, разделённых указанным символом.
type: docs
url: /ru/com.aspose.slides/mathdelimiter/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Определяет объект разделителя, состоящий из открывающих и закрывающих символов (например, скобок, фигурных скобок, квадратных скобок и вертикальных черт) и одного или нескольких математических элементов внутри, разделённых указанным символом. Примеры: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Инициализирует MathDelimiter указанным элементом в качестве единственного базового аргумента |
## Методы

| Метод | Описание |
| --- | --- |
| [getArguments()](#getArguments--) | Один или несколько математических элементов, разделённых символами разделителя |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character указывает начальный, то есть открывающий, символ разделителя. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character указывает начальный, то есть открывающий, символ разделителя. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character указывает символ, который разделяет аргументы в объекте разделителя. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character указывает символ, который разделяет аргументы в объекте разделителя. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character указывает конечный, то есть закрывающий, символ разделителя. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character указывает конечный, то есть закрывающий, символ разделителя. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда значение истинно, разделители растут вертикально, чтобы соответствовать высоте операнда. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда значение истинно, разделители растут вертикально, чтобы соответствовать высоте операнда. |
| [getDelimiterShape()](#getDelimiterShape--) | Указывает форму разделителей в объекте разделителя. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Указывает форму разделителей в объекте разделителя. |
| [delimit(char separatorCharacter)](#delimit-char-) | Разделяет аргументы, используя указанный символ разделителя |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Обрамляет математический элемент указанными символами, например скобками или другими символами в качестве рамки |
| [getChildren()](#getChildren--) | Получает дочерние элементы |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Свойства управляющих символов |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Инициализирует MathDelimiter указанным элементом в качестве единственного базового аргумента

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Базовый элемент, к которому применяется разделитель. Может быть null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Один или несколько математических элементов, разделённых символами разделителя

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
public final char getBeginningCharacter()
```

Delimiter Beginning Character указывает начальный, то есть открывающий, символ разделителя. Математические разделители — это ограничивающие символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: '('.

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
public final void setBeginningCharacter(char value)
```

Delimiter Beginning Character указывает начальный, то есть открывающий, символ разделителя. Математические разделители — это ограничивающие символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: '('.

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
public final char getSeparatorCharacter()
```

Delimiter Separator Character указывает символ, который разделяет аргументы в объекте разделителя. По умолчанию: '|'.

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
public final void setSeparatorCharacter(char value)
```

Delimiter Separator Character указывает символ, который разделяет аргументы в объекте разделителя. По умолчанию: '|'.

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
public final char getEndingCharacter()
```

Delimiter Ending Character указывает конечный, то есть закрывающий, символ разделителя. Математические разделители — это ограничивающие символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: ')'.

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
public final void setEndingCharacter(char value)
```

Delimiter Ending Character указывает конечный, то есть закрывающий, символ разделителя. Математические разделители — это ограничивающие символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: ')'.

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
public final boolean getGrowToMatchOperandHeight()
```

Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда значение истинно, разделители растут вертикально, чтобы соответствовать высоте операнда. Значение по умолчанию — true

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
public final void setGrowToMatchOperandHeight(boolean value)
```

Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда значение истинно, разделители растут вертикально, чтобы соответствовать высоте операнда. Значение по умолчанию — true

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
public final int getDelimiterShape()
```

Указывает форму разделителей в объекте разделителя. Когда форма — MathDelimiterShape.Centered, разделители центрируются вокруг математической оси текста и могут быть масштабированы до полной высоты их содержимого. Когда форма — MathDelimiterShape.Match, их высота и форма изменяются, чтобы точно соответствовать содержимому.

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
public final void setDelimiterShape(int value)
```

Указывает форму разделителей в объекте разделителя. Когда форма — MathDelimiterShape.Centered, разделители центрируются вокруг математической оси текста и могут быть масштабированы до полной высоты их содержимого. Когда форма --- MathDelimiterShape.Match, их высота и форма изменяются, чтобы точно соответствовать содержимому.

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
public final IMathDelimiter delimit(char separatorCharacter)
```

Разделяет аргументы, используя указанный символ разделителя

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| separatorCharacter | char | символ разделителя |

**Возвращаемое значение:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Этот объект после применения символа разделителя
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Обрамляет математический элемент указанными символами, например скобками или другими символами в качестве рамки

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| beginningCharacter | char | Начальный символ (обычно левая скобка) |
| endingCharacter | char | Конечный символ (обычно правая скобка) |

**Возвращаемое значение:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Если beginningCharacter и endingCharacter равны null, соответствующие свойства получают только значения и новый объект не создаётся (возвращается текущий экземпляр). В противном случае возвращается новый математический элемент типа Delimiter, который включает указанные символы в качестве рамки и текущий экземпляр [MathDelimiter](../../com.aspose.slides/mathdelimiter) внутри.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Получает дочерние элементы

**Возвращаемое значение:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Свойства управляющих символов

**Возвращаемое значение:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps