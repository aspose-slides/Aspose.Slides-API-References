---
title: MathGroupingCharacter
second_title: Aspose.Slides för Java API-referens
description: Anger en grupperingssymbol ovanför eller under ett uttryck, vanligtvis för att framhäva relationen mellan element
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

Anger en grupperingssymbol ovanför eller under ett uttryck, vanligtvis för att framhäva relationen mellan element

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Initierar en ny instans av MathGroupingCharacter-klassen med standardgrupperingssymbolen U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Initierar en ny instans av MathGroupingCharacter-klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Basargument |
| [getCharacter()](#getCharacter--) | Grouping Character Standardvärde: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Grouping Character Standardvärde: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Position för grupperingssymbolen. |
| [setPosition(int value)](#setPosition-int-) | Position för grupperingssymbolen. |
| [getVerticalJustification()](#getVerticalJustification--) | Vertikal justering av grupperingssymbolen. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Vertikal justering av grupperingssymbolen. |
| [getChildren()](#getChildren--) | Hämta underordnade element |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```


Initierar en ny instans av MathGroupingCharacter-klassen med standardgrupperingssymbolen U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Det baselement som stapeln tillämpas på |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Initierar en ny instans av MathGroupingCharacter-klassen.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Det baselement som stapeln tillämpas på |
| character | char | Grouping Character |
| position | int | Position för grupperingssymbolen |
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


Grouping Character Standardvärde: U+23DF (BOTTOM CURLY BRACKET)

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


Grouping Character Standardvärde: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Nedre parentes
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


Position för grupptecken. Standard: Bottom

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


Position för grupptecken. Standard: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```


Vertikal justering av grupptecken. Anger objektets inriktning i förhållande till referenslinjen. Till exempel, när grupptecknet är ovanför objektet innebär VertikalJustering Top att objektets topp ligger på referenslinjen; när VertikalJustering är satt till Bottom ligger objektets botten på referenslinjen. Standard: Bottom för Position=Top och Top för Position=Bottom

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


Vertikal justering av grupptecken. Anger objektets inriktning i förhållande till referenslinjen. Till exempel, när grupptecknet är ovanför objektet innebär VertikalJustering Top att objektets topp ligger på referenslinjen; när VertikalJustering är satt till Bottom ligger objektets botten på referenslinjen. Standard: Bottom för Position=Top och Top för Position=Bottom

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


Hämta underordnade element

**Returnerar:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Control Character Properties

**Returnerar:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps