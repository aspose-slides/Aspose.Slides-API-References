---
title: IMathGroupingCharacter
second_title: Aspose.Slides för Java API-referens
description: Anger en grupperingstext ovan eller nedanför ett uttryck, vanligtvis för att belysa relationen mellan element
type: docs
url: /sv/com.aspose.slides/imathgroupingcharacter/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Anger en grupperingstext ovan eller nedanför ett uttryck, vanligtvis för att belysa relationen mellan element

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
>  ```

## Methods

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Basargument |
| [getCharacter()](#getCharacter--) | Grupperingstecken Standardvärde: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Grupperingstecken Standardvärde: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Placering av grupperingstecken. |
| [setPosition(int value)](#setPosition-int-) | Placering av grupperingstecken. |
| [getVerticalJustification()](#getVerticalJustification--) | Vertikal justering av grupperingstecken. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Vertikal justering av grupperingstecken. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
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
public abstract char getCharacter()
```


Grupperingstecken Standardvärde: U+23DF (BOTTOM CURLY BRACKET)

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
public abstract void setCharacter(char value)
```


Grupperingstecken Standardvärde: U+23DF (BOTTOM CURLY BRACKET)

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
public abstract int getPosition()
```


Placering av grupperingstecken. Standard: Bottom

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
public abstract void setPosition(int value)
```


Placering av grupperingstecken. Standard: Bottom

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
public abstract int getVerticalJustification()
```


Vertikal justering av grupperingstecken. Anger objektets justering i förhållande till baslinjen. Till exempel, när grupperingstecknet är ovanför objektet, betyder VerticalJustification av Top att objektets topp ligger på baslinjen; när VerticalJustification är satt till Bottom ligger objektets botten på baslinjen. Standard: Bottom för Position=Top, och Top för Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Returnerar:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```


Vertikal justering av grupperingstecken. Anger objektets justering i förhållande till baslinjen. Till exempel, när grupperingstecknet är ovanför objektet, betyder VerticalJustification av Top att objektets topp ligger på baslinjen; när VerticalJustification är satt till Bottom ligger objektets botten på baslinjen. Standard: Bottom för Position=Top, och Top för Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |