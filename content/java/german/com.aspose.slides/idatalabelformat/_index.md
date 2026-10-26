---
title: IDataLabelFormat
second_title: Aspose.Slides für Java API Referenz
description: Stellt Formatierungsoptionen für DataLabel dar.
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
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Lese-/Schreib-Boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Lese-/Schreib-Boolean. |
| [getNumberFormat()](#getNumberFormat--) | Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. |
| [getFormat()](#getFormat--) | Stellt das Format der Datenbeschriftung dar. |
| [getPosition()](#getPosition--) | Stellt die Position der Datenbeschriftung dar. |
| [setPosition(int value)](#setPosition-int-) | Stellt die Position der Datenbeschriftung dar. |
| [getShowLegendKey()](#getShowLegendKey--) | Stellt das Anzeigeverhalten des Legenden-Schlüssels einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Stellt das Anzeigeverhalten des Legenden-Schlüssels einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowValue()](#getShowValue--) | Stellt das Anzeigeverhalten des Prozentwerts einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Stellt das Anzeigeverhalten des Prozentwerts einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowCategoryName()](#getShowCategoryName--) | Stellt das Anzeigeverhalten des Kategorienamens einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Stellt das Anzeigeverhalten des Kategorienamens einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowSeriesName()](#getShowSeriesName--) | Gibt ein Boolean zurück oder legt es fest, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm anzugeben. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Gibt ein Boolean zurück oder legt es fest, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm anzugeben. |
| [getShowPercentage()](#getShowPercentage--) | Stellt das Anzeigeverhalten des Prozentwerts einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Stellt das Anzeigeverhalten des Prozentwerts einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Stellt das Anzeigeverhalten des Blasengrößenwerts einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Stellt das Anzeigeverhalten des Blasengrößenwerts einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Stellt das Anzeigeverhalten der Leitlinien einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Stellt das Anzeigeverhalten der Leitlinien einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Bestimmt, ob die Datenbeschriftung eines angegebenen Diagramms als Daten-Callout oder als Datenbeschriftung angezeigt wird. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Bestimmt, ob die Datenbeschriftung eines angegebenen Diagramms als Daten-Callout oder als Datenbeschriftung angezeigt wird. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Stellt das Anzeigeverhalten des Zellenwerts einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Stellt das Anzeigeverhalten des Zellenwerts einer angegebenen Diagrammdatenbeschriftung dar. |
| [getSeparator()](#getSeparator--) | Legt einen Variant fest oder gibt ihn zurück, der das Trennzeichen für die Datenbeschriftungen in einem Diagramm darstellt. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Legt einen Variant fest oder gibt ihn zurück, der das Trennzeichen für die Datenbeschriftungen in einem Diagramm darstellt. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Lese-/Schreib-Boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Container von Datenbeschriftungen ist, ruft diese Eigenschaft den Standardwert der IsNumberFormatLinkedToSource-Eigenschaft für neue Datenbeschriftungen in der DataLabelCollection ab bzw. legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert ändert diesen Wert ebenfalls für die IsNumberFormatLinkedToSource-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. „DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);“, wodurch für alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() der Wert val gilt).

**Rückgabe:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Lese-/Schreib-Boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Container von Datenbeschriftungen ist, ruft diese Eigenschaft den Standardwert der IsNumberFormatLinkedToSource-Eigenschaft für neue Datenbeschriftungen in der DataLabelCollection ab bzw. legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert ändert diesen Wert ebenfalls für die IsNumberFormatLinkedToSource-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. „DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);“, wodurch für alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() der Wert val gilt).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Lese-/Schreib-String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Container von Datenbeschriftungen ist, ruft diese Eigenschaft den Standardwert der NumberFormat-Eigenschaft für neue Datenbeschriftungen in der DataLabelCollection ab bzw. legt ihn fest. Wird diese Eigenschaft mit einem Wert gesetzt, wird derselbe Wert auch für die NumberFormat-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection übernommen (z. B. „DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);“, wodurch für alle DataLabels.get_Item(i).getNumberFormat() der Wert val gilt).

**Rückgabe:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Lese-/Schreib-String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Container von Datenbeschriftungen ist, ruft diese Eigenschaft den Standardwert der NumberFormat-Eigenschaft für neue Datenbeschriftungen in der DataLabelCollection ab bzw. legt ihn fest. Wird diese Eigenschaft mit einem Wert gesetzt, wird derselbe Wert auch für die NumberFormat-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection übernommen (z. B. „DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);“, wodurch für alle DataLabels.get_Item(i).getNumberFormat() der Wert val gilt).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Stellt das Format der Datenbeschriftung dar. Nur-Lesen [IFormat](../../com.aspose.slides/iformat).

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Container von Datenbeschriftungen ist, stellt diese Eigenschaft das Standardformat für neue Datenbeschriftungen in der DataLabelCollection dar.

**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Stellt die Position der Datenbeschriftung dar. Lese-/Schreib [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Container von Datenbeschriftungen ist, ruft diese Eigenschaft den Standardwert der Position-Eigenschaft für neue Datenbeschriftungen in der DataLabelCollection ab bzw. legt ihn fest. Sie stellt die Position für die DataLabel-Objekte dar. Das Setzen dieser Eigenschaft mit einem Wert ändert diesen Wert ebenfalls für die Position-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. „DataLabels.getDefaultDataLabelFormat().setPosition(val)“, wodurch für alle DataLabels.get_Item(i).getPosition() der Wert val gilt).

**Rückgabe:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Stellt die Position der Datenbeschriftung dar. Lese-/Schreib [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Container von Datenbeschriftungen ist, ruft diese Eigenschaft den Standardwert der Position-Eigenschaft für neue Datenbeschriftungen in der DataLabelCollection ab bzw. legt ihn fest. Sie stellt die Position für die DataLabel-Objekte dar. Das Setzen dieser Eigenschaft mit einem Wert ändert diesen Wert ebenfalls für die Position-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. „DataLabels.getDefaultDataLabelFormat().setPosition(val)“, wodurch für alle DataLabels.get_Item(i).getPosition() der Wert val gilt).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Stellt das Anzeigeverhalten des Legenden-Schlüssels einer angegebenen Diagrammdatenbeschriftung dar. True, wenn der Legenden-Schlüssel sichtbar ist. Lese-/Schreib-Boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Container von Datenbeschriftungen ist, ruft diese Eigenschaft den Standardwert der ShowLegendKey-Eigenschaft für neue Datenbeschriftungen in der DataLabelCollection ab bzw. legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert ändert diesen Wert ebenfalls für die ShowLegendKey-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. „DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);“, wodurch für alle DataLabels.get_Item(i).getShowLegendKey() der Wert val gilt).

**Rückgabe:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Stellt das Anzeigeverhalten des Legenden-Schlüssels einer angegebenen Diagrammdatenbeschriftung dar. True, wenn der Legenden-Schlüssel sichtbar ist. Lese-/Schreib-Boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Container von Datenbeschriftungen ist, ruft diese Eigenschaft den Standardwert der ShowLegendKey-Eigenschaft für neue Datenbeschriftungen in der DataLabelCollection ab bzw. legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert ändert diesen Wert ebenfalls für die ShowLegendKey-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. „DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);“, wodurch für alle DataLabels.get_Item(i).getShowLegendKey() der Wert val gilt).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Stellt das Anzeigeverhalten des Prozentwerts einer angegebenen Diagrammdatenbeschriftung dar. True zeigt den Prozentwert an. False zum Ausblenden. Lese-/Schreib-Boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Container von Datenbeschriftungen ist, ruft diese Eigenschaft den Standardwert der ShowValue-Eigenschaft für neue Datenbeschriftungen in der DataLabelCollection ab bzw. legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert ändert diesen Wert ebenfalls für die ShowValue-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. „DataLabels.getDefaultDataLabelFormat().setShowValue(val);“, wodurch für alle DataLabels.get_Item(i).getShowValue() der Wert val gilt).

**Rückgabe:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Stellt das Anzeigeverhalten des Prozentwerts einer angegebenen Diagrammdatenbeschriftung dar. True zeigt den Prozentwert an. False zum Ausblenden. Lese-/Schreib-Boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Container von Datenbeschriftungen ist, ruft diese Eigenschaft den Standardwert der ShowValue-Eigenschaft für neue Datenbeschriftungen in der DataLabelCollection ab bzw. legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert ändert diesen Wert ebenfalls für die ShowValue-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. „DataLabels.getDefaultDataLabelFormat().setShowValue(val);“, wodurch für alle DataLabels.get_Item(i).getShowValue() der Wert val gilt).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Stellt das Anzeigeverhalten des Kategorienamens einer angegebenen Diagrammdatenbeschriftung dar. True, um den Kategorienamen für die Datenbeschriftungen in einem Diagramm anzuzeigen. False, um ihn auszublenden. Lese-/Schreib-Boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Container von Datenbeschriftungen ist, ruft diese Eigenschaft den Standardwert der ShowCategoryName-Eigenschaft für neue Datenbeschriftungen in der DataLabelCollection ab bzw. legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert ändert diesen Wert ebenfalls für die ShowCategoryName-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. „DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);“, wodurch für alle DataLabels.get_Item(i).getShowCategoryName() der Wert val gilt).

**Rückgabe:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Stellt das Anzeigeverhalten des Kategorienamens einer angegebenen Diagrammdatenbeschriftung dar. True, um den Kategorienamen für die Datenbeschriftungen in einem Diagramm anzuzeigen. False, um ihn auszublenden. Lese-/Schreib-Boolean.

--------------------
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Gibt einen Boolean zurück oder legt ihn fest, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm zu bestimmen. True zeigt den Seriennamen an. False blendet ihn aus. Lese-/Schreib-Boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**Rückgabewert:**  
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Gibt einen Boolean zurück oder legt ihn fest, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm zu bestimmen. True zeigt den Seriennamen an. False blendet ihn aus. Lese-/Schreib-Boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Stellt das Anzeigeverhalten des Prozentwerts einer Datenbeschriftung in einem angegebenen Diagramm dar. True zeigt den Prozentwert an. False blendet ihn aus. Lese-/Schreib-Boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Rückgabewert:**  
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Stellt das Anzeigeverhalten des Prozentwerts einer Datenbeschriftung in einem angegebenen Diagramm dar. True zeigt den Prozentwert an. False blendet ihn aus. Lese-/Schreib-Boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Stellt das Anzeigeverhalten des Blasengrößenwerts einer Datenbeschriftung in einem angegebenen Diagramm dar. True zeigt den Blasengrößenwert an. False blendet ihn aus. Lese-/Schreib-Boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**Rückgabewert:**  
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Stellt das Anzeigeverhalten des Blasengrößenwerts einer Datenbeschriftung in einem angegebenen Diagramm dar. True zeigt den Blasengrößenwert an. False blendet ihn aus. Lese-/Schreib-Boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Stellt das Anzeigeverhalten von Führungs-Linien einer Datenbeschriftung in einem angegebenen Diagramm dar. True zeigt die Führungs-Linien an. False blendet sie aus. Lese-/Schreib-Boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**Rückgabewert:**  
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Stellt das Anzeigeverhalten von Führungs-Linien einer Datenbeschriftung in einem angegebenen Diagramm dar. True zeigt die Führungs-Linien an. False blendet sie aus. Lese-/Schreib-Boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

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

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Rückgabewert:**  
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Bestimmt, ob die Datenbeschriftung eines angegebenen Diagramms als Daten-Callout oder als Datenbeschriftung angezeigt wird.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Stellt das Anzeigeverhalten des Zellwerts einer Datenbeschriftung in einem angegebenen Diagramm dar. True zeigt den Zellwert an. False blendet ihn aus. Lese-/Schreib-Boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Rückgabewert:**  
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Stellt das Anzeigeverhalten des Zellwerts einer Datenbeschriftung in einem angegebenen Diagramm dar. True zeigt den Zellwert an. False blendet ihn aus. Lese-/Schreib-Boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Legt einen Variant fest oder gibt ihn zurück, der das Trennzeichen für die Datenbeschriftungen in einem Diagramm darstellt. Lese-/Schreib-String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).

**Rückgabewert:**  
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Legt einen Variant fest oder gibt ihn zurück, der das Trennzeichen für die Datenbeschriftungen in einem Diagramm darstellt. Lese-/Schreib-String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).
**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |