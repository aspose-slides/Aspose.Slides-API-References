---
title: MathArray
second_title: Aspose.Slides für Android via Java API Referenz
description: Gibt ein vertikales Array von Gleichungen oder beliebigen mathematischen Objekten an
type: docs
url: /de/com.aspose.slides/matharray/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Gibt ein vertikales Array von Gleichungen oder beliebigen mathematischen Objekten an

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Erstellt ein mathematisches Array und platziert das angegebene Element darin |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Erstellt ein mathematisches Array und platziert die angegebenen Elemente darin |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getArguments()](#getArguments--) | Die Menge der Elemente des Arrays |
| [getBaseJustification()](#getBaseJustification--) | Gibt die Ausrichtung des Arrays relativ zum umgebenden Text an. Text außerhalb des Arrays kann mit dem unteren, oberen oder mittleren Teil eines Array-Objekts ausgerichtet werden. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Gibt die Ausrichtung des Arrays relativ zum umgebenden Text an. Text außerhalb des Arrays kann mit dem unteren, oberen oder mittleren Teil eines Array-Objekts ausgerichtet werden. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution: Wenn true, wird das Array auf die maximale Breite des enthaltenden Elements (Seite, Spalte, Zelle usw.) ausgedehnt. |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution: Wenn true, wird das Array auf die maximale Breite des enthaltenden Elements (Seite, Spalte, Zelle usw.) ausgedehnt. |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution: Wenn true, werden die Inhalte des Arrays auf die maximale Breite des Array-Objekts ausgedehnt. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution: Wenn true, werden die Inhalte des Arrays auf die maximale Breite des Array-Objekts ausgedehnt. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Der Typ des vertikalen Abstands zwischen Array-Elementen. Standard: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Der Typ des vertikalen Abstands zwischen Array-Elementen. Standard: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Abstand zwischen Zeilen eines Arrays. Wird nur verwendet, wenn RowSpacingRule auf 3 gesetzt ist. In diesem Fall ist die Maßeinheit Punkte, oder bei Multiple ist die Einheit halbe Zeilen. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Abstand zwischen Zeilen eines Arrays. Wird nur verwendet, wenn RowSpacingRule auf 3 gesetzt ist. In diesem Fall ist die Maßeinheit Punkte, oder bei Multiple ist die Einheit halbe Zeilen. |
| [getChildren()](#getChildren--) | Ruft Kindelemente ab |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```


Erstellt ein mathematisches Array und platziert das angegebene Element darin

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Das Element, das im Array platziert werden soll |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```


Erstellt ein mathematisches Array und platziert die angegebenen Elemente darin

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elemente, die im Array platziert werden sollen |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```


Die Menge der Elemente des Arrays

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Rückgabe:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```


Gibt die Ausrichtung des Arrays relativ zum umgebenden Text an. Text außerhalb des Arrays kann mit dem unteren, oberen oder mittleren Teil eines Array-Objekts ausgerichtet werden. Standardwert: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Rückgabe:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```


Gibt die Ausrichtung des Arrays relativ zum umgebenden Text an. Text außerhalb des Arrays kann mit dem unteren, oberen oder mittleren Teil eines Array-Objekts ausgerichtet werden. Standardwert: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```


Maximum Distribution: Wenn true, wird das Array auf die maximale Breite des enthaltenden Elements (Seite, Spalte, Zelle usw.) ausgedehnt.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Rückgabe:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```


Maximum Distribution: Wenn true, wird das Array auf die maximale Breite des enthaltenden Elements (Seite, Spalte, Zelle usw.) ausgedehnt.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```


Object Distribution: Wenn true, werden die Inhalte des Arrays auf die maximale Breite des Array-Objekts ausgedehnt.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Rückgabe:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```


Object Distribution: Wenn true, werden die Inhalte des Arrays auf die maximale Breite des Array-Objekts ausgedehnt.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```


Der Typ des vertikalen Abstands zwischen Array-Elementen. Standard: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Rückgabe:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```


Der Typ des vertikalen Abstands zwischen Array-Elementen. Standard: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```


Abstand zwischen Zeilen eines Arrays. Wird nur verwendet, wenn RowSpacingRule auf 3 gesetzt ist. In diesem Fall ist die Maßeinheit Punkte, oder bei Multiple ist die Einheit halbe Zeilen. Standard: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Rückgabe:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```


Abstand zwischen Zeilen eines Arrays. Wird nur verwendet, wenn RowSpacingRule auf 3 gesetzt ist. In diesem Fall ist die Maßeinheit Punkte, oder bei Multiple ist die Einheit halbe Zeilen. Standard: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Ruft Kindelemente ab

**Rückgabe:**
com.aspose.slides.IMathElement[]