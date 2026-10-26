---
title: IMathAccent
second_title: Aspose.Slides för Android via Java API-referens
description: Specificerar accentfunktionen som består av ett grundtecken och ett kombinerande diakritiskt tecken. Exempel ud835udc4eu0301
type: docs
url: /sv/com.aspose.slides/imathaccent/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Anger accentfunktionen, bestående av en bas och ett kombinerande diakritiskt tecken Exempel: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Argumentet som accenten applicerades på |
| [getCharacter()](#getCharacter--) | Accenttecken Värdet bör ligga inom intervallet (U+0300\\u2013U+036F) eller(U+20D0\\u2013U+20EF) Standardvärde: Kombinerande cirkumflexaccent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accenttecken Värdet bör ligga inom intervallet (U+0300\\u2013U+036F) eller(U+20D0\\u2013U+20EF) Standardvärde: Kombinerande cirkumflexaccent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argumentet som accenten applicerades på

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Accenttecken Värdet bör ligga inom intervallet (U+0300\\u2013U+036F) eller(U+20D0\\u2013U+20EF) Standardvärde: Kombinerande cirkumflexaccent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Returnerar:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Accenttecken Värdet bör ligga inom intervallet (U+0300\\u2013U+036F) eller(U+20D0\\u2013U+20EF) Standardvärde: Kombinerande cirkumflexaccent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char |  |