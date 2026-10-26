---
title: IMathGroupingCharacter
second_title: Aspose.Slides für Java API-Referenz
description: Gibt ein Gruppensymbol über oder unter einem Ausdruck an, das normalerweise die Beziehung zwischen Elementen hervorhebt
type: docs
url: /de/com.aspose.slides/imathgroupingcharacter/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Gibt ein Gruppensymbol über oder unter einem Ausdruck an, meist um die Beziehung zwischen Elementen hervorzuheben

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getCharacter()](#getCharacter--) | Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Position of grouping character. |
| [setPosition(int value)](#setPosition-int-) | Position of grouping character. |
| [getVerticalJustification()](#getVerticalJustification--) | Vertical justification of group character. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Vertical justification of group character. |
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

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Gruppierungszeichen Standardwert: U+23DF (UNTERE KURLIGE KLAMMER)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Untere Klammer
> ```

**Rückgabe:** char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Gruppierungszeichen Standardwert: U+23DF (UNTERE KURLIGE KLAMMER)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Untere Klammer
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Position des Gruppierungszeichens. Standard: Unten

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Rückgabe:** int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Position des Gruppierungszeichens. Standard: Unten

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```

Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts relativ zur Grundlinie an. Zum Beispiel, wenn das Gruppierungszeichen über dem Objekt steht, bedeutet VerticalJustification of Top, dass die Oberseite des Objekts auf der Grundlinie liegt; wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterseite des Objekts auf der Grundlinie. Standard: Bottom für Position=Top und Top für Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Rückgabe:** int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts relativ zur Grundlinie an. Zum Beispiel, wenn das Gruppierungszeichen über dem Objekt steht, bedeutet VerticalJustification of Top, dass die Oberseite des Objekts auf der Grundlinie liegt; wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterseite des Objekts auf der Grundlinie. Standard: Bottom für Position=Top und Top für Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |