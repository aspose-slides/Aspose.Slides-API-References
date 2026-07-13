---
title: IMathAccent
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Określa funkcję akcentu, składającą się z podstawy i łączącego znaku diakrytycznego. Przykład ud835udc4eu0301
type: docs
url: /pl/com.aspose.slides/imathaccent/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Określa funkcję akcentu, składającą się z podstawy i łączącego znaku diakrytycznego. Przykład: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument, do którego zastosowano akcent |
| [getCharacter()](#getCharacter--) | Znak akcentu. Wartość powinna mieścić się w zakresie (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF). Domyślna wartość: Łączący akcent kąta (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Znak akcentu. Wartość powinna mieścić się w zakresie (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF). Domyślna wartość: Łączący akcent kąta (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument, do którego zastosowano akcent

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


Znak akcentu. Wartość powinna mieścić się w zakresie (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF). Domyślna wartość: Łączący akcent kąta (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Zwraca:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


Znak akcentu. Wartość powinna mieścić się w zakresie (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF). Domyślna wartość: Łączący akcent kąta (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |