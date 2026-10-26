---
title: MathBox
second_title: Aspose.Slides für Java API Referenz
description: Gibt die logische Box-Verpackung eines mathematischen Elements an.
type: docs
url: /de/com.aspose.slides/mathbox/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Gibt die logische Boxung (Verpackung) eines mathematischen Elements an. Beispielsweise kann ein verpacktes Objekt als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass innerhalb des Objekts keine Zeilenumbrüche erlaubt sind. Zum Beispiel sollte der Operator "==" boxiert werden, um Zeilenumbrüche zu verhindern.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Initialisiert MathBox mit dem angegebenen Element als Argument |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator Emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator Emulator. |
| [getNoBreak()](#getNoBreak--) | No break Diese Eigenschaft gibt die "unbreakable"-Eigenschaft des Objektkastens an. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | No break Diese Eigenschaft gibt die "unbreakable"-Eigenschaft des Objektkastens an. |
| [getDifferential()](#getDifferential--) | Differential Wenn true, wirkt die Box als Differential (z. B. \\ud835\\udc51\\ud835\\udc65 in einem Integranden) und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential Wenn true, wirkt die Box als Differential (z. B. \\ud835\\udc51\\ud835\\udc65 in einem Integranden) und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Wenn true, dient dieser Operator-Emulator als Ausrichtungspunkt; das heißt, benannte Ausrichtungspunkte in anderen Gleichungen können mit ihm ausgerichtet werden. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Wenn true, dient dieser Operator-Emulator als Ausrichtungspunkt; das heißt, benannte Ausrichtungspunkte in anderen Gleichungen können mit ihm ausgerichtet werden. |
| [getExplicitBreak()](#getExplicitBreak--) | Expliziter Umbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch vorhanden ist, sodass die Zeile am Anfang des Box-Objekts umbricht. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Expliziter Umbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch vorhanden ist, sodass die Zeile am Anfang des Box-Objekts umbricht. |
| [getChildren()](#getChildren--) | Gibt Kindelemente zurück |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Steuerzeichen-Eigenschaften |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```


Initialisiert MathBox mit dem angegebenen Element als Argument

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Das Basiselement, auf das die Box angewendet wird. Kann null sein. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```


Operator Emulator. Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Punkt für einen Zeilenumbruch dienen und an anderen Operatoren ausgerichtet werden kann. Operator-Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, wie z. B. '=='. Standardwert: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Rückgabewert:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```


Operator Emulator. Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Punkt für einen Zeilenumbruch dienen und an anderen Operatoren ausgerichtet werden kann. Operator-Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, wie z. B. '=='. Standardwert: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```


No break Diese Eigenschaft gibt die "unbreakable"-Eigenschaft des Objektkastens an. Wenn true, können innerhalb der Box keine Zeilenumbrüche auftreten. Dies kann bei Operator-Emulatoren wichtig sein, die aus mehr als einem binären Operator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb der Box Umbrüche auftreten. Standardwert: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Rückgabewert:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```


No break Diese Eigenschaft gibt die "unbreakable"-Eigenschaft des Objektkastens an. Wenn true, können innerhalb der Box keine Zeilenumbrüche auftreten. Dies kann bei Operator-Emulatoren wichtig sein, die aus mehr als einem binären Operator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb der Box Umbrüche auftreten. Standardwert: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```


Differential Wenn true, wirkt die Box als Differential (z. B. \\ud835\\udc51\\ud835\\udc65 in einem Integranden) und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. Standardwert: false

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
public final void setDifferential(boolean value)
```


Differential Wenn true, wirkt die Box als Differential (z. B. \\ud835\\udc51\\ud835\\udc65 in einem Integranden) und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. Standardwert: false

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
public final boolean getAlignmentPoint()
```


Wenn true, dient dieser Operator-Emulator als Ausrichtungspunkt; das heißt, benannte Ausrichtungspunkte in anderen Gleichungen können mit ihm ausgerichtet werden. Standardwert: false

--------------------

> ```
> Beispiel:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Rückgabewert:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```


Wenn true, dient dieser Operator-Emulator als Ausrichtungspunkt; das heißt, benannte Ausrichtungspunkte in anderen Gleichungen können mit ihm ausgerichtet werden. Standardwert: false

--------------------

> ```
> Beispiel:
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
public final byte getExplicitBreak()
```


Expliziter Umbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch vorhanden ist, sodass die Zeile am Anfang des Box-Objekts umbricht. Gibt die Nummer des Operators in der vorherigen Zeile mathematischen Textes an, die als Ausrichtungspunkt für die aktuelle Zeile mathematischen Textes verwendet werden soll. Mögliche Werte: 1..255 Standardwert: 0 (kein expliziter Umbruch)

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
public final void setExplicitBreak(byte value)
```


Expliziter Umbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch vorhanden ist, sodass die Zeile am Anfang des Box-Objekts umbricht. Gibt die Nummer des Operators in der vorherigen Zeile mathematischen Textes an, die als Ausrichtungspunkt für die aktuelle Zeile mathematischen Textes verwendet werden soll. Mögliche Werte: 1..255 Standardwert: 0 (kein expliziter Umbruch)

--------------------

> ```
> Beispiel:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

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