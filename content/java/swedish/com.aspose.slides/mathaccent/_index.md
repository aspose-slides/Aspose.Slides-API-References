---
title: MathAccent
second_title: Aspose.Slides för Java API-referens
description: Anger accentfunktionen som består av en bas och ett kombinerande diakritiskt tecken Exempel ud835udc4eu0301
type: docs
url: /sv/com.aspose.slides/mathaccent/
---
**Arv:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Anger accentfunktionen, bestående av en bas och ett kombinerande diakritiskt tecken Exempel: \\ud835\\udc4e\\u0301

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
>  ```

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Skapar ett matematiskt accent som appliceras på ett angivet matematiskt element med standardvärdet för accenttecken |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Skapar ett matematiskt accent som appliceras på ett specificerat matematiskt element |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Argumentet som accenten applicerades på |
| [getCharacter()](#getCharacter--) | Accenttecken Värdet ska ligga inom intervallet (U+0300\\u2013U+036F) eller (U+20D0\\u2013U+20EF) Standardvärde: Kombinerande cirkumflexaccent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accenttecken Värdet ska ligga inom intervallet (U+0300\\u2013U+036F) eller (U+20D0\\u2013U+20EF) Standardvärde: Kombinerande cirkumflexaccent (U+0302) |
| [getChildren()](#getChildren--) | Hämta underordnade element |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Egenskaper för kontrolltecken |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```


Skapar ett matematiskt accent som appliceras på ett angivet matematiskt element med standardvärdet för accenttecken

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | ett matematiskt element för att applicera accent |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```


Skapar ett matematiskt accent som appliceras på ett specificerat matematiskt element

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
>  ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematisk element för att applicera accent |
| accentCharacter | char | accenttecken |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argumentet som accenten applicerades på

--------------------

> ```
> Exempel:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```


**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Accenttecken Värdet ska ligga inom intervallet (U+0300\\u2013U+036F) eller (U+20D0\\u2013U+20EF) Standardvärde: Kombinerande cirkumflexaccent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```


**Returnerar:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```


Accenttecken Värdet ska ligga inom intervallet (U+0300\\u2013U+036F) eller (U+20D0\\u2013U+20EF) Standardvärde: Kombinerande cirkumflexaccent (U+0302)

--------------------

> ```
> Exempel:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Hämta underordnade element

**Returnerar:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Egenskaper för kontrolltecken

**Returnerar:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps