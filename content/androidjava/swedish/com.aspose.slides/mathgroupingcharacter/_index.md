---
title: MathGroupingCharacter
second_title: Aspose.Slides för Android via Java API-referens
description: Anger en gruppsymbol ovanför eller under ett uttryck, vanligtvis för att framhäva relationen mellan element
type: docs
url: /sv/com.aspose.slides/mathgroupingcharacter/
---
**Arv:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

Anger en gruppsymbol ovanför eller under ett uttryck, vanligtvis för att framhäva relationen mellan elementen

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Initierar en ny instans av klassen MathGroupingCharacter med standardgrupptecknet U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Initierar en ny instans av klassen MathGroupingCharacter. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Basargument |
| [getCharacter()](#getCharacter--) | Standardvärde för grupptecken: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Standardvärde för grupptecken: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Position för grupptecken. |
| [setPosition(int value)](#setPosition-int-) | Position för grupptecken. |
| [getVerticalJustification()](#getVerticalJustification--) | Vertikal justering av grupptecken. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Vertikal justering av grupptecken. |
| [getChildren()](#getChildren--) | Hämta barn element |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Egenskaper för kontrolltecken |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

Initierar en ny instans av klassen MathGroupingCharacter med standardgrupptecknet U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Bas elementet som strecket appliceras på |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Initierar en ny instans av klassen MathGroupingCharacter.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Bas elementet som strecket appliceras på |
| character | char | Grupperingssymbol |
| position | int | Position för grupptecken |
| verticalJustification | int | Vertikal justering av grupptecken |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Basargument

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Standardvärde för grupptecken: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Nedre parentes
> ```

**Returnerar:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Standardvärde för grupptecken: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setCharacter('\u23dd'); // Nedre parentes
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Position för grupptecken. Standard: Nederkant

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Returnerar:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Position för grupptecken. Standard: Nederkant

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```

Vertikal justering av grupptecken. Anger justeringen av objektet i förhållande till baslinjen. Till exempel, när grupptecknet är ovanför objektet, innebär VerticalJustification av Top att objektets topp ligger på baslinjen; när VerticalJustification är satt till Bottom, ligger objektets botten på baslinjen Default: Bottom for Position=Top, and Top for Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Returnerar:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```

Vertikal justering av grupptecken. Anger justeringen av objektet i förhållande till baslinjen. Till exempel, när grupptecknet är ovanför objektet, innebär VerticalJustification av Top att objektets topp ligger på baslinjen; när VerticalJustification är satt till Bottom, ligger objektets botten på baslinjen Default: Bottom for Position=Top, and Top for Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Hämta barn element

**Returnerar:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Egenskaper för kontrolltecken

**Returnerar:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps