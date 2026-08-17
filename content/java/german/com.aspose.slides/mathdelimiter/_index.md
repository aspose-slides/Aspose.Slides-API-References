---
title: MathDelimiter
second_title: Aspose.Slides für Java API Referenz
description: Gibt das Trennzeichenobjekt an, das aus öffnenden und schließenden Zeichen wie Klammern, geschweiften Klammern, eckigen Klammern und senkrechten Strichen besteht und ein oder mehrere mathematische Elemente darin enthält, die durch ein angegebenes Zeichen getrennt sind.
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

Gibt das Trennzeichenobjekt an, das aus öffnenden und schließenden Zeichen (wie Klammern, geschweiften Klammern, eckigen Klammern und senkrechten Strichen) besteht und ein oder mehrere mathematische Elemente darin enthält, die durch ein angegebenes Zeichen getrennt sind. Beispiele: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Initialisiert MathDelimiter mit dem angegebenen Element als einzelnes Basiselement |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getArguments()](#getArguments--) | Ein oder mehrere mathematische Elemente, getrennt durch Trennzeichenzeichen |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character gibt das Anfangszeichen, bzw. das öffnende Trennzeichen an. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character gibt das Anfangszeichen, bzw. das öffnende Trennzeichen an. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character gibt das Zeichen an, das Argumente im Trennzeichenobjekt trennt. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character gibt das Zeichen an, das Argumente im Trennzeichenobjekt trennt. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character gibt das Endzeichen, bzw. das schließende Trennzeichen an. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character gibt das Endzeichen, bzw. das schließende Trennzeichen an. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Gibt an, dass BeginningCharacter, SeparatorCharacter und EndingCharacter wachsen. Wenn true, wachsen die Trennzeichen vertikal, um die Höhe ihres Operanden anzupassen. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Gibt an, dass BeginningCharacter, SeparatorCharacter und EndingCharacter wachsen. Wenn true, wachsen die Trennzeichen vertikal, um die Höhe ihres Operanden anzupassen. |
| [getDelimiterShape()](#getDelimiterShape--) | Gibt die Form der Trennzeichen im Trennzeichenobjekt an. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Gibt die Form der Trennzeichen im Trennzeichenobjekt an. |
| [delimit(char separatorCharacter)](#delimit-char-) | Grenzt Argumente mit dem angegebenen Trennzeichen ab. |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Umfasst ein Math-Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen. |
| [getChildren()](#getChildren--) | Liefert Kindelemente |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Initialisiert MathDelimiter mit dem angegebenen Element als einzelnes Basiselement

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

Ein oder mehrere mathematische Elemente, getrennt durch Trennzeichenzeichen

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

Delimiter Beginning Character gibt das Anfangszeichen, bzw. das öffnende Trennzeichen an. Mathematische Trennzeichen sind umschließende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Der Standardwert: '('.

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

Delimiter Beginning Character gibt das Anfangszeichen, bzw. das öffnende Trennzeichen an. Mathematische Trennzeichen sind umschließende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Der Standardwert: '('.

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

Delimiter Separator Character gibt das Zeichen an, das Argumente im Trennzeichenobjekt trennt. Der Standardwert: '|'.

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

Delimiter Separator Character gibt das Zeichen an, das Argumente im Trennzeichenobjekt trennt. Der Standardwert: '|'.

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

Delimiter Ending Character gibt das Endzeichen, bzw. das schließende Trennzeichen an. Mathematische Trennzeichen sind umschließende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Der Standardwert: ')'.

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

Delimiter Ending Character gibt das Endzeichen, bzw. das schließende Trennzeichen an. Mathematische Trennzeichen sind umschließende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Der Standardwert: ')'.

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

Gibt an, dass BeginningCharacter, SeparatorCharacter und EndingCharacter wachsen. Wenn true, wachsen die Trennzeichen vertikal, um die Höhe ihres Operanden anzupassen. Der Standardwert ist true

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

Gibt an, dass BeginningCharacter, SeparatorCharacter und EndingCharacter wachsen. Wenn true, wachsen die Trennzeichen vertikal, um die Höhe ihres Operanden anzupassen. Der Standardwert ist true

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

Gibt die Form der Trennzeichen im Trennzeichenobjekt an. Wenn MathDelimiterShape.Centered, sind die Trennzeichen um die mathematische Achse des Textes zentriert und passen sich an die gesamte Höhe ihres Inhalts an. Wenn MathDelimiterShape.Match, werden Höhe und Form exakt an den Inhalt angepasst.

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

Gibt die Form der Trennzeichen im Trennzeichenobjekt an. Wenn MathDelimiterShape.Centered, sind die Trennzeichen um die mathematische Achse des Textes zentriert und passen sich an die gesamte Höhe ihres Inhalts an. Wenn MathDelimiterShape.Match, werden Höhe und Form exakt an den Inhalt angepasst.

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

Grenzt Argumente mit dem angegebenen Trennzeichen ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separatorCharacter | char | Trennzeichenzeichen |

**Rückgabewert:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Dieses Objekt nach dem Anwenden des Trennzeichens
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Umfasst ein Math-Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen

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
| beginningCharacter | char | Anfangszeichen (gewöhnlich linke Klammer) |
| endingCharacter | char | Endzeichen (gewöhnlich rechte Klammer) |

**Rückgabewert:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Wenn beginningCharacter und endingCharacter null sind, werden die entsprechenden Eigenschaften nur gesetzt und es wird kein neues Objekt erstellt (gibt diese Instanz zurück). Andernfalls wird ein neues Math-Element vom Typ Delimiter zurückgegeben, das die angegebenen Zeichen als Rahmen enthält und diese Instanz von [MathDelimiter](../../com.aspose.slides/mathdelimiter) darin eingeschlossen ist.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Liefert Kindelemente

**Rückgabewert:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**Rückgabewert:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps