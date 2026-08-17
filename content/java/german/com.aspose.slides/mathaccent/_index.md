---
title: MathAccent
second_title: Aspose.Slides für Java API-Referenz
description: Gibt die Akzentfunktion an, die aus einer Basis und einem kombinierenden diakritischen Zeichen besteht. Beispiel ud835udc4eu0301
type: docs
url: /de/com.aspose.slides/mathaccent/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Gibt die Akzentfunktion an, bestehend aus einer Basis und einem kombinierenden diakritischen Zeichen. Beispiel: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element mit dem Standardwert für das Akzentzeichen angewendet wird |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element angewendet wird |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Das Argument, auf das der Akzent angewendet wurde |
| [getCharacter()](#getCharacter--) | Akzentzeichen Der Wert sollte im Bereich von (U+0300\\u2013U+036F) oder (U+20D0\\u2013U+20EF) liegen. Standardwert: Kombinierender Zirkumflex-Akzent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Akzentzeichen Der Wert sollte im Bereich von (U+0300\\u2013U+036F) oder (U+20D0\\u2013U+20EF) liegen. Standardwert: Kombinierender Zirkumflex-Akzent (U+0302) |
| [getChildren()](#getChildren--) | Gibt Kind-Elemente zurück |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Steuerzeichen-Eigenschaften |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element mit dem Standardwert für das Akzentzeichen angewendet wird

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | ein mathematisches Element, auf das das Akzent angewendet wird |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element angewendet wird

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | mathematisches Element, auf das das Akzent angewendet wird |
| accentCharacter | char | Akzentzeichen |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Das Argument, auf das der Akzent angewendet wurde

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Akzentzeichen Der Wert sollte im Bereich von (U+0300\\u2013U+036F) oder (U+20D0\\u2013U+20EF) liegen. Standardwert: Kombinierender Zirkumflex-Akzent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Rückgabewert:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Akzentzeichen Der Wert sollte im Bereich von (U+0300\\u2013U+036F) oder (U+20D0\\u2013U+20EF) liegen. Standardwert: Kombinierender Zirkumflex-Akzent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gibt Kind-Elemente zurück

**Rückgabewert:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Steuerzeichen-Eigenschaften

**Rückgabewert:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps