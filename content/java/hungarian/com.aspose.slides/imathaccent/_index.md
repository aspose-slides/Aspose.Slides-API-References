---
title: IMathAccent
second_title: Aspose.Slides a Java API referencia
description: Megadja a hangsúly funkciót, amely egy alapot és egy kombináló diakritikus jelet tartalmaz. Példa ud835udc4eu0301
type: docs
url: /hu/com.aspose.slides/imathaccent/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Meghatározza a hangsúly funkciót, amely egy alapot és egy kombináló diakritikus jelet tartalmaz. Példa: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Az argumentum, amelyre a hangsúlyt alkalmazták |
| [getCharacter()](#getCharacter--) | Accent Character Az értéknek a (U+0300–U+036F) vagy (U+20D0–U+20EF) tartományon belül kell lennie. Alapértelmezett érték: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character Az értéknek a (U+0300–U+036F) vagy (U+20D0–U+20EF) tartományon belül kell lennie. Alapértelmezett érték: Combining Circumflex Accent (U+0302) |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Az argumentum, amelyre a hangsúlyt alkalmazták

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Accent Character Az értéknek a (U+0300–U+036F) vagy (U+20D0–U+20EF) tartományon belül kell lennie. Alapértelmezett érték: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Visszatérési érték:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Accent Character Az értéknek a (U+0300–U+036F) vagy (U+20D0–U+20EF) tartományon belül kell lennie. Alapértelmezett érték: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char |  |