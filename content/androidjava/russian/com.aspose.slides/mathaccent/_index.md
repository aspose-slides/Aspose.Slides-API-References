---
title: MathAccent
second_title: Aspose.Slides для Android через Java API справочник
description: Указывает функцию акцента, состоящую из основы и комбинирующего диакритического знака. Пример ud835udc4eu0301
type: docs
url: /ru/com.aspose.slides/mathaccent/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Указывает функцию акцента, состоящую из основы и комбинирующего диакритического знака. Пример: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Создает математический акцент, применяемый к указанному математическому элементу, со значением символа акцента по умолчанию |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Создает математический акцент, применяемый к указанному математическому элементу |
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Аргумент, к которому был применен акцент |
| [getCharacter()](#getCharacter--) | Accent Character Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или (U+20D0\\u2013U+20EF). Значение по умолчанию: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или (U+20D0\\u2013U+20EF). Значение по умолчанию: Combining Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | Получить дочерние элементы |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

Создает математический акцент, применяемый к указанному математическому элементу со значением символа акцента по умолчанию

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент для применения акцента |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

Создает математический акцент, применяемый к указанному математическому элементу

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент для применения акцента |
| accentCharacter | char | символ акцента |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Аргумент, к которому был применен акцент

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Accent Character Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или (U+20D0\\u2013U+20EF). Значение по умолчанию: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Возвращаемое значение:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Accent Character Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или (U+20D0\\u2013U+20EF). Значение по умолчанию: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char |  |

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

Control Character Properties

**Возвращаемое значение:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps