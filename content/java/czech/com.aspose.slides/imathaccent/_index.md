---
title: IMathAccent
second_title: Aspose.Slides pro Java API Referenci
description: Určuje funkci akcentu, která se skládá ze základního a kombinujícího diakritického znaku. Příklad ud835udc4eu0301
type: docs
url: /cs/com.aspose.slides/imathaccent/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Určuje funkci akcentu, skládající se ze základní a kombinující diakritické značky Example: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Argument, na který byl akcent aplikován |
| [getCharacter()](#getCharacter--) | Znak akcentu Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF). Výchozí hodnota: Kombinující střelový akcent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Znak akcentu Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF). Výchozí hodnota: Kombinující střelový akcent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argument, na který byl akcent aplikován

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Znak akcentu Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF). Výchozí hodnota: Kombinující střelový akcent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Vrací:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Znak akcentu Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF). Výchozí hodnota: Kombinující střelový akcent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char |  |