---
title: IMathAccent
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Spécifie la fonction d'accent composée d'une base et d'une marque diacritique combinée Exemple ud835udc4eu0301
type: docs
url: /fr/com.aspose.slides/imathaccent/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Spécifie la fonction d'accent, composée d'une base et d'une marque diacritique combinée Exemple: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | The argument to which the accent was applied |
| [getCharacter()](#getCharacter--) | Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

The argument to which the accent was applied

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Accent Character The value should be within the range of (U+0300\u2013U+036F) or(U+20D0\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Returns:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)


Caractère d'accent La valeur doit être comprise dans la plage (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valeur par défaut: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char |  |