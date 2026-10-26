---
title: IMathAccent
second_title: Aspose.Slides pro Android prostřednictvím referenční dokumentace Java API
description: Určuje funkci přízvuku skládající se ze základny a kombinující diakritické značky. Příklad ud835udc4eu0301
type: docs
url: /cs/com.aspose.slides/imathaccent/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Určuje funkci přízvuku, která se skládá ze základny a kombinující diakritické značky Příklad: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Argument, ke kterému byl příznak aplikován |
| [getCharacter()](#getCharacter--) | Znak přízvuku Hodnota by měla být v rozmezí (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF) Výchozí hodnota: Kombinující stříškový příznak (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Znak přízvuku Hodnota by měla být v rozmezí (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF) Výchozí hodnota: Kombinující stříškový příznak (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argument, ke kterému byl příznak aplikován

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

Znak přízvuku Hodnota by měla být v rozmezí (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF) Výchozí hodnota: Kombinující stříškový příznak (U+0302)

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

Znak přízvuku Hodnota by měla být v rozmezí (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF) Výchozí hodnota: Kombinující stříškový příznak (U+0302)

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