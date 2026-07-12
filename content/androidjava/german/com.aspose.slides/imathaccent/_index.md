---
title: IMathAccent
second_title: Aspose.Slides für Android über Java API Referenz
description: Gibt die Akzentfunktion an, die aus einer Basis und einem kombinierenden diakritischen Zeichen besteht. Beispiel ud835udc4eu0301
type: docs
url: /de/com.aspose.slides/imathaccent/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Gibt die Akzentfunktion an, bestehend aus einer Basis und einem kombinierenden diakritischen Zeichen Beispiel: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Das Argument, auf das der Akzent angewendet wurde |
| [getCharacter()](#getCharacter--) | Akzentzeichen Der Wert sollte im Bereich von (U+0300\\u2013U+036F) oder (U+20D0\\u2013U+20EF) liegen. Standardwert: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Akzentzeichen Der Wert sollte im Bereich von (U+0300\\u2013U+036F) oder (U+20D0\\u2013U+20EF) liegen. Standardwert: Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Das Argument, auf das der Akzent angewendet wurde

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Akzentzeichen Der Wert sollte im Bereich von (U+0300\\u2013U+036F) oder (U+20D0\\u2013U+20EF) liegen. Standardwert: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Rückgabewert:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Akzentzeichen Der Wert sollte im Bereich von (U+0300\\u2013U+036F) oder (U+20D0\\u2013U+20EF) liegen. Standardwert: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char |  |