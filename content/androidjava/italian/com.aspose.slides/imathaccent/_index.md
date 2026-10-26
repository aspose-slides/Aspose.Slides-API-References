---
title: IMathAccent
second_title: Riferimento API Java di Aspose.Slides per Android
description: Specifica la funzione di accento composta da una base e da un segno diacritico combinante. Esempio ud835udc4eu0301
type: docs
url: /it/com.aspose.slides/imathaccent/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Specifica la funzione di accento, composta da una base e un segno diacritico combinante. Esempio: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | L'argomento a cui è stato applicato l'accento |
| [getCharacter()](#getCharacter--) | Carattere di accento Il valore deve essere compreso nell'intervallo (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) Valore predefinito: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Carattere di accento Il valore deve essere compreso nell'intervallo (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) Valore predefinito: Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

L'argomento a cui è stato applicato l'accento

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```


**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Carattere di accento Il valore deve essere compreso nell'intervallo (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) Valore predefinito: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Restituisce:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Carattere di accento Il valore deve essere compreso nell'intervallo (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) Valore predefinito: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char |  |