---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Java API Reference
description: Stellt Formatierungseigenschaften für Diagrammtext-Elemente dar.
type: docs
url: /de/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Stellt Formatierungseigenschaften für Diagrammtext-Elemente dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Gibt zurück oder legt fest, wo der vertikale Ankertext in einem TextFrame steht. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Gibt zurück oder legt fest, wo der vertikale Ankertext in einem TextFrame steht. |
| [getCenterText()](#getCenterText--) | Wenn NullableBool.True, dann sollte der Text horizontal zentriert im Feld sein. |
| [setCenterText(byte value)](#setCenterText-byte-) | Wenn NullableBool.True, dann sollte der Text horizontal zentriert im Feld sein. |
| [getTextVerticalType()](#getTextVerticalType--) | Bestimmt die Textorientierung. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Bestimmt die Textorientierung. |
| [getMarginLeft()](#getMarginLeft--) | Gibt zurück oder legt fest, welcher linke Rand (Punkte) in einem TextFrame verwendet wird. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Gibt zurück oder legt fest, welcher linke Rand (Punkte) in einem TextFrame verwendet wird. |
| [getMarginRight()](#getMarginRight--) | Gibt zurück oder legt fest, welcher rechte Rand (Punkte) in einem TextFrame verwendet wird. |
| [setMarginRight(double value)](#setMarginRight-double-) | Gibt zurück oder legt fest, welcher rechte Rand (Punkte) in einem TextFrame verwendet wird. |
| [getMarginTop()](#getMarginTop--) | Gibt zurück oder legt fest, welcher obere Rand (Punkte) in einem TextFrame verwendet wird. |
| [setMarginTop(double value)](#setMarginTop-double-) | Gibt zurück oder legt fest, welcher obere Rand (Punkte) in einem TextFrame verwendet wird. |
| [getMarginBottom()](#getMarginBottom--) | Gibt zurück oder legt fest, welcher untere Rand (Punkte) in einem TextFrame verwendet wird. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Gibt zurück oder legt fest, welcher untere Rand (Punkte) in einem TextFrame verwendet wird. |
| [getWrapText()](#getWrapText--) | Wahr, wenn der Text an den Rändern des TextFrames umbrochen wird. |
| [setWrapText(byte value)](#setWrapText-byte-) | Wahr, wenn der Text an den Rändern des TextFrames umbrochen wird. |
| [getAutofitType()](#getAutofitType--) | Gibt zurück oder legt fest, welcher Autofit-Modus für den Text verwendet wird. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Gibt zurück oder legt fest, welcher Autofit-Modus für den Text verwendet wird. |
| [getRotationAngle()](#getRotationAngle--) | Gibt die benutzerdefinierte Drehung an, die auf den Text im Begrenzungsrahmen angewendet wird. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Gibt die benutzerdefinierte Drehung an, die auf den Text im Begrenzungsrahmen angewendet wird. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Gibt zurück oder legt fest, wo der vertikale Ankertext in einem TextFrame steht. Lesen/Schreiben [TextAnchorType](../../com.aspose.slides/textanchortype).

**Rückgabewert:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Gibt zurück oder legt fest, wo der vertikale Ankertext in einem TextFrame steht. Lesen/Schreiben [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Wenn NullableBool.True, dann sollte der Text horizontal zentriert im Feld sein. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabewert:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Wenn NullableBool.True, dann sollte der Text horizontal zentriert im Feld sein. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Bestimmt die Textorientierung. Der resultierende visuelle Textrotationswert ergibt sich aus dieser Eigenschaft und dem benutzerdefinierten Winkel in der Eigenschaft RotationAngle. Lesen/Schreiben [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Rückgabewert:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Bestimmt die Textorientierung. Der resultierende visuelle Textrotationswert ergibt sich aus dieser Eigenschaft und dem benutzerdefinierten Winkel in der Eigenschaft RotationAngle. Lesen/Schreiben [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Gibt zurück oder legt fest, welcher linke Rand (Punkte) in einem TextFrame verwendet wird. Die Änderung dieser Eigenschaft kann nur bei folgenden Diagrammteilen Einfluss haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat sie keinen Effekt auf die Darstellung). Lesen/Schreiben double.

**Rückgabewert:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Gibt zurück oder legt fest, welcher linke Rand (Punkte) in einem TextFrame verwendet wird. Die Änderung dieser Eigenschaft kann nur bei folgenden Diagrammteilen Einfluss haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat sie keinen Effekt auf die Darstellung). Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Gibt zurück oder legt fest, welcher rechte Rand (Punkte) in einem TextFrame verwendet wird. Die Änderung dieser Eigenschaft kann nur bei folgenden Diagrammteilen Einfluss haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat sie keinen Effekt auf die Darstellung). Lesen/Schreiben double.

**Rückgabewert:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Gibt zurück oder legt fest, welcher rechte Rand (Punkte) in einem TextFrame verwendet wird. Die Änderung dieser Eigenschaft kann nur bei folgenden Diagrammteilen Einfluss haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat sie keinen Effekt auf die Darstellung). Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Gibt zurück oder legt fest, welcher obere Rand (Punkte) in einem TextFrame verwendet wird. Die Änderung dieser Eigenschaft kann nur bei folgenden Diagrammteilen Einfluss haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat sie keinen Effekt auf die Darstellung). Lesen/Schreiben double.

**Rückgabewert:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Gibt zurück oder legt fest, welcher obere Rand (Punkte) in einem TextFrame verwendet wird. Die Änderung dieser Eigenschaft kann nur bei folgenden Diagrammteilen Einfluss haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat sie keinen Effekt auf die Darstellung). Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Gibt zurück oder legt fest, welcher untere Rand (Punkte) in einem TextFrame verwendet wird. Die Änderung dieser Eigenschaft kann nur bei folgenden Diagrammteilen Einfluss haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat sie keinen Effekt auf die Darstellung). Lesen/Schreiben double.

**Rückgabewert:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Gibt zurück oder legt fest, welcher untere Rand (Punkte) in einem TextFrame verwendet wird. Die Änderung dieser Eigenschaft kann nur bei folgenden Diagrammteilen Einfluss haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat sie keinen Effekt auf die Darstellung). Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Wahr, wenn der Text an den Rändern des TextFrames umbrochen wird. Die Änderung dieser Eigenschaft kann nur bei folgenden Diagrammteilen Einfluss haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2007/2013). Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabewert:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Wahr, wenn der Text an den Rändern des TextFrames umbrochen wird. Die Änderung dieser Eigenschaft kann nur bei folgenden Diagrammteilen Einfluss haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2007/2013). Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Gibt zurück oder legt fest, welcher Autofit-Modus für den Text verwendet wird. Die Änderung dieser Eigenschaft kann nur bei folgenden Diagrammteilen Einfluss haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat sie keinen Effekt auf die Darstellung). Lesen/Schreiben [TextAutofitType](../../com.aspose.slides/textautofittype).

**Rückgabewert:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Gibt zurück oder legt fest, welcher Autofit-Modus für den Text verwendet wird. Die Änderung dieser Eigenschaft kann nur bei folgenden Diagrammteilen Einfluss haben: DataLabel und DataLabelFormat (vollständige Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat sie keinen Effekt auf die Darstellung). Lesen/Schreiben [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Gibt die benutzerdefinierte Drehung an, die auf den Text im Begrenzungsrahmen angewendet wird. Wenn sie nicht angegeben ist, wird die Drehung der zugehörigen Form verwendet. Ist sie angegeben, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form zusätzlich zu dem Text selbst eine eigene Drehung haben kann. Der resultierende visuelle Textrotationswert ergibt sich aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType. Lesen/Schreiben float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Rückgabewert:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Gibt die benutzerdefinierte Drehung an, die auf den Text im Begrenzungsrahmen angewendet wird. Wenn sie nicht angegeben ist, wird die Drehung der zugehörigen Form verwendet. Ist sie angegeben, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form zusätzlich zu dem Text selbst eine eigene Drehung haben kann. Der resultierende visuelle Textrotationswert ergibt sich aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType. Lesen/Schreiben float.

--------------------

> ```
> Betrachten Sie den Fall, dass einer Form eine Drehung von 90 Grad im Uhrzeigersinn zugewiesen wird. 
>  Zusätzlich dazu hat der Textkörper selbst eine Drehung von -90 Grad 
>  gegen den Uhrzeigersinn angewendet. Dann würde die resultierende Form erscheinen, dass
>  sie rotiert ist, aber der Text darin würde erscheinen, als wäre er überhaupt nicht rotiert worden.
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |