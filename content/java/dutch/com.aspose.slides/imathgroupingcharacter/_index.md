---
title: IMathGroupingCharacter
second_title: Aspose.Slides voor Java API-referentie
description: Specificeert een groepssymbool boven of onder een expressie, meestal om de relatie tussen elementen te benadrukken
type: docs
url: /nl/com.aspose.slides/imathgroupingcharacter/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Specificeert een groepsymbool boven of onder een expressie, meestal om de relatie tussen elementen te benadrukken

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getCharacter()](#getCharacter--) | Standaardwaarde van groepskarakter: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Standaardwaarde van groepskarakter: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Positie van groepskarakter. |
| [setPosition(int value)](#setPosition-int-) | Positie van groepskarakter. |
| [getVerticalJustification()](#getVerticalJustification--) | Verticale uitlijning van groepskarakter. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Verticale uitlijning van groepskarakter. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


Standaardwaarde van groepskarakter: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Onderste haak
> ```

**Retour:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


Standaardwaarde van groepskarakter: U+23DF (BOTTOM CURLY BRACKET)

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
public abstract int getPosition()
```


Positie van groepskarakter. Standaard: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Retour:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Positie van groepskarakter. Standaard: Bottom

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
public abstract int getVerticalJustification()
```


Verticale uitlijning van groepskarakter. Bepaalt de uitlijning van het object ten opzichte van de baseline. Bijvoorbeeld, wanneer het groepskarakter boven het object staat, geeft VerticalJustification van Top aan dat de bovenkant van het object op de baseline valt; wanneer VerticalJustification is ingesteld op Bottom, ligt de onderkant van het object op de baseline. Standaard: Bottom voor Position=Top, en Top voor Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Retour:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```


Verticale uitlijning van groepskarakter. Bepaalt de uitlijning van het object ten opzichte van de baseline. Bijvoorbeeld, wanneer het groepskarakter boven het object staat, geeft VerticalJustification van Top aan dat de bovenkant van het object op de baseline valt; wanneer VerticalJustification is ingesteld op Bottom, ligt de onderkant van het object op de baseline. Standaard: Bottom voor Position=Top, en Top voor Position=Bottom

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