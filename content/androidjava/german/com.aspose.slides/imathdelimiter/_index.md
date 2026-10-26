---
title: IMathDelimiter
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Gibt das Trennzeichenobjekt an, das aus öffnenden und schließenden Zeichen wie Klammern, geschweiften Klammern, eckigen Klammern und senkrechten Strichen besteht und ein oder mehrere mathematische Elemente darin enthält, die durch ein angegebenes Zeichen getrennt sind.
type: docs
url: /de/com.aspose.slides/imathdelimiter/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Gibt das Trennzeichenobjekt an, das aus öffnenden und schließenden Zeichen besteht (wie Klammern, geschweifte Klammern, eckige Klammern und senkrechte Striche) und ein oder mehrere mathematische Elemente darin, getrennt durch ein angegebenes Zeichen. Beispiele: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getArguments()](#getArguments--) | Ein oder mehrere mathematische Elemente, getrennt durch Trennzeichen |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character gibt das Anfangs- bzw. öffnende Trennzeichen an. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character gibt das Anfangs- bzw. öffnende Trennzeichen an. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character gibt das Zeichen an, das Argumente im Trennzeichenobjekt trennt. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character gibt das Zeichen an, das Argumente im Trennzeichenobjekt trennt. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character gibt das End- bzw. schließende Trennzeichen an. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character gibt das End- bzw. schließende Trennzeichen an. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Gibt das Wachstum von BeginningCharacter, SeparatorCharacter, EndingCharacter an. Wenn true, wachsen die Trennzeichen vertikal, um die Höhe ihres Operanden anzupassen. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Gibt das Wachstum von BeginningCharacter, SeparatorCharacter, EndingCharacter an. Wenn true, wachsen die Trennzeichen vertikal, um die Höhe ihres Operanden anzupassen. |
| [getDelimiterShape()](#getDelimiterShape--) | Gibt die Form der Trennzeichen im Trennzeichenobjekt an. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Gibt die Form der Trennzeichen im Trennzeichenobjekt an. |
| [delimit(char separatorCharacter)](#delimit-char-) | Trennt Argumente mit dem angegebenen Trennzeichenzeichen |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Ein oder mehrere mathematische Elemente, getrennt durch Trennzeichen

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
public abstract char getBeginningCharacter()
```

Delimiter Beginning Character gibt das Anfangs- bzw. öffnende Trennzeichen an. Mathematische Trennzeichen sind einschließende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Der Standardwert: '('.

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
public abstract void setBeginningCharacter(char value)
```

Delimiter Beginning Character gibt das Anfangs- bzw. öffnende Trennzeichen an. Mathematische Trennzeichen sind einschließende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Der Standardwert: '('.

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
public abstract char getSeparatorCharacter()
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
public abstract void setSeparatorCharacter(char value)
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
public abstract char getEndingCharacter()
```

Delimiter Ending Character gibt das End- bzw. schließende Trennzeichen an. Mathematische Trennzeichen sind einschließende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Der Standardwert: ')'.

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
public abstract void setEndingCharacter(char value)
```

Delimiter Ending Character gibt das End- bzw. schließende Trennzeichen an. Mathematische Trennzeichen sind einschließende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Der Standardwert: ')'.

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
public abstract boolean getGrowToMatchOperandHeight()
```

Gibt das Wachstum von BeginningCharacter, SeparatorCharacter, EndingCharacter an. Wenn true, wachsen die Trennzeichen vertikal, um die Höhe ihres Operanden anzupassen. Der Standardwert ist true

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
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Gibt das Wachstum von BeginningCharacter, SeparatorCharacter, EndingCharacter an. Wenn true, wachsen die Trennzeichen vertikal, um die Höhe ihres Operanden anzupassen. Der Standardwert ist true

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
public abstract int getDelimiterShape()
```

Gibt die Form der Trennzeichen im Trennzeichenobjekt an. Wenn MathDelimiterShape.Centered, sind die Trennzeichen um die mathematische Achse des Textes zentriert und passen sich dennoch der Gesamthöhe ihres Inhalts an. Wenn MathDelimiterShape.Match, werden Höhe und Form exakt an den Inhalt angepasst.

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
public abstract void setDelimiterShape(int value)
```

Gibt die Form der Trennzeichen im Trennzeichenobjekt an. Wenn MathDelimiterShape.Centered, sind die Trennzeichen um die mathematische Achse des Textes zentriert und passen sich dennoch der Gesamthöhe ihres Inhalts an. Wenn MathDelimiterShape.Match, werden Höhe und Form exakt an den Inhalt angepasst.

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
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Trennt Argumente mit dem angegebenen Trennzeichenzeichen

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separatorCharacter | char | Trennzeichen |

**Rückgabewert:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Dieses Objekt nach Anwendung des Trennzeichenzeichens