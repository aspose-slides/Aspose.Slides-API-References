---
title: IDataLabelFormat
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Stellt Formatoptionen für DataLabel dar.
type: docs
url: /de/com.aspose.slides/idatalabelformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Stellt Formatoptionen für DataLabel dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Lese-/Schreib boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Lese-/Schreib boolean. |
| [getNumberFormat()](#getNumberFormat--) | Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. |
| [getFormat()](#getFormat--) | Stellt das Format der Datenbeschriftung dar. |
| [getPosition()](#getPosition--) | Stellt die Position der Datenbeschriftung dar. |
| [setPosition(int value)](#setPosition-int-) | Stellt die Position der Datenbeschriftung dar. |
| [getShowLegendKey()](#getShowLegendKey--) | Stellt das Legenden-Schlüsseldarstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Stellt das Legenden-Schlüsseldarstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowValue()](#getShowValue--) | Stellt das Prozentwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Stellt das Prozentwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowCategoryName()](#getShowCategoryName--) | Stellt das Kategorienamen-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Stellt das Kategorienamen-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowSeriesName()](#getShowSeriesName--) | Gibt einen Boolean zurück oder legt ihn fest, um das Anzeigen des Seriennamens für die Datenbeschriftungen eines Diagramms zu steuern. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Gibt einen Boolean zurück oder legt ihn fest, um das Anzeigen des Seriennamens für die Datenbeschriftungen eines Diagramms zu steuern. |
| [getShowPercentage()](#getShowPercentage--) | Stellt das Prozentwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Stellt das Prozentwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Stellt das Bubble-Größenwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Stellt das Bubble-Größenwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Stellt das Leitlinien-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Stellt das Leitlinien-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Bestimmt, ob die Datenbeschriftung eines angegebenen Diagramms als Daten-Callout oder als Datenbeschriftung angezeigt wird. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Bestimmt, ob die Datenbeschriftung eines angegebenen Diagramms als Daten-Callout oder als Datenbeschriftung angezeigt wird. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Stellt das Zellenwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Stellt das Zellenwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. |
| [getSeparator()](#getSeparator--) | Setzt oder gibt eine Variant zurück, die das Trennzeichen für die Datenbeschriftungen eines Diagramms darstellt. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Setzt oder gibt eine Variant zurück, die das Trennzeichen für die Datenbeschriftungen eines Diagramms darstellt. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der IsNumberFormatLinkedToSource-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird dieser Wert auch für die IsNumberFormatLinkedToSource-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" bewirkt, dass alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() den Wert val haben).

**Rückgabewert:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der IsNumberFormatLinkedToSource-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird dieser Wert auch für die IsNumberFormatLinkedToSource-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" bewirkt, dass alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() den Wert val haben).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Lese-/Schreib String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der NumberFormat-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Wird diese Eigenschaft mit einem Wert gesetzt, wird derselbe Wert auch für die NumberFormat-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" bewirkt, dass alle DataLabels.get_Item(i).getNumberFormat() den Wert val haben).

**Rückgabewert:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Lese-/Schreib String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der NumberFormat-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Wird diese Eigenschaft mit einem Wert gesetzt, wird derselbe Wert auch für die NumberFormat-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" bewirkt, dass alle DataLabels.get_Item(i).getNumberFormat() den Wert val haben).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Stellt das Format der Datenbeschriftung dar. Nur-lesen [IFormat](../../com.aspose.slides/iformat).

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann stellt diese Eigenschaft das Standardformat für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung dar.

**Rückgabewert:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Stellt die Position der Datenbeschriftung dar. Lese-/Schreib [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der Position-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Sie stellt die Position für die DataLabel-Objekte dar. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die Position-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" bewirkt, dass alle DataLabels.get_Item(i).getPosition() den Wert val haben).

**Rückgabewert:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Stellt die Position der Datenbeschriftung dar. Lese-/Schreib [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der Position-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Sie stellt die Position für die DataLabel-Objekte dar. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die Position-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" bewirkt, dass alle DataLabels.get_Item(i).getPosition() den Wert val haben).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Stellt das Legenden-Schlüsseldarstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. True, wenn der Legenden-Schlüssel der Datenbeschriftung sichtbar ist. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLegendKey-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowLegendKey-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowLegendKey() den Wert val haben).

**Rückgabewert:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Stellt das Legenden-Schlüsseldarstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. True, wenn der Legenden-Schlüssel der Datenbeschriftung sichtbar ist. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLegendKey-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowLegendKey-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowLegendKey() den Wert val haben).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Stellt das Prozentwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. True zeigt den Prozentwert an. False, um zu verbergen. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowValue-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowValue-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowValue() den Wert val haben).

**Rückgabewert:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Stellt das Prozentwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. True zeigt den Prozentwert an. False, um zu verbergen. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowValue-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowValue-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowValue() den Wert val haben).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Stellt das Kategorienamen-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. True, um den Kategorienamen für die Datenbeschriftungen eines Diagramms anzuzeigen. False, um zu verbergen. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowCategoryName-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowCategoryName-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowCategoryName() den Wert val haben).

**Rückgabewert:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Stellt das Kategorienamen-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. True, um den Kategorienamen für die Datenbeschriftungen eines Diagramms anzuzeigen. False, um zu verbergen. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowCategoryName-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowCategoryName-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowCategoryName() den Wert val haben).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Gibt einen Boolean zurück oder legt ihn fest, um das Anzeigen des Seriennamens für die Datenbeschriftungen eines Diagramms zu steuern. True, um den Seriennamen anzuzeigen. False, um zu verbergen. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowSeriesName-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowSeriesName-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowSeriesName() den Wert val haben).

**Rückgabewert:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Gibt einen Boolean zurück oder legt ihn fest, um das Anzeigen des Seriennamens für die Datenbeschriftungen eines Diagramms zu steuern. True, um den Seriennamen anzuzeigen. False, um zu verbergen. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowSeriesName-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowSeriesName-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowSeriesName() den Wert val haben).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Stellt das Prozentwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. True zeigt den Prozentwert an. False, um zu verbergen. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowPercentage-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowPercentage-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowPercentage() den Wert val haben).

**Rückgabewert:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Stellt das Prozentwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. True zeigt den Prozentwert an. False, um zu verbergen. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowPercentage-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowPercentage-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowPercentage() den Wert val haben).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Stellt das Bubble-Größenwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. True zeigt den Bubble-Größenwert an. False, um zu verbergen. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowBubbleSize-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowBubbleSize-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowBubbleSize() den Wert val haben).

**Rückgabewert:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Stellt das Bubble-Größenwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. True zeigt den Bubble-Größenwert an. False, um zu verbergen. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowBubbleSize-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowBubbleSize-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowBubbleSize() den Wert val haben).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Stellt das Leitlinien-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. True zeigt die Leitlinien an. False, um zu verbergen. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLeaderLines-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowLeaderLines-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowLeaderLines() den Wert val haben).

**Rückgabewert:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Stellt das Leitlinien-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. True zeigt die Leitlinien an. False, um zu verbergen. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLeaderLines-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowLeaderLines-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowLeaderLines() den Wert val haben).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Bestimmt, ob die Datenbeschriftung eines angegebenen Diagramms als Daten-Callout oder als Datenbeschriftung angezeigt wird.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLabelAsDataCallout-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowLabelAsDataCallout-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowLabelAsDataCallout() den Wert val haben).

**Rückgabewert:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Bestimmt, ob die Datenbeschriftung eines angegebenen Diagramms als Daten-Callout oder als Datenbeschriftung angezeigt wird.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLabelAsDataCallout-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowLabelAsDataCallout-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowLabelAsDataCallout() den Wert val haben).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Stellt das Zellenwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. True zeigt den Zellenwert an. False, um zu verbergen. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLabelValueFromCell-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowLabelValueFromCell-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowLabelValueFromCell() den Wert val haben).

**Rückgabewert:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Stellt das Zellenwert-Darstellungsverhalten einer angegebenen Diagrammdatenbeschriftung dar. True zeigt den Zellenwert an. False, um zu verbergen. Lese-/Schreib boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLabelValueFromCell-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die ShowLabelValueFromCell-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" bewirkt, dass alle DataLabels.get_Item(i).getShowLabelValueFromCell() den Wert val haben).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Setzt oder gibt eine Variant zurück, die das Trennzeichen für die Datenbeschriftungen eines Diagramms darstellt. Lese-/Schreib String.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der Separator-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die Separator-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" bewirkt, dass alle DataLabels.get_Item(i).getSeparator() den Wert val haben).

**Rückgabewert:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Setzt oder gibt eine Variant zurück, die das Trennzeichen für die Datenbeschriftungen eines Diagramms darstellt. Lese-/Schreib String.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der Separator-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird derselbe Wert auch für die Separator-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (z. B. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" bewirkt, dass alle DataLabels.get_Item(i).getSeparator() den Wert val haben).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |