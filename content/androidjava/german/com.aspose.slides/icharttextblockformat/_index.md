---
title: IChartTextBlockFormat
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt Formatierungseigenschaften für Diagramm-Text-Elemente dar.
type: docs
url: /de/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Stellt Formatierungseigenschaften für Diagramm-Text-Elemente dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Gibt den vertikalen Ankertext in einem TextFrame zurück oder legt ihn fest. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Gibt den vertikalen Ankertext in einem TextFrame zurück oder legt ihn fest. |
| [getCenterText()](#getCenterText--) | Wenn NullableBool.True, dann sollte der Text horizontal in der Box zentriert werden. |
| [setCenterText(byte value)](#setCenterText-byte-) | Wenn NullableBool.True, dann sollte der Text horizontal in der Box zentriert werden. |
| [getTextVerticalType()](#getTextVerticalType--) | Bestimmt die Textorientierung. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Bestimmt die Textorientierung. |
| [getMarginLeft()](#getMarginLeft--) | Gibt den linken Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Gibt den linken Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [getMarginRight()](#getMarginRight--) | Gibt den rechten Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [setMarginRight(double value)](#setMarginRight-double-) | Gibt den rechten Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [getMarginTop()](#getMarginTop--) | Gibt den oberen Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [setMarginTop(double value)](#setMarginTop-double-) | Gibt den oberen Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [getMarginBottom()](#getMarginBottom--) | Gibt den unteren Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Gibt den unteren Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [getWrapText()](#getWrapText--) | Wahr, wenn der Text an den Rändern des TextFrames umbrochen wird. |
| [setWrapText(byte value)](#setWrapText-byte-) | Wahr, wenn der Text an den Rändern des TextFrames umbrochen wird. |
| [getAutofitType()](#getAutofitType--) | Gibt den Autofit-Modus des Textes zurück oder legt ihn fest. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Gibt den Autofit-Modus des Textes zurück oder legt ihn fest. |
| [getRotationAngle()](#getRotationAngle--) | Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Gibt den vertikalen Ankertext in einem TextFrame zurück oder legt ihn fest. Lesen/Schreiben [TextAnchorType](../../com.aspose.slides/textanchortype).

**Rückgabe:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Gibt den vertikalen Ankertext in einem TextFrame zurück oder legt ihn fest. Lesen/Schreiben [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Wenn NullableBool.True, dann sollte der Text horizontal in der Box zentriert werden. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Wenn NullableBool.True, dann sollte der Text horizontal in der Box zentriert werden. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Bestimmt die Textorientierung. Der aus dieser Eigenschaft und dem benutzerdefinierten Winkel in der Eigenschaft RotationAngle errechnete visuelle Textrotationswert wird zurückgegeben. Lesen/Schreiben [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Rückgabe:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Bestimmt die Textorientierung. Der aus dieser Eigenschaft und dem benutzerdefinierten Winkel in der Eigenschaft RotationAngle errechnete visuelle Textrotationswert wird zurückgegeben. Lesen/Schreiben [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Gibt den linken Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Das Ändern dieser Eigenschaft kann nur für die folgenden Diagrammteile Einfluss haben: DataLabel und DataLabelFormat (volle Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat es keine Auswirkung auf die Darstellung). Lesen/Schreiben double.

**Rückgabe:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Gibt den linken Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Das Ändern dieser Eigenschaft kann nur für die folgenden Diagrammteile Einfluss haben: DataLabel und DataLabelFormat (volle Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat es keine Auswirkung auf die Darstellung). Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Gibt den rechten Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Das Ändern dieser Eigenschaft kann nur für die folgenden Diagrammteile Einfluss haben: DataLabel und DataLabelFormat (volle Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat es keine Auswirkung auf die Darstellung). Lesen/Schreiben double.

**Rückgabe:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Gibt den rechten Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Das Ändern dieser Eigenschaft kann nur für die folgenden Diagrammteile Einfluss haben: DataLabel und DataLabelFormat (volle Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat es keine Auswirkung auf die Darstellung). Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Gibt den oberen Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Das Ändern dieser Eigenschaft kann nur für die folgenden Diagrammteile Einfluss haben: DataLabel und DataLabelFormat (volle Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat es keine Auswirkung auf die Darstellung). Lesen/Schreiben double.

**Rückgabe:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Gibt den oberen Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Das Ändern dieser Eigenschaft kann nur für die folgenden Diagrammteile Einfluss haben: DataLabel und DataLabelFormat (volle Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat es keine Auswirkung auf die Darstellung). Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Gibt den unteren Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Das Ändern dieser Eigenschaft kann nur für die folgenden Diagrammteile Einfluss haben: DataLabel und DataLabelFormat (volle Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat es keine Auswirkung auf die Darstellung). Lesen/Schreiben double.

**Rückgabe:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Gibt den unteren Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Das Ändern dieser Eigenschaft kann nur für die folgenden Diagrammteile Einfluss haben: DataLabel und DataLabelFormat (volle Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat es keine Auswirkung auf die Darstellung). Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Wahr, wenn der Text an den Rändern des TextFrames umbrochen wird. Das Ändern dieser Eigenschaft kann nur für die folgenden Diagrammteile Einfluss haben: DataLabel und DataLabelFormat (volle Unterstützung in PowerPoint 2007/2013). Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Wahr, wenn der Text an den Rändern des TextFrames umbrochen wird. Das Ändern dieser Eigenschaft kann nur für die folgenden Diagrammteile Einfluss haben: DataLabel und DataLabelFormat (volle Unterstützung in PowerPoint 2007/2013). Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Gibt den Autofit-Modus des Textes zurück oder legt ihn fest. Das Ändern dieser Eigenschaft kann nur für die folgenden Diagrammteile Einfluss haben: DataLabel und DataLabelFormat (volle Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat es keine Auswirkung auf die Darstellung). Lesen/Schreiben [TextAutofitType](../../com.aspose.slides/textautofittype).

**Rückgabe:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Gibt den Autofit-Modus des Textes zurück oder legt ihn fest. Das Ändern dieser Eigenschaft kann nur für die folgenden Diagrammteile Einfluss haben: DataLabel und DataLabelFormat (volle Unterstützung in PowerPoint 2013; in PowerPoint 2007 hat es keine Auswirkung auf die Darstellung). Lesen/Schreiben [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn sie nicht angegeben ist, wird die Drehung der zugehörigen Form verwendet. Ist sie angegeben, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form zusätzlich zu einer eigenen Drehung des Textes rotieren kann. Der aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType errechnete visuelle Textrotationswert wird zurückgegeben. Lesen/Schreiben float.

--------------------

> ```
> Betrachten Sie den Fall, dass einer Form eine Drehung von 90 Grad im Uhrzeigersinn auferlegt wird. 
>  Zusätzlich dazu hat der Textkörper selbst eine Drehung von -90 Grad 
>  gegen den Uhrzeigersinn erhalten. Dann würde die resultierende Form erscheinen, 
>  gedreht, aber der Text darin würde erscheinen, als wäre er überhaupt nicht gedreht worden.
```

**Rückgabe:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn sie nicht angegeben ist, wird die Drehung der zugehörigen Form verwendet. Ist sie angegeben, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form zusätzlich zu einer eigenen Drehung des Textes rotieren kann. Der aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType errechnete visuelle Textrotationswert wird zurückgegeben. Lesen/Schreiben float.

--------------------

> ```
> Betrachten Sie den Fall, dass einer Form eine Drehung von 90 Grad im Uhrzeigersinn auferlegt wird. 
>  Zusätzlich dazu hat der Textkörper selbst eine Drehung von -90 Grad 
>  gegen den Uhrzeigersinn erhalten. Dann würde die resultierende Form erscheinen, 
>  gedreht, aber der Text darin würde erscheinen, als wäre er überhaupt nicht gedreht worden.
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |