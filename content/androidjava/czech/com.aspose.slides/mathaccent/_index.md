---
title: MathAccent
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Určuje funkci akcentu skládající se ze základny a kombinující diakritické značky. Příklad ud835udc4eu0301
type: docs
url: /cs/com.aspose.slides/mathaccent/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Určuje funkci akcentu, která se skládá ze základny a kombinující diakritické značky. Příklad: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Vytvoří matematický akcent aplikovaný na zadaný matematický prvek s výchozí hodnotou znaku akcentu |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Vytvoří matematický akcent aplikovaný na zadaný matematický prvek |
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Argument, ke kterému byl akcent aplikován |
| [getCharacter()](#getCharacter--) | Znak akcentu. Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF). Výchozí hodnota: Kombinovaný stříškový akcent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Znak akcentu. Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF). Výchozí hodnota: Kombinovaný stříškový akcent (U+0302) |
| [getChildren()](#getChildren--) | Získat podřízené prvky |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vlastnosti řídícího znaku |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```


Vytvoří matematický akcent aplikovaný na zadaný matematický prvek s výchozí hodnotou znaku akcentu

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element, na který se aplikuje akcent |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```


Vytvoří matematický akcent aplikovaný na zadaný matematický prvek

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element, na který se aplikuje akcent |
| accentCharacter | char | znak akcentu |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argument, ke kterému byl akcent aplikován

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
public final char getCharacter()
```


Znak akcentu. Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF). Výchozí hodnota: Kombinovaný stříškový akcent (U+0302)

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
public final void setCharacter(char value)
```


Znak akcentu. Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF). Výchozí hodnota: Kombinovaný stříškový akcent (U+0302)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Získat podřízené prvky

**Vrací:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Vlastnosti řídícího znaku

**Vrací:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps