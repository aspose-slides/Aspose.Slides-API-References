---
title: IMathGroupingCharacter
second_title: Aspose.Slides för Android via Java API-referens
description: Specificerar en grupperingssymbol ovan eller under ett uttryck, vanligtvis för att framhäva relationen mellan element
type: docs
url: /sv/com.aspose.slides/imathgroupingcharacter/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Specificerar en grupperingssymbol ovan eller under ett uttryck, vanligtvis för att framhäva relationen mellan element

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Basargument |
| [getCharacter()](#getCharacter--) | Grouping Character standardvärde: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Grouping Character standardvärde: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Position för grupperingssymbolen. |
| [setPosition(int value)](#setPosition-int-) | Position för grupperingssymbolen. |
| [getVerticalJustification()](#getVerticalJustification--) | Vertikal justering av gruppsymbolen. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Vertikal justering av gruppsymbolen. |
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

Grouping Character standardvärde: U+23DF (BOTTOM CURLY BRACKET)

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

Grouping Character standardvärde: U+23DF (BOTTOM CURLY BRACKET)

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

Position för grupperingssymbolen. Standard: Bottom

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

Position för grupperingssymbolen. Standard: Bottom

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

Vertikal justering av gruppsymbolen. Anger justeringen av objektet i förhållande till baslinjen. Till exempel, när gruppsymbolen är ovanför objektet, VerticalJustification av Top betyder att objektets topp ligger på baslinjen; när VerticalJustification är satt till Bottom ligger objektets botten på baslinjen Standard: Bottom för Position=Top, och Top för Position=Bottom

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

Vertikal justering av gruppsymbolen. Anger justeringen av objektet i förhållande till baslinjen. Till exempel, när gruppsymbolen är ovanför objektet, VerticalJustification av Top betyder att objektets topp ligger på baslinjen; när VerticalJustification är satt till Bottom ligger objektets botten på baslinjen Standard: Bottom för Position=Top, och Top för Position=Bottom

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