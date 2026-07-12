---
title: MathGroupingCharacter
second_title: Aspose.Slides für Android über die Java API Referenz
description: Gibt ein Gruppierungssymbol über oder unter einem Ausdruck an, das normalerweise die Beziehung zwischen den Elementen hervorhebt
type: docs
url: /de/com.aspose.slides/mathgroupingcharacter/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

Gibt ein Gruppierungssymbol über oder unter einem Ausdruck an, das normalerweise die Beziehung zwischen den Elementen hervorhebt.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Erstellt eine neue Instanz der MathGroupingCharacter-Klasse mit dem Standardgruppierungszeichen U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Erstellt eine neue Instanz der MathGroupingCharacter-Klasse. |
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
| [getChildren()](#getChildren--) | Gibt Kindelemente zurück |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Steuerzeichen-Eigenschaften |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```


Erstellt eine neue Instanz der MathGroupingCharacter-Klasse mit dem Standardgruppierungszeichen U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Das Basiselement, auf das der Balken angewendet wird |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Erstellt eine neue Instanz der MathGroupingCharacter-Klasse.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Das Basiselement, auf das der Balken angewendet wird |
| character | char | Gruppierungszeichen |
| position | int | Position des Gruppierungszeichens |
| verticalJustification | int | Vertikale Ausrichtung des Gruppierungszeichens |

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

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
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
public final void setCharacter(char value)
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
public final int getPosition()
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
public final void setPosition(int value)
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
public final int getVerticalJustification()
```


Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts relativ zur Grundlinie an. Beispiel: Wenn das Gruppierungszeichen über dem Objekt liegt, bedeutet VerticalJustification von Top, dass die Oberseite des Objekts auf der Grundlinie liegt; wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterseite des Objekts auf der Grundlinie. Standard: Bottom für Position=Top und Top für Position=Bottom

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
public final void setVerticalJustification(int value)
```


Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts relativ zur Grundlinie an. Beispiel: Wenn das Gruppierungszeichen über dem Objekt liegt, bedeutet VerticalJustification von Top, dass die Oberseite des Objekts auf der Grundlinie liegt; wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterseite des Objekts auf der Grundlinie. Standard: Bottom für Position=Top und Top für Position=Bottom

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Gibt Kindelemente zurück

**Rückgabewert:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Steuerzeichen-Eigenschaften

**Rückgabewert:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps