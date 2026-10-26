---
title: IMathAccent
second_title: Aspose.Slides Androidra a Java API hivatkozás alapján
description: Meghatározza a hangsúlyfüggvényt, amely egy alapelemből és egy kombináló diakritikus jelből áll. Példa ud835udc4eu0301
type: docs
url: /hu/com.aspose.slides/imathaccent/
---
**Minden implementált interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Meghatározza a hangsúlyfüggvényt, amely egy alapból és egy kombináló diakritikus jelből áll. Példa: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Az argumentum, amelyre a hangsúly alkalmazva lett |
| [getCharacter()](#getCharacter--) | Hangsúly karakter. Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie. Alapértelmezett érték: Kombináló körív hangsúly (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Hangsúly karakter. Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie. Alapértelmezett érték: Kombináló körív hangsúly (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Az argumentum, amelyre a hangsúly alkalmazva lett

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Hangsúly karakter. Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie. Alapértelmezett érték: Kombináló körív hangsúly (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Visszatér:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Hangsúly karakter. Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie. Alapértelmezett érték: Kombináló körív hangsúly (U+0302)

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