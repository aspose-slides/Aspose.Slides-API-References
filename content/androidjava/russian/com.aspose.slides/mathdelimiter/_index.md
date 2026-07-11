---
title: MathDelimiter
second_title: Aspose.Slides для Android через справочник Java API
description: Определяет объект-разделитель, состоящий из открывающих и закрывающих символов, таких как скобки, фигурные скобки, квадратные скобки и вертикальные черты, а также одного или нескольких математических элементов внутри, разделённых указанным символом.
type: docs
url: /ru/com.aspose.slides/mathdelimiter/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Определяет объект-разделитель, состоящий из символов открытия и закрытия (например, скобки, фигурные скобки, квадратные скобки и вертикальные черты) и одного или нескольких математических элементов внутри, разделённых указанным символом. Examples: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [getBeginningCharacter()](#getBeginningCharacter--) | Символ начала разделителя указывает начальный, или открывающий, символ разделителя. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Символ начала разделителя указывает начальный, или открывающий, символ разделителя. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Символ разделителя указывает символ, который разделяет аргументы в объекте разделителя. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Символ разделителя указывает символ, который разделяет аргументы в объекте разделителя. |
| [getEndingCharacter()](#getEndingCharacter--) | Символ окончания разделителя указывает конечный, или закрывающий, символ разделителя. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Символ окончания разделителя указывает конечный, или закрывающий, символ разделителя. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда true, разделители растут вертикально, чтобы соответствовать высоте операнда. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда true, разделители растут вертикально, чтобы соответствовать высоте операнда. |
| [getDelimiterShape()](#getDelimiterShape--) | Указывает форму разделителей в объекте разделителя. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Указывает форму разделителей в объекте разделителя. |
| [delimit(char separatorCharacter)](#delimit-char-) | Разделяет аргументы, используя указанный символ разделителя |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Обрамляет математический элемент в указанных символах, таких как скобки или другие символы, в качестве рамки |
| [getChildren()](#getChildren--) | Получить дочерние элементы |
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

**Возвращает:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```


Символ начала разделителя указывает начальный, или открывающий, символ разделителя. Математические разделители — это ограничительные символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Возвращает:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```


Символ начала разделителя указывает начальный, или открывающий, символ разделителя. Математические разделители — это ограничительные символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: '('.

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


Символ разделителя указывает символ, который разделяет аргументы в объекте разделителя. По умолчанию: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Возвращает:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```


Символ разделителя указывает символ, который разделяет аргументы в объекте разделителя. По умолчанию: '|'.

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


Символ окончания разделителя указывает конечный, или закрывающий, символ разделителя. Математические разделители — это ограничительные символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Возвращает:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```


Символ окончания разделителя указывает конечный, или закрывающий, символ разделителя. Математические разделители — это ограничительные символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: ')'.

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


Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда true, разделители растут вертикально, чтобы соответствовать высоте операнда. Значение по умолчанию: true

--------------------

> ```
> Пример:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Возвращает:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```


Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда true, разделители растут вертикально, чтобы соответствовать высоте операнда. Значение по умолчанию: true

--------------------

> ```
> Пример:
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


Указывает форму разделителей в объекте разделителя. Когда значение MathDelimiterShape.Centered, разделители центрируются вокруг оси математического текста и продолжают подстраиваться под всю высоту их содержимого. Когда значение MathDelimiterShape.Match, их высота и форма изменяются, чтобы точно соответствовать содержимому.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Возвращает:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```


Указывает форму разделителей в объекте разделителя. Когда значение MathDelimiterShape.Centered, разделители центрируются вокруг оси математического текста и продолжают подстраиваться под всю высоту их содержимого. Когда значение MathDelimiterShape.Match, их высота и форма изменяются, чтобы точно соответствовать содержимому.

--------------------

> ```
> Пример:
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

**Возвращает:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Этот объект после применения символа разделителя
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


Обрамляет математический элемент в указанных символах, таких как скобки или другие символы, в качестве рамки

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

**Возвращает:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Если beginningCharacter и endingCharacter равны null, соответствующие свойства присваиваются только значениями и новый объект не создаётся (возвращает этот экземпляр). В противном случае возвращает новый математический элемент типа Delimiter, который включает указанные символы как рамку и этот экземпляр [MathDelimiter](../../com.aspose.slides/mathdelimiter) внутри.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Получить дочерние элементы

**Возвращает:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Свойства управляющих символов

**Возвращает:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps