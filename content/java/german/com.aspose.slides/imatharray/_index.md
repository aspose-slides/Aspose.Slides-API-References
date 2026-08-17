---
title: IMathArray
second_title: Aspose.Slides für Java API-Referenz
description: Gibt ein vertikales Array von Gleichungen oder beliebigen mathematischen Objekten an
type: docs
url: /de/com.aspose.slides/imatharray/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Gibt ein vertikales Array von Gleichungen oder beliebigen mathematischen Objekten an

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getArguments()](#getArguments--) | Die Menge der Elemente des Arrays |
| [getBaseJustification()](#getBaseJustification--) | Legt die Ausrichtung des Arrays relativ zum umgebenden Text fest. Text außerhalb des Arrays kann mit dem unteren Rand, dem oberen Rand oder der Mitte eines Array-Objekts ausgerichtet werden. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Legt die Ausrichtung des Arrays relativ zum umgebenden Text fest. Text außerhalb des Arrays kann mit dem unteren Rand, dem oberen Rand oder der Mitte eines Array-Objekts ausgerichtet werden. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximale Verteilung. Wenn true, wird das Array auf die maximale Breite des enthaltenden Elements (Seite, Spalte, Zelle usw.) ausgedehnt. |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximale Verteilung. Wenn true, wird das Array auf die maximale Breite des enthaltenden Elements (Seite, Spalte, Zelle usw.) ausgedehnt. |
| [getObjectDistribution()](#getObjectDistribution--) | Objektverteilung. Wenn true, wird der Inhalt des Arrays auf die maximale Breite des Array-Objekts ausgedehnt. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Objektverteilung. Wenn true, wird der Inhalt des Arrays auf die maximale Breite des Array-Objekts ausgedehnt. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Der Typ des vertikalen Abstands zwischen Array-Elementen |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Der Typ des vertikalen Abstands zwischen Array-Elementen |
| [getRowSpacing()](#getRowSpacing--) | Abstand zwischen Zeilen eines Arrays. Wird nur verwendet, wenn RowSpacingRule auf 3 gesetzt ist. Genau in diesem Fall ist die Maßeinheit Punkte, oder Multiple, wobei die Maßeinheit Halblinien ist. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Abstand zwischen Zeilen eines Arrays. Wird nur verwendet, wenn RowSpacingRule auf 3 gesetzt ist. Genau in diesem Fall ist die Maßeinheit Punkte, oder Multiple, wobei die Maßeinheit Halblinien ist. |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Die Menge der Elemente des Arrays

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Rückgabewert:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Legt die Ausrichtung des Arrays relativ zum umgebenden Text fest. Text außerhalb des Arrays kann mit dem unteren Rand, dem oberen Rand oder der Mitte eines Array-Objekts ausgerichtet werden. Standardwert: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Rückgabewert:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Legt die Ausrichtung des Arrays relativ zum umgebenden Text fest. Text außerhalb des Arrays kann mit dem unteren Rand, dem oberen Rand oder der Mitte eines Array-Objekts ausgerichtet werden. Standardwert: Center

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
public abstract boolean getMaximumDistribution()
```

Maximale Verteilung. Wenn true, wird das Array auf die maximale Breite des enthaltenden Elements (Seite, Spalte, Zelle usw.) ausgedehnt.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Rückgabewert:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

Maximale Verteilung. Wenn true, wird das Array auf die maximale Breite des enthaltenden Elements (Seite, Spalte, Zelle usw.) ausgedehnt.

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
public abstract boolean getObjectDistribution()
```

Objektverteilung. Wenn true, wird der Inhalt des Arrays auf die maximale Breite des Array-Objekts ausgedehnt.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Rückgabewert:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

Objektverteilung. Wenn true, wird der Inhalt des Arrays auf die maximale Breite des Array-Objekts ausgedehnt.

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
public abstract int getRowSpacingRule()
```

Der Typ des vertikalen Abstands zwischen Array-Elementen

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Rückgabewert:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

Der Typ des vertikalen Abstands zwischen Array-Elementen

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
public abstract long getRowSpacing()
```

Abstand zwischen Zeilen eines Arrays. Wird nur verwendet, wenn RowSpacingRule auf 3 gesetzt ist. Genau in diesem Fall ist die Maßeinheit Punkte, oder Multiple, wobei die Maßeinheit Halblinien ist. Standard: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Rückgabewert:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

Abstand zwischen Zeilen eines Arrays. Wird nur verwendet, wenn RowSpacingRule auf 3 gesetzt ist. Genau in diesem Fall ist die Maßeinheit Punkte, oder Multiple, wobei die Maßeinheit Halblinien ist. Standard: 0

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