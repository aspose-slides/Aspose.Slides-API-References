---
title: IMathBox
second_title: Aspose.Slides für Java API Referenz
description: Gibt die logische Box-Verpackung eines mathematischen Elements an.
type: docs
url: /de/com.aspose.slides/imathbox/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Gibt die logische Box (Verpackung) eines mathematischen Elements an. Zum Beispiel kann ein eingeschachteltes Objekt als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt dienen oder gruppiert werden, sodass innerhalb keine Zeilenumbrüche erlaubt sind. Zum Beispiel sollte der Operator „==“ in eine Box eingeschlossen werden, um Zeilenumbrüche zu verhindern.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator Emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator Emulator. |
| [getNoBreak()](#getNoBreak--) | No break. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | No break. |
| [getDifferential()](#getDifferential--) | Differential. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential. |
| [getAlignmentPoint()](#getAlignmentPoint--) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
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

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```


Operator-Emulator. Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und übernehmen die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Zeilenumbruchpunkt dienen und an andere Operatoren ausgerichtet werden kann. Operator-Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, z. B. „==“. Standardwert: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```


**Rückgabewert:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```


Operator-Emulator. Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und übernehmen die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Zeilenumbruchpunkt dienen und an andere Operatoren ausgerichtet werden kann. Operator-Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, z. B. „==“. Standardwert: false

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


Kein Zeilenumbruch. Diese Eigenschaft gibt die „unbreakable“-Eigenschaft des Objekt-Box an. Wenn true, können innerhalb der Box keine Zeilenumbrüche auftreten. Dies kann für Operator-Emulatoren wichtig sein, die aus mehr als einem binären Operator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb der Box Zeilenumbrüche auftreten. Standard: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Rückgabewert:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```


Kein Zeilenumbruch. Diese Eigenschaft gibt die „unbreakable“-Eigenschaft des Objekt-Box an. Wenn true, können innerhalb der Box keine Zeilenumbrüche auftreten. Dies kann für Operator-Emulatoren wichtig sein, die aus mehr als einem binären Operator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb der Box Zeilenumbrüche auftreten. Standard: true

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


Differential. Wenn true, fungiert die Box als Differential (z. B. \\ud835\\udc51\\ud835\\udc65 in einem Integranden) und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. Standard: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Rückgabewert:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```


Differential. Wenn true, fungiert die Box als Differential (z. B. \\ud835\\udc51\\ud835\\udc65 in einem Integranden) und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. Standard: false

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


Wenn true, dient dieser Operator-Emulator als Ausrichtungspunkt; das heißt, bezeichnete Ausrichtungspunkte in anderen Gleichungen können mit ihm ausgerichtet werden. Standard: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Rückgabewert:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```


Wenn true, dient dieser Operator-Emulator als Ausrichtungspunkt; das heißt, bezeichnete Ausrichtungspunkte in anderen Gleichungen können mit ihm ausgerichtet werden. Standard: false

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


Expliziter Zeilenumbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch erfolgt, sodass die Zeile am Anfang des Box-Objekts umbricht. Gibt die Nummer des Operators in der vorherigen Zeile des mathematischen Textes an, der als Ausrichtungspunkt für die aktuelle Zeile des mathematischen Textes verwendet werden soll. Mögliche Werte: 1..255 Standard: 0 (kein expliziter Zeilenumbruch)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Rückgabewert:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```


Expliziter Zeilenumbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch erfolgt, sodass die Zeile am Anfang des Box-Objekts umbricht. Gibt die Nummer des Operators in der vorherigen Zeile des mathematischen Textes an, der als Ausrichtungspunkt für die aktuelle Zeile des mathematischen Textes verwendet werden soll. Mögliche Werte: 1..255 Standard: 0 (kein expliziter Zeilenumbruch)

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