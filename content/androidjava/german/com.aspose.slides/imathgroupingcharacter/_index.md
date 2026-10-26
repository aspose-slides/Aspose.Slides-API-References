---
title: IMathGroupingCharacter
second_title: Aspose.Slides für Android über die Java API Referenz
description: Gibt ein Gruppierungssymbol über oder unter einem Ausdruck an, das in der Regel die Beziehung zwischen Elementen hervorhebt.
type: docs
url: /de/com.aspose.slides/imathgroupingcharacter/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Gibt ein Gruppierungssymbol über oder unter einem Ausdruck an, das in der Regel die Beziehung zwischen Elementen hervorhebt.

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getCharacter()](#getCharacter--) | Gruppierungszeichen Standardwert: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Gruppierungszeichen Standardwert: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Position des Gruppierungszeichens. |
| [setPosition(int value)](#setPosition-int-) | Position des Gruppierungszeichens. |
| [getVerticalJustification()](#getVerticalJustification--) | Vertikale Ausrichtung des Gruppierungszeichens. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Vertikale Ausrichtung des Gruppierungszeichens. |
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

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Gruppierungszeichen Standardwert: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Untere Klammer
> ```

**Rückgabewert:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Gruppierungszeichen Standardwert: U+23DF (BOTTOM CURLY BRACKET)

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

Position des Gruppierungszeichens. Standard: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Rückgabewert:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Position des Gruppierungszeichens. Standard: Bottom

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

Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts in Bezug auf die Grundlinie an. Zum Beispiel bedeutet VerticalJustification von Top, dass die Oberseite des Objekts auf der Grundlinie liegt, wenn das Gruppierungszeichen über dem Objekt ist; wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterseite des Objekts auf der Grundlinie. Standard: Bottom für Position=Top und Top für Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Rückgabewert:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts in Bezug auf die Grundlinie an. Zum Beispiel bedeutet VerticalJustification von Top, dass die Oberseite des Objekts auf der Grundlinie liegt, wenn das Gruppierungszeichen über dem Objekt ist; wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterseite des Objekts auf der Grundlinie. Standard: Bottom für Position=Top und Top für Position=Bottom

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