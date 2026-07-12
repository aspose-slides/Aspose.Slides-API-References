---
title: IMathBox
second_title: Aspose.Slides für Android über Java API-Referenz
description: Gibt die logische Verpackung (Boxing) eines mathematischen Elements an.
type: docs
url: /de/com.aspose.slides/imathbox/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Gibt die logische Kapselung (Verpackung) eines mathematischen Elements an. Zum Beispiel kann ein gekapseltes Objekt als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass Zeilenumbrüche innerhalb verhindert werden. Zum Beispiel sollte der Operator “==” gekapselt werden, um Zeilenumbrüche zu verhindern.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator-Emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator-Emulator. |
| [getNoBreak()](#getNoBreak--) | Kein Umbruch. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Kein Umbruch. |
| [getDifferential()](#getDifferential--) | Differential. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Wenn true, dient dieser Operator-Emulator als Ausrichtungspunkt; das heißt, festgelegte Ausrichtungspunkte in anderen Gleichungen können mit ihm ausgerichtet werden. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Wenn true, dient dieser Operator-Emulator als Ausrichtungspunkt; das heißt, festgelegte Ausrichtungspunkte in anderen Gleichungen können mit ihm ausgerichtet werden. |
| [getExplicitBreak()](#getExplicitBreak--) | Expliziter Umbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch erfolgt, sodass die Zeile am Anfang des Box-Objekts umbricht. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Expliziter Umbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch erfolgt, sodass die Zeile am Anfang des Box-Objekts umbricht. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Basisargument

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Operator-Emulator. Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Punkt für einen Zeilenumbruch dienen und zu anderen Operatoren ausgerichtet werden kann. Operator-Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, wie z. B. '=='. Standardwert: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Rückgabe:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Operator-Emulator. Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Punkt für einen Zeilenbruch dienen und zu anderen Operatoren ausgerichtet werden kann. Operator-Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, wie z. B. '=='. Standardwert: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

Kein Umbruch. Diese Eigenschaft gibt die „unbreakable“-Eigenschaft des Objekt-Box an. Wenn true, können innerhalb der Box keine Zeilenumbrüche auftreten. Dies kann bei Operator-Emulatoren wichtig sein, die aus mehr als einem binären Operator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb der Box Umbrüche auftreten. Standardwert: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Rückgabe:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Kein Umbruch. Diese Eigenschaft gibt die „unbreakable“-Eigenschaft des Objekt-Box an. Wenn true, können innerhalb der Box keine Zeilenumbrüche auftreten. Dies kann bei Operator-Emulatoren wichtig sein, die aus mehr als einem binären Operator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb der Box Umbrüche auftreten. Standardwert: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

Differential. Wenn true, fungiert die Box als Differential (z. B. \\ud835\\udc51\\ud835\\udc65 in einem Integranden) und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. Standardwert: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Rückgabe:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

Differential. Wenn true, fungiert die Box als Differential (z. B. \\ud835\\udc51\\ud835\\udc65 in einem Integranden) und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. Standardwert: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

Wenn true, dient dieser Operator-Emulator als Ausrichtungspunkt; das heißt, festgelegte Ausrichtungspunkte in anderen Gleichungen können mit ihm ausgerichtet werden. Standardwert: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Rückgabe:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

Wenn true, dient dieser Operator-Emulator als Ausrichtungspunkt; das heißt, festgelegte Ausrichtungspunkte in anderen Gleichungen können mit ihm ausgerichtet werden. Standardwert: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

Expliziter Umbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch erfolgt, sodass die Zeile am Anfang des Box-Objekts umbricht. Gibt die Nummer des Operators in der vorherigen Zeile des mathematischen Textes an, der als Ausrichtungspunkt für die aktuelle Zeile des mathematischen Textes verwendet werden soll. Mögliche Werte: 1..255 Standardwert: 0 (kein expliziter Umbruch)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Rückgabe:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

Expliziter Umbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch erfolgt, sodass die Zeile am Anfang des Box-Objekts umbricht. Gibt die Nummer des Operators in der vorherigen Zeile des mathematischen Textes an, der als Ausrichtungspunkt für die aktuelle Zeile des mathematischen Textes verwendet werden soll. Mögliche Werte: 1..255 Standardwert: 0 (kein expliziter Umbruch)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |