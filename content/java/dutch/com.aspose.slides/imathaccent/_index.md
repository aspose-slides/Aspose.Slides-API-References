---
title: IMathAccent
second_title: Aspose.Slides voor Java API-referentie
description: Specificeert de accentfunctie bestaande uit een basis en een combinatiediacritisch teken Voorbeeld ud835udc4eu0301
type: docs
url: /nl/com.aspose.slides/imathaccent/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Specificeert de accentfunctie, bestaande uit een basis en een combinatiediacritisch teken Voorbeeld: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## Methoden

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Het argument waarop het accent is toegepast |
| [getCharacter()](#getCharacter--) | Accentteken De waarde moet binnen het bereik (U+0300\\u2013U+036F) of (U+20D0\\u2013U+20EF) liggen Standaardwaarde: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accentteken De waarde moet binnen het bereik (U+0300\\u2013U+036F) of (U+20D0\\u2013U+20EF) liggen Standaardwaarde: Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Het argument waarop het accent is toegepast

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Accentteken De waarde moet binnen het bereik (U+0300\\u2013U+036F) of (U+20D0\\u2013U+20EF) liggen Standaardwaarde: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Retour:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Accentteken De waarde moet binnen het bereik (U+0300\\u2013U+036F) of (U+20D0\\u2013U+20EF) liggen Standaardwaarde: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |