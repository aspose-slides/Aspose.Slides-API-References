---
title: MathAccent
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Megadja az akcentus függvényt, amely egy alapelemből és egy kombináló diakritikus jelből áll. Példa ud835udc4eu0301
type: docs
url: /hu/com.aspose.slides/mathaccent/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**  
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Meghatározza az akcentus funkciót, amely egy alapból és egy kombináló diakritikus jelből áll. Példa: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Létrehoz egy matematikai akcentust, amely egy megadott matematikai elemre alkalmazza az alapértelmezett akcentus karakter értékkel |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Létrehoz egy matematikai akcentust, amely egy megadott matematikai elemre alkalmazza |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Az argumentum, amelyhez az akcentus alkalmazva lett |
| [getCharacter()](#getCharacter--) | Akcentus karakter. Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie. Alapértelmezett érték: Kombináló köríves akcentus (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Akcentus karakter. Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie. Alapértelmezett érték: Kombináló köríves akcentus (U+0302) |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontroll karakter tulajdonságok |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

Létrehoz egy matematikai akcentust, amely egy megadott matematikai elemre alkalmazza az alapértelmezett akcentus karakter értékkel

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | egy matematikai elem, amelyre az akcentust alkalmazzuk |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

Létrehoz egy matematikai akcentust, amely egy megadott matematikai elemre alkalmazza

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem, amelyre az akcentust alkalmazzuk |
| accentCharacter | char | akcentus karakter |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Az argumentum, amelyhez az akcentus alkalmazva lett

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
public final char getCharacter()
```

Akcentus karakter. Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie. Alapértelmezett érték: Kombináló köríves akcentus (U+0302)

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
public final void setCharacter(char value)
```

Akcentus karakter. Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie. Alapértelmezett érték: Kombináló köríves akcentus (U+0302)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gyermekelemek lekérése

**Visszatérési érték:**  
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Kontroll karakter tulajdonságok

**Visszatérési érték:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps