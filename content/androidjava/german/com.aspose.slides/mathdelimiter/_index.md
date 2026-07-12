---
title: MathDelimiter
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Gibt das Trennzeichen-Objekt an, das aus öffnenden und schließenden Zeichen wie Klammern, geschweiften Klammern, eckigen Klammern und senkrechten Strichen besteht und ein oder mehrere mathematische Elemente enthält, die durch ein angegebenes Zeichen getrennt sind.
type: docs
url: /de/com.aspose.slides/mathdelimiter/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Beschreibt das Trennzeichen-Objekt, das aus öffnenden und schließenden Zeichen (wie Klammern, geschweiften Klammern, eckigen Klammern und senkrechten Strichen) besteht und ein oder mehrere mathematische Elemente enthält, die durch ein angegebenes Zeichen getrennt sind. Beispiele: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Initialisiert MathDelimiter mit dem angegebenen Element als einziges Basiselement |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getArguments()](#getArguments--) | Ein oder mehrere mathematische Elemente, die durch Trennzeichenzeichen getrennt sind |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character gibt das Anfangs- oder Öffnungszeichen des Trennzeichens an. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character gibt das Anfangs- oder Öffnungszeichen des Trennzeichens an. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character gibt das Zeichen an, das Argumente im Trennzeichen-Objekt trennt. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character gibt das Zeichen an, das Argumente im Trennzeichen-Objekt trennt. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character gibt das End- oder Schließzeichen des Trennzeichens an. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character gibt das End- oder Schließzeichen des Trennzeichens an. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Gibt an, ob BeginningCharacter, SeparatorCharacter und EndingCharacter wachsen sollen. Wenn wahr, wächst das Trennzeichen vertikal, um die Höhe seiner Operanden anzupassen. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Gibt an, ob BeginningCharacter, SeparatorCharacter und EndingCharacter wachsen sollen. Wenn wahr, wächst das Trennzeichen vertikal, um die Höhe seiner Operanden anzupassen. |
| [getDelimiterShape()](#getDelimiterShape--) | Gibt die Form der Trennzeichen im Trennzeichen-Objekt an. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Gibt die Form der Trennzeichen im Trennzeichen-Objekt an. |
| [delimit(char separatorCharacter)](#delimit-char-) | Begrenzt Argumente mit dem angegebenen Trennzeichenzeichen. |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Schliesst ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen ein. |
| [getChildren()](#getChildren--) | Liefert die Kind-Elemente. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Eigenschaften des Steuerzeichens. |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Initialisiert MathDelimiter mit dem angegebenen Element als einziges Basiselement

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Das Basiselement, auf das das Trennzeichen angewendet wird. Kann null sein. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Ein oder mehrere mathematische Elemente, die durch Trennzeichenzeichen getrennt sind

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Rückgabewert:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

Delimiter Beginning Character gibt das Anfangs- bzw. Öffnungszeichen des Trennzeichens an. Mathematische Trennzeichen sind umgebende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Standard: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Rückgabewert:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

Delimiter Beginning Character gibt das Anfangs- bzw. Öffnungszeichen des Trennzeichens an. Mathematische Trennzeichen sind umgebende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Standard: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```

Delimiter Separator Character gibt das Zeichen an, das Argumente im Trennzeichen-Objekt trennt. Standard: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Rückgabewert:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

Delimiter Separator Character gibt das Zeichen an, das Argumente im Trennzeichen-Objekt trennt. Standard: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char |  |
### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```

Delimiter Ending Character gibt das End- bzw. Schließzeichen des Trennzeichens an. Mathematische Trennzeichen sind umgebende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Standard: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Rückgabewert:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

Delimiter Ending Character gibt das End- bzw. Schließzeichen des Trennzeichens an. Mathematische Trennzeichen sind umgebende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Standard: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char |  |
### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Gibt an, ob BeginningCharacter, SeparatorCharacter und EndingCharacter wachsen sollen. Wenn wahr, wächst das Trennzeichen vertikal, um die Höhe seiner Operanden anzupassen. Der Standardwert ist true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Rückgabewert:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Gibt an, ob BeginningCharacter, SeparatorCharacter und EndingCharacter wachsen sollen. Wenn wahr, wächst das Trennzeichen vertikal, um die Höhe seiner Operanden anzupassen. Der Standardwert ist true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```

Gibt die Form der Trennzeichen im Trennzeichen-Objekt an. Wenn MathDelimiterShape.Centered, sind die Trennzeichen um die mathematische Achse des mathematischen Textes zentriert und passen sich an die gesamte Höhe ihres Inhalts an. Wenn MathDelimiterShape.Match, werden Höhe und Form exakt an den Inhalt angepasst.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Rückgabewert:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

Gibt die Form der Trennzeichen im Trennzeichen-Objekt an. Wenn MathDelimiterShape.Centered, sind die Trennzeichen um die mathematische Achse des mathematischen Textes zentriert und passen sich an die gesamte Höhe ihres Inhalts an. Wenn MathDelimiterShape.Match, werden Höhe und Form exakt an den Inhalt angepasst.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Begrenzt Argumente mit dem angegebenen Trennzeichenzeichen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separatorCharacter | char | Trennzeichen |

**Rückgabewert:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Dieses Objekt nach Anwendung des Trennzeichenzeichens
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Schliesst ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen ein

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginningCharacter | char | Anfangszeichen (üblicherweise linke Klammer) |
| endingCharacter | char | Endzeichen (üblicherweise rechte Klammer) |

**Rückgabewert:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Wenn beginningCharacter und endingCharacter null sind, werden nur die zugehörigen Eigenschaften gesetzt und kein neues Objekt erstellt (gibt diese Instanz zurück). Andernfalls wird ein neues mathematisches Element vom Typ Delimiter zurückgegeben, das die angegebenen Zeichen als Rahmen enthält und diese Instanz von [MathDelimiter](../../com.aspose.slides/mathdelimiter) darin einrahmt.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Liefert die Kind-Elemente.

**Rückgabewert:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Eigenschaften des Steuerzeichens.

**Rückgabewert:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps