---
title: MathAccent
second_title: Aspose.Slides voor Java API-referentie
description: Specificeert de accentfunctie die bestaat uit een basis en een samenvoegende diakritische markering Voorbeeld ud835udc4eu0301
type: docs
url: /nl/com.aspose.slides/mathaccent/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Specificeert de accentfunctie, bestaande uit een basis en een samenvoegende diakritische markering Voorbeeld: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Creëert een wiskundige accent die wordt toegepast op een specifiek wiskunde-element met de standaard-accentkarakterwaarde |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Creëert een wiskundige accent die wordt toegepast op een specifiek wiskunde-element |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Het argument waarop het accent werd toegepast |
| [getCharacter()](#getCharacter--) | Accent Character De waarde moet binnen het bereik (U+0300\\u2013U+036F) of (U+20D0\\u2013U+20EF) liggen Standaardwaarde: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character De waarde moet binnen het bereik (U+0300\\u2013U+036F) of (U+20D0\\u2013U+20EF) liggen Standaardwaarde: Combining Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | Haal kind-elementen op |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

Creëert een wiskundige accent die wordt toegepast op een specifiek wiskunde-element met de standaard-accentkarakterwaarde

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | een wiskundig element om een accent toe te passen |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

Creëert een wiskundige accent die wordt toegepast op een specifiek wiskunde-element

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskundig element om accent toe te passen |
| accentCharacter | char | accentteken |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Het argument waarop het accent werd toegepast

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
public final char getCharacter()
```

Accent Character De waarde moet binnen het bereik (U+0300\\u2013U+036F) of (U+20D0\\u2013U+20EF) liggen Standaardwaarde: Combining Circumflex Accent (U+0302)

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
public final void setCharacter(char value)
```

Accent Character De waarde moet binnen het bereik (U+0300\\u2013U+036F) of (U+20D0\\u2013U+20EF) liggen Standaardwaarde: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Haal kind-elementen op

**Retour:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**Retour:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps