---
title: IMathAccent
second_title: Aspose.Slides для Android через справку Java API
description: Указывает функцию акцента, состоящую из основы и комбинирующего диакритического знака. Пример ud835udc4eu0301
type: docs
url: /ru/com.aspose.slides/imathaccent/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Указывает функцию акцента, состоящую из основы и комбинирующего диакритического знака. Пример: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## Методы

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Аргумент, к которому был применён акцент |
| [getCharacter()](#getCharacter--) | Символ акцента. Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или (U+20D0\\u2013U+20EF). Значение по умолчанию: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Символ акцента. Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или (U+20D0\\u2013U+20EF). Значение по умолчанию: Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Аргумент, к которому был применён акцент

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
public abstract char getCharacter()
```

Символ акцента. Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или (U+20D0\\u2013U+20EF). Значение по умолчанию: Combining Circumflex Accent (U+0302)

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
public abstract void setCharacter(char value)
```

Символ акцента. Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или (U+20D0\\u2013U+20EF). Значение по умолчанию: Combining Circumflex Accent (U+0302)

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