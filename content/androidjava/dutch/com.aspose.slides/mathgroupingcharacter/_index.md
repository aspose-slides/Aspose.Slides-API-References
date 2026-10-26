---
title: MathGroupingCharacter
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert een groepssymbool boven of onder een expressie, meestal om de relatie tussen elementen te benadrukken
type: docs
url: /nl/com.aspose.slides/mathgroupingcharacter/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

Specificeert een groepsymbool boven of onder een expressie, meestal om de relatie tussen elementen te benadrukken

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Initialiseert een nieuw exemplaar van de MathGroupingCharacter-klasse met het standaard groepsymbool U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Initialiseert een nieuw exemplaar van de MathGroupingCharacter-klasse. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getCharacter()](#getCharacter--) | Groepsteken Standaardwaarde: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Groepsteken Standaardwaarde: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Positie van groepsymbool. |
| [setPosition(int value)](#setPosition-int-) | Positie van groepsymbool. |
| [getVerticalJustification()](#getVerticalJustification--) | Verticale uitlijning van groepsymbool. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Verticale uitlijning van groepsymbool. |
| [getChildren()](#getChildren--) | Haal kindelementen op |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Controle-teken-eigenschappen |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```


Initialiseert een nieuw exemplaar van de MathGroupingCharacter-klasse met het standaard groepsymbool U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Het basiselement waaraan de balk wordt toegepast |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Initialiseert een nieuw exemplaar van de MathGroupingCharacter-klasse.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Het basiselement waaraan de balk wordt toegepast |
| character | char | Groepsteken |
| position | int | Positie van groepsymbool |
| verticalJustification | int | Verticale uitlijning van groepsymbool |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Groepsteken Standaardwaarde: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Onderste haak
> ```

**Returns:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```


Groepsteken Standaardwaarde: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Onderste haak
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


Positie van groepsymbool. Standaard: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Positie van groepsymbool. Standaard: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```


Verticale uitlijning van groepsymbool. Geeft de uitlijning van het object ten opzichte van de basislijn aan. Bijvoorbeeld, wanneer het groepsymbool boven het object staat, betekent VerticalJustification = Top dat de bovenkant van het object op de basislijn ligt; wanneer VerticalJustification op Bottom staat, ligt de onderkant van het object op de basislijn. Standaard: Bottom voor Position=Top, en Top voor Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Returns:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```


Verticale uitlijning van groepsymbool. Geeft de uitlijning van het object ten opzichte van de basislijn aan. Bijvoorbeeld, wanneer het groepsymbool boven het object staat, betekent VerticalJustification = Top dat de bovenkant van het object op de basislijn ligt; wanneer VerticalJustification op Bottom staat, ligt de onderkant van het object op de basislijn. Standaard: Bottom voor Position=Top, en Top voor Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Haal kindelementen op

**Returns:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Controle-teken-eigenschappen

**Returns:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps