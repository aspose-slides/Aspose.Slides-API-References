---
title: MathGroupingCharacter
second_title: Aspose.Slides voor Java API-referentie
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
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Initialiseert een nieuw exemplaar van de MathGroupingCharacter-klasse met het standaard groeperingskarakter U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Initialiseert een nieuw exemplaar van de MathGroupingCharacter-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getCharacter()](#getCharacter--) | Groeperingskarakter Standaardwaarde: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Groeperingskarakter Standaardwaarde: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Positie van groeperingskarakter. |
| [setPosition(int value)](#setPosition-int-) | Positie van groeperingskarakter. |
| [getVerticalJustification()](#getVerticalJustification--) | Verticale uitlijning van het groepteken. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Verticale uitlijning van het groepteken. |
| [getChildren()](#getChildren--) | Haal onderliggende elementen op |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

Initialiseert een nieuw exemplaar van de MathGroupingCharacter-klasse met het standaard groeperingskarakter U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Het basiselement waarop de balk wordt toegepast |
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Het basiselement waarop de balk wordt toegepast |
| character | char | Groeperingskarakter |
| position | int | Positie van groeperingskarakter |
| verticalJustification | int | Verticale uitlijning van het groepteken |
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

**Retourwaarde:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Groeperingskarakter Standaardwaarde: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Onderste haak
> ```

**Retourwaarde:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Groeperingskarakter Standaardwaarde: U+23DF (BOTTOM CURLY BRACKET)

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

Positie van groeperingskarakter. Standaard: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Retourwaarde:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Positie van groeperingskarakter. Standaard: Bottom

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

Verticale uitlijning van het groepteken. Specificeert de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groepteken boven het object staat, geeft VerticalJustification van Top aan dat de bovenkant van het object op de basislijn valt; wanneer VerticalJustification is ingesteld op Bottom, staat de onderkant van het object op de basislijn. Standaard: Bottom voor Position=Top, en Top voor Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Retourwaarde:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```

Verticale uitlijning van het groepteken. Specificeert de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groepteken boven het object staat, geeft VerticalJustification van Top aan dat de bovenkant van het object op de basislijn valt; wanneer VerticalJustification is ingesteld op Bottom, staat de onderkant van het object op de basislijn. Standaard: Bottom voor Position=Top, en Top voor Position=Bottom

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

Haal onderliggende elementen op

**Retourwaarde:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**Retourwaarde:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps