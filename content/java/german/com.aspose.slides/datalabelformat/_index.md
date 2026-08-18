---
title: DataLabelFormat
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Formatierungsoptionen für Datenbeschriftungen dar.
type: docs
url: /de/com.aspose.slides/datalabelformat/
---
**Vererbung:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**  
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Stellt Formatierungsoptionen für DataLabel bereit.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Lese/Schreib-boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Lese/Schreib-boolean. |
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
| [getShowSeriesName()](#getShowSeriesName--) | Gibt einen Boolean zurück oder setzt ihn, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen eines Diagramms festzulegen. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Gibt einen Boolean zurück oder setzt ihn, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen eines Diagramms festzulegen. |
| [getShowPercentage()](#getShowPercentage--) | Stellt das Anzeigeverhalten des Prozentwerts einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Stellt das Anzeigeverhalten des Prozentwerts einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Stellt das Anzeigeverhalten des Blasengrößenwerts einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Stellt das Anzeigeverhalten des Blasengrößenwerts einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Stellt das Anzeigeverhalten der Führungsleitungen einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Stellt das Anzeigeverhalten der Führungsleitungen einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Stellt das Anzeigeverhalten des Zellwerts einer angegebenen Diagrammdatenbeschriftung dar. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Stellt das Anzeigeverhalten des Zellwerts einer angegebenen Diagrammdatenbeschriftung dar. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Bestimmt, ob die Datenbeschriftung eines angegebenen Diagramms als Datencallout oder als Datenbeschriftung angezeigt wird. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Bestimmt, ob die Datenbeschriftung eines angegebenen Diagramms als Datencallout oder als Datenbeschriftung angezeigt wird. |
| [getSeparator()](#getSeparator--) | Setzt oder gibt eine Variant zurück, die das Trennzeichen für die Datenbeschriftungen eines Diagramms darstellt. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Setzt oder gibt eine Variant zurück, die das Trennzeichen für die Datenbeschriftungen eines Diagramms darstellt. |
| [getTextFormat()](#getTextFormat--) | Gibt das Diagramm-Textformat zurück. |
| [getChart()](#getChart--) | Gibt das Diagramm zurück. |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Nur lesend long.

**Rückgabe:**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


Lese/Schreib-boolean.

--------------------

Wenn das übergeordnete Objekt dieses DataLabelFormat ein DataLabelCollection von Datenbeschriftungen ist, dann gibt diese Eigenschaft den Standardwert der IsNumberFormatLinkedToSource-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection zurück oder setzt ihn. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert auch für die IsNumberFormatLinkedToSource-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" führt dazu, dass für alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() der Wert gleich val ist).

**Rückgabe:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


Lese/Schreib-boolean.

--------------------

Wenn das übergeordnete Objekt dieses DataLabelFormat ein DataLabelCollection von Datenbeschriftungen ist, dann gibt diese Eigenschaft den Standardwert der IsNumberFormatLinkedToSource-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection zurück oder setzt ihn. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert auch für die IsNumberFormatLinkedToSource-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" führt dazu, dass für alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() der Wert gleich val ist).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Lese/Schreib-String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Wenn das übergeordnete Objekt dieses DataLabelFormat ein DataLabelCollection von Datenbeschriftungen ist, dann gibt diese Eigenschaft den Standardwert der NumberFormat-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection zurück oder setzt ihn. Wird diese Eigenschaft mit einem Wert gesetzt, so wird dieser Wert ebenfalls für die NumberFormat-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection gesetzt (z. B. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" führt dazu, dass für alle DataLabels.get_Item(i).getNumberFormat() der Wert gleich val ist).

**Rückgabe:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Lese/Schreib-String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Wenn das übergeordnete Objekt dieses DataLabelFormat ein DataLabelCollection von Datenbeschriftungen ist, dann gibt diese Eigenschaft den Standardwert der NumberFormat-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection zurück oder setzt ihn. Wird diese Eigenschaft mit einem Wert gesetzt, so wird dieser Wert ebenfalls für die NumberFormat-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection gesetzt (z. B. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" führt dazu, dass für alle DataLabels.get_Item(i).getNumberFormat() der Wert gleich val ist).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Stellt das Format der Datenbeschriftung dar. Nur lesend [IFormat](../../com.aspose.slides/iformat).

--------------------

Wenn das übergeordnete Objekt dieses DataLabelFormat ein DataLabelCollection von Datenbeschriftungen ist, dann stellt diese Eigenschaft das Standardformat für die neuen Datenbeschriftungen in der DataLabelCollection dar.

**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```


Stellt die Position der Datenbeschriftung dar. Lese/Schreib [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Wenn das übergeordnete Objekt dieses DataLabelFormat ein DataLabelCollection von Datenbeschriftungen ist, dann gibt diese Eigenschaft den Standardwert der Position-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection zurück oder setzt ihn. Sie stellt die Position für die DataLabel-Objekte dar. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert auch für die Position-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" führt dazu, dass für alle DataLabels.get_Item(i).getPosition() der Wert gleich val ist).

**Rückgabe:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Stellt die Position der Datenbeschriftung dar. Lese/Schreib [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Wenn das übergeordnete Objekt dieses DataLabelFormat ein DataLabelCollection von Datenbeschriftungen ist, dann gibt diese Eigenschaft den Standardwert der Position-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection zurück oder setzt ihn. Sie stellt die Position für die DataLabel-Objekte dar. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert auch für die Position-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" führt dazu, dass für alle DataLabels.get_Item(i).getPosition() der Wert gleich val ist).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```


Stellt das Anzeigeverhalten des Legenden-Schlüssels einer angegebenen Diagrammdatenbeschriftung dar. True, wenn der Legenden-Schlüssel sichtbar ist. Lese/Schreib-boolean.

--------------------

Wenn das übergeordnete Objekt dieses DataLabelFormat ein DataLabelCollection von Datenbeschriftungen ist, dann gibt diese Eigenschaft den Standardwert der ShowLegendKey-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection zurück oder setzt ihn. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert auch für die ShowLegendKey-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" führt dazu, dass für alle DataLabels.get_Item(i).getShowLegendKey() der Wert gleich val ist).

**Rückgabe:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```


Stellt das Anzeigeverhalten des Legenden-Schlüssels einer angegebenen Diagrammdatenbeschriftung dar. True, wenn der Legenden-Schlüssel sichtbar ist. Lese/Schreib-boolean.

--------------------

Wenn das übergeordnete Objekt dieses DataLabelFormat ein DataLabelCollection von Datenbeschriftungen ist, dann gibt diese Eigenschaft den Standardwert der ShowLegendKey-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection zurück oder setzt ihn. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert auch für die ShowLegendKey-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" führt dazu, dass für alle DataLabels.get_Item(i).getShowLegendKey() der Wert gleich val ist).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```


Stellt das Anzeigeverhalten des Prozentwerts einer angegebenen Diagrammdatenbeschriftung dar. True, wenn der Prozentwert angezeigt wird. False, um ihn zu verbergen. Lese/Schreib-boolean.

--------------------

Wenn das übergeordnete Objekt dieses DataLabelFormat ein DataLabelCollection von Datenbeschriftungen ist, dann gibt diese Eigenschaft den Standardwert der ShowValue-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection zurück oder setzt ihn. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert auch für die ShowValue-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" führt dazu, dass für alle DataLabels.get_Item(i).getShowValue() der Wert gleich val ist).

**Rückgabe:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```


Stellt das Anzeigeverhalten des Prozentwerts einer angegebenen Diagrammdatenbeschriftung dar. True, wenn der Prozentwert angezeigt wird. False, um ihn zu verbergen. Lese/Schreib-boolean.

--------------------

Wenn das übergeordnete Objekt dieses DataLabelFormat ein DataLabelCollection von Datenbeschriftungen ist, dann gibt diese Eigenschaft den Standardwert der ShowValue-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection zurück oder setzt ihn. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert auch für die ShowValue-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" führt dazu, dass für alle DataLabels.get_Item(i).getShowValue() der Wert gleich val ist).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```


Stellt das Anzeigeverhalten des Kategorienamens einer angegebenen Diagrammdatenbeschriftung dar. True, um den Kategorienamen für die Datenbeschriftungen eines Diagramms anzuzeigen. False, um ihn zu verbergen. Lese/Schreib-boolean.

--------------------

Wenn das übergeordnete Objekt dieses DataLabelFormat ein DataLabelCollection von Datenbeschriftungen ist, dann gibt diese Eigenschaft den Standardwert der ShowCategoryName-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection zurück oder setzt ihn. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert auch für die ShowCategoryName-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (z. B. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" führt dazu, dass für alle DataLabels.get_Item(i).getShowCategoryName() der Wert gleich val ist).

**Rückgabe:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```


Stellt das Anzeigeverhalten des Kategorienamens einer angegebenen Diagrammdatenbeschriftung dar. True, um den Kategorienamen für die Datenbeschriftungen eines Diagramms anzuzeigen. False, um ihn zu verbergen. Lese/Schreib-boolean.

--------------------
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Gibt einen Boolean zurück oder legt ihn fest, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm zu bestimmen. True zum Anzeigen des Seriennamens. False zum Ausblenden. Lese-/Schreib-boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**Rückgabewert:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Gibt einen Boolean zurück oder legt ihn fest, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm zu bestimmen. True zum Anzeigen des Seriennamens. False zum Ausblenden. Lese-/Schreib-boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Stellt das Anzeigeverhalten des Prozentwerts einer Datenbeschriftung in einem Diagramm dar. True zeigt den Prozentwert an. False blendet ihn aus. Lese-/Schreib-boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Rückgabewert:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Stellt das Anzeigeverhalten des Prozentwerts einer Datenbeschriftung in einem Diagramm dar. True zeigt den Prozentwert an. False blendet ihn aus. Lese-/Schreib-boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Stellt das Anzeigeverhalten der Blasengröße einer Datenbeschriftung in einem Diagramm dar. True zeigt die Blasengröße an. False blendet sie aus. Lese-/Schreib-boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**Rückgabewert:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Stellt das Anzeigeverhalten der Blasengröße einer Datenbeschriftung in einem Diagramm dar. True zeigt die Blasengröße an. False blendet sie aus. Lese-/Schreib-boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Stellt das Anzeigeverhalten der Führungslinien einer Datenbeschriftung in einem Diagramm dar. True zeigt die Führungslinien an. False blendet sie aus. Lese-/Schreib-boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**Rückgabewert:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Stellt das Anzeigeverhalten der Führungslinien einer Datenbeschriftung in einem Diagramm dar. True zeigt die Führungslinien an. False blendet sie aus. Lese-/Schreib-boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Stellt das Anzeigeverhalten des Zellenwerts einer Datenbeschriftung in einem Diagramm dar. True zeigt den Zellenwert an. False blendet ihn aus. Lese-/Schreib-boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Rückgabewert:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Stellt das Anzeigeverhalten des Zellenwerts einer Datenbeschriftung in einem Diagramm dar. True zeigt den Zellenwert an. False blendet ihn aus. Lese-/Schreib-boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Bestimmt, ob die Datenbeschriftung eines Diagramms als Daten-Callout oder als Datenbeschriftung angezeigt wird.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Rückgabewert:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Bestimmt, ob die Datenbeschriftung eines Diagramms als Daten-Callout oder als Datenbeschriftung angezeigt wird.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Setzt oder gibt ein Variant zurück, das das Trennzeichen für die Datenbeschriftungen in einem Diagramm darstellt. Lese-/Schreib-String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).

**Rückgabewert:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Setzt oder gibt ein Variant zurück, das das Trennzeichen für die Datenbeschriftungen in einem Diagramm darstellt. Lese-/Schreib-String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).
**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Gibt das Textformat des Diagramms zurück. Nur lesbar [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Rückgabe:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Gibt das Diagramm zurück. Nur lesbar [IChart](../../com.aspose.slides/ichart).

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart)