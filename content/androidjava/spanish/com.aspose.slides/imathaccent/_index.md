---
title: IMathAccent
second_title: Aspose.Slides para Android mediante la referencia de API de Java
description: Especifica la función de acento que consiste en una base y una marca diacrítica combinante Ejemplo ud835udc4eu0301
type: docs
url: /es/com.aspose.slides/imathaccent/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Especifica la función de acento, que consiste en una base y una marca diacrítica combinante Ejemplo: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | El argumento al que se aplicó el acento |
| [getCharacter()](#getCharacter--) | Carácter de acento El valor debe estar dentro del rango de (U+0300\\u2013U+036F) o(U+20D0\\u2013U+20EF) Valor predeterminado: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Carácter de acento El valor debe estar dentro del rango de (U+0300\\u2013U+036F) o(U+20D0\\u2013U+20EF) Valor predeterminado: Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

El argumento al que se aplicó el acento

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Carácter de acento El valor debe estar dentro del rango de (U+0300\\u2013U+036F) o(U+20D0\\u2013U+20EF) Valor predeterminado: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Devuelve:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Carácter de acento El valor debe estar dentro del rango de (U+0300\\u2013U+036F) o(U+20D0\\u2013U+20EF) Valor predeterminado: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char |  |