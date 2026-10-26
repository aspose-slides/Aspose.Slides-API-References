---
title: IMathGroupingCharacter
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert een groeperingssymbool boven of onder een expressie, meestal om de relatie tussen elementen te benadrukken
type: docs
url: /nl/com.aspose.slides/imathgroupingcharacter/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Specificeert een groeperingssymbool boven of onder een expressie, meestal om de relatie tussen elementen te benadrukken.

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
| [getCharacter()](#getCharacter--) | Groeperingskarakter Standaardwaarde: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Groeperingskarakter Standaardwaarde: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Positie van het groeperingskarakter. |
| [setPosition(int value)](#setPosition-int-) | Positie van het groeperingskarakter. |
| [getVerticalJustification()](#getVerticalJustification--) | Verticale uitlijning van het groepskarakter. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Verticale uitlijning van het groepskarakter. |
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


Groeperingskarakter Standaardwaarde: U+23DF (BOTTOM CURLY BRACKET)

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
public abstract int getPosition()
```


Positie van het groeperingskarakter. Standaard: Bottom

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


Positie van het groeperingskarakter. Standaard: Bottom

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


Verticale uitlijning van het groepskarakter. Bepaalt de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groepskarakter boven het object staat, geeft VerticalJustification van Top aan dat de bovenkant van het object op de basislijn valt; wanneer VerticalJustification is ingesteld op Bottom, bevindt de onderkant van het object zich op de basislijn. Standaard: Bottom voor Position=Top, en Top voor Position=Bottom

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


Verticale uitlijning van het groepskarakter. Bepaalt de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groepskarakter boven het object staat, geeft VerticalJustification van Top aan dat de bovenkant van het object op de basislijn valt; wanneer VerticalJustification is ingesteld op Bottom, bevindt de onderkant van het object zich op de basislijn. Standaard: Bottom voor Position=Top, en Top voor Position=Bottom

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