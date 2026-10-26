---
title: MathAccent
second_title: Aspose.Slides Java API-referencia
description: Meghatározza a felhúzási funkciót, amely egy bázisból és egy kombináló diakritikus jelből áll. Példa ud835udc4eu0301
type: docs
url: /hu/com.aspose.slides/mathaccent/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```java
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Meghatározza a felhúzott funkciót, amely egy bázisból és egy kombináló diakritikus jelből áll Example: \\ud835\\udc4e\\u0301

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
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Létrehozza a matematikai felhúzást, amely egy megadott matematikai elemre alkalmazza az alapértelmezett felhúzási karakterértékkel |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Létrehozza a matematikai felhúzást, amely egy megadott matematikai elemre alkalmaz |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Az argumentum, amelyhez a felhúzás alkalmazva lett |
| [getCharacter()](#getCharacter--) | Felhúzási karakter Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie Alapértelmezett érték: Kombináló körkörös felhúzás (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Felhúzási karakter Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie Alapértelmezett érték: Kombináló körkörös felhúzás (U+0302) |
| [getChildren()](#getChildren--) | Gyerek elemek lekérése |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontroll karakter tulajdonságok |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```


Létrehozza a matematikai felhúzást, amely egy megadott matematikai elemre alkalmazza az alapértelmezett felhúzási karakterértékkel

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | egy matematikai elem, amelyre a felhúzást alkalmazzuk |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```


Létrehozza a matematikai felhúzást, amely egy megadott matematikai elemre alkalmaz

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem, amelyre a felhúzást alkalmazzák |
| accentCharacter | char | felhúzási karakter |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Az argumentum, amelyhez a felhúzás alkalmazva lett

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
public final char getCharacter()
```


Felhúzási karakter Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie Alapértelmezett érték: Kombináló körkörös felhúzás (U+0302)

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
public final void setCharacter(char value)
```


Felhúzási karakter Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie Alapértelmezett érték: Kombináló körkörös felhúzás (U+0302)

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


Gyerek elemek lekérése

**Visszatér:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Kontroll karakter tulajdonságok

**Visszatér:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps