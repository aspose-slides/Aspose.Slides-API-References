---
title: DataLabelFormat
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt Formatierungsoptionen für DataLabel dar.
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

Stellt Formatierungsoptionen für DataLabel dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Lese-/Schreib- boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Lese-/Schreib- boolean. |
| [getNumberFormat()](#getNumberFormat--) | Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. |
| [getFormat()](#getFormat--) | Stellt das Format des Datenbeschriftungsfeldes dar. |
| [getPosition()](#getPosition--) | Stellt die Position der Datenbeschriftung dar. |
| [setPosition(int value)](#setPosition-int-) | Stellt die Position der Datenbeschriftung dar. |
| [getShowLegendKey()](#getShowLegendKey--) | Stellt das Anzeigeverhalten des Legenden-Schlüssels einer bestimmten Diagrammdatenbeschriftung dar. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Stellt das Anzeigeverhalten des Legenden-Schlüssels einer bestimmten Diagrammdatenbeschriftung dar. |
| [getShowValue()](#getShowValue--) | Stellt das Anzeigeverhalten des prozentualen Werts einer bestimmten Diagrammdatenbeschriftung dar. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Stellt das Anzeigeverhalten des prozentualen Werts einer bestimmten Diagrammdatenbeschriftung dar. |
| [getShowCategoryName()](#getShowCategoryName--) | Stellt das Anzeigeverhalten des Kategorienamens einer bestimmten Diagrammdatenbeschriftung dar. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Stellt das Anzeigeverhalten des Kategorienamens einer bestimmten Diagrammdatenbeschriftung dar. |
| [getShowSeriesName()](#getShowSeriesName--) | Gibt einen Boolean zurück oder legt ihn fest, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm zu bestimmen. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Gibt einen Boolean zurück oder legt ihn fest, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm zu bestimmen. |
| [getShowPercentage()](#getShowPercentage--) | Stellt das Anzeigeverhalten des prozentualen Werts einer bestimmten Diagrammdatenbeschriftung dar. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Stellt das Anzeigeverhalten des prozentualen Werts einer bestimmten Diagrammdatenbeschriftung dar. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Stellt das Anzeigeverhalten der Blasengrößenwerte einer bestimmten Diagrammdatenbeschriftung dar. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Stellt das Anzeigeverhalten der Blasengrößenwerte einer bestimmten Diagrammdatenbeschriftung dar. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Stellt das Anzeigeverhalten der Führungslinien einer bestimmten Diagrammdatenbeschriftung dar. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Stellt das Anzeigeverhalten der Führungslinien einer bestimmten Diagrammdatenbeschriftung dar. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Stellt das Anzeigeverhalten des Zellwerts einer bestimmten Diagrammdatenbeschriftung dar. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Stellt das Anzeigeverhalten des Zellwerts einer bestimmten Diagrammdatenbeschriftung dar. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Bestimmt, ob die Datenbeschriftung eines bestimmten Diagramms als Daten-Callout oder als Datenbeschriftung angezeigt wird. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Bestimmt, ob die Datenbeschriftung eines bestimmten Diagramms als Daten-Callout oder als Datenbeschriftung angezeigt wird. |
| [getSeparator()](#getSeparator--) | Legt einen Variant fest oder gibt ihn zurück, der das Trennzeichen für die Datenbeschriftungen in einem Diagramm darstellt. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Legt einen Variant fest oder gibt ihn zurück, der das Trennzeichen für die Datenbeschriftungen in einem Diagramm darstellt. |
| [getTextFormat()](#getTextFormat--) | Gibt das Diagramm-Textformat zurück. |
| [getChart()](#getChart--) | Gibt das Diagramm zurück. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Nur lesbar long.

**Rückgabe:**
long
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft IsNumberFormatLinkedToSource für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft IsNumberFormatLinkedToSource aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);“, sodass alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() den Wert val besitzen).

**Rückgabe:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft IsNumberFormatLinkedToSource für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft IsNumberFormatLinkedToSource aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);“, sodass alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() den Wert val besitzen).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Lese-/Schreib- String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft NumberFormat für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Wird diese Eigenschaft mit einem Wert gesetzt, wird derselbe Wert auch für die Eigenschaft NumberFormat aller Datenbeschriftungen in der DataLabelCollection-Sammlung gesetzt (z. B. „DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);“, wodurch alle DataLabels.get_Item(i).getNumberFormat() den Wert val erhalten).

**Rückgabe:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Lese-/Schreib- String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft NumberFormat für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Wird diese Eigenschaft mit einem Wert gesetzt, wird derselbe Wert auch für die Eigenschaft NumberFormat aller Datenbeschriftungen in der DataLabelCollection-Sammlung gesetzt (z. B. „DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);“, wodurch alle DataLabels.get_Item(i).getNumberFormat() den Wert val erhalten).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Stellt das Format der Datenbeschriftung dar. Nur lesbar [IFormat](../../com.aspose.slides/iformat).

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, stellt diese Eigenschaft das Standardformat für neue Datenbeschriftungen in der DataLabelCollection-Sammlung dar.

**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Stellt die Position der Datenbeschriftung dar. Lese-/Schreib- [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft Position für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Sie stellt die Position für die DataLabel-Objekte dar. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft Position aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setPosition(val);“, sodass alle DataLabels.get_Item(i).getPosition() den Wert val erhalten).

**Rückgabe:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Stellt die Position der Datenbeschriftung dar. Lese-/Schreib- [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft Position für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Sie stellt die Position für die DataLabel-Objekte dar. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft Position aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setPosition(val);“, sodass alle DataLabels.get_Item(i).getPosition() den Wert val erhalten).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```


Stellt das Anzeigeverhalten des Legenden-Schlüssels einer bestimmten Diagrammdatenbeschriftung dar. True, wenn der Legenden-Schlüssel sichtbar ist. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowLegendKey für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowLegendKey aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);“, sodass alle DataLabels.get_Item(i).getShowLegendKey() den Wert val besitzen).

**Rückgabe:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```


Stellt das Anzeigeverhalten des Legenden-Schlüssels einer bestimmten Diagrammdatenbeschriftung dar. True, wenn der Legenden-Schlüssel sichtbar ist. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowLegendKey für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowLegendKey aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);“, sodass alle DataLabels.get_Item(i).getShowLegendKey() den Wert val besitzen).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```


Stellt das Anzeigeverhalten des prozentualen Werts einer bestimmten Diagrammdatenbeschriftung dar. True, wenn der Prozentwert angezeigt wird. False, um ihn zu verbergen. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowValue für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowValue aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowValue(val);“, sodass alle DataLabels.get_Item(i).getShowValue() den Wert val besitzen).

**Rückgabe:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```


Stellt das Anzeigeverhalten des prozentualen Werts einer bestimmten Diagrammdatenbeschriftung dar. True, wenn der Prozentwert angezeigt wird. False, um ihn zu verbergen. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowValue für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowValue aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowValue(val);“, sodass alle DataLabels.get_Item(i).getShowValue() den Wert val besitzen).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```


Stellt das Anzeigeverhalten des Kategorienamens einer bestimmten Diagrammdatenbeschriftung dar. True, um den Kategorienamen anzuzeigen. False, um ihn zu verbergen. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowCategoryName für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowCategoryName aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);“, sodass alle DataLabels.get_Item(i).getShowCategoryName() den Wert val besitzen).

**Rückgabe:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```


Stellt das Anzeigeverhalten des Kategorienamens einer bestimmten Diagrammdatenbeschriftung dar. True, um den Kategorienamen anzuzeigen. False, um ihn zu verbergen. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowCategoryName für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowCategoryName aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);“, sodass alle DataLabels.get_Item(i).getShowCategoryName() den Wert val besitzen).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```


Gibt einen Boolean zurück oder legt ihn fest, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm zu bestimmen. True, um den Seriennamen anzuzeigen. False, um ihn zu verbergen. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowSeriesName für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowSeriesName aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);“, sodass alle DataLabels.get_Item(i).getShowSeriesName() den Wert val besitzen).

**Rückgabe:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```


Gibt einen Boolean zurück oder legt ihn fest, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm zu bestimmen. True, um den Seriennamen anzuzeigen. False, um ihn zu verbergen. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowSeriesName für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowSeriesName aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);“, sodass alle DataLabels.get_Item(i).getShowSeriesName() den Wert val besitzen).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```


Stellt das Anzeigeverhalten des prozentualen Werts einer bestimmten Diagrammdatenbeschriftung dar. True, wenn der Prozentwert angezeigt wird. False, um ihn zu verbergen. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowPercentage für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowPercentage aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);“, sodass alle DataLabels.get_Item(i).getShowPercentage() den Wert val besitzen).

**Rückgabe:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```


Stellt das Anzeigeverhalten des prozentualen Werts einer bestimmten Diagrammdatenbeschriftung dar. True, wenn der Prozentwert angezeigt wird. False, um ihn zu verbergen. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowPercentage für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowPercentage aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);“, sodass alle DataLabels.get_Item(i).getShowPercentage() den Wert val besitzen).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```


Stellt das Anzeigeverhalten der Blasengrößenwerte einer bestimmten Diagrammdatenbeschriftung dar. True, wenn die Blasengrößenwerte angezeigt werden. False, um sie zu verbergen. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowBubbleSize für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowBubbleSize aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);“, sodass alle DataLabels.get_Item(i).getShowBubbleSize() den Wert val besitzen).

**Rückgabe:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```


Stellt das Anzeigeverhalten der Blasengrößenwerte einer bestimmten Diagrammdatenbeschriftung dar. True, wenn die Blasengrößenwerte angezeigt werden. False, um sie zu verbergen. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowBubbleSize für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowBubbleSize aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);“, sodass alle DataLabels.get_Item(i).getShowBubbleSize() den Wert val besitzen).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```


Stellt das Anzeigeverhalten der Führungslinien einer bestimmten Diagrammdatenbeschriftung dar. True, wenn die Führungslinien angezeigt werden. False, um sie zu verbergen. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowLeaderLines für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowLeaderLines aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);“, sodass alle DataLabels.get_Item(i).getShowLeaderLines() den Wert val besitzen).

**Rückgabe:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```


Stellt das Anzeigeverhalten der Führungslinien einer bestimmten Diagrammdatenbeschriftung dar. True, wenn die Führungslinien angezeigt werden. False, um sie zu verbergen. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowLeaderLines für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowLeaderLines aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);“, sodass alle DataLabels.get_Item(i).getShowLeaderLines() den Wert val besitzen).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```


Stellt das Anzeigeverhalten des Zellwerts einer bestimmten Diagrammdatenbeschriftung dar. True, wenn der Zellwert angezeigt wird. False, um ihn zu verbergen. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowLabelValueFromCell für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowLabelValueFromCell aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);“, sodass alle DataLabels.get_Item(i).getShowLabelValueFromCell() den Wert val besitzen).

**Rückgabe:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```


Stellt das Anzeigeverhalten des Zellwerts einer bestimmten Diagrammdatenbeschriftung dar. True, wenn der Zellwert angezeigt wird. False, um ihn zu verbergen. Lese-/Schreib- boolean.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowLabelValueFromCell für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowLabelValueFromCell aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);“, sodass alle DataLabels.get_Item(i).getShowLabelValueFromCell() den Wert val besitzen).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```


Bestimmt, ob die Datenbeschriftung eines bestimmten Diagramms als Daten-Callout oder als Datenbeschriftung angezeigt wird.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowLabelAsDataCallout für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowLabelAsDataCallout aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);“, sodass alle DataLabels.get_Item(i).getShowLabelAsDataCallout() den Wert val besitzen).

**Rückgabe:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```


Bestimmt, ob die Datenbeschriftung eines bestimmten Diagramms als Daten-Callout oder als Datenbeschriftung angezeigt wird.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft ShowLabelAsDataCallout für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft ShowLabelAsDataCallout aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);“, sodass alle DataLabels.get_Item(i).getShowLabelAsDataCallout() den Wert val besitzen).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Setzt oder gibt ein Variant zurück, das den Trennzeichenwert für die Datenbeschriftungen in einem Diagramm darstellt. Lese-/Schreib- String.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft Separator für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft Separator aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setSeparator(val);“, sodass alle DataLabels.get_Item(i).getSeparator() den Wert val besitzen).

**Rückgabe:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Setzt oder gibt ein Variant zurück, das den Trennzeichenwert für die Datenbeschriftungen in einem Diagramm darstellt. Lese-/Schreib- String.

--------------------

Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, gibt diese Eigenschaft den Standardwert der Eigenschaft Separator für neue Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die Eigenschaft Separator aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. „DataLabels.getDefaultDataLabelFormat().setSeparator(val);“, sodass alle DataLabels.get_Item(i).getSeparator() den Wert val besitzen).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Gibt das Diagramm-Textformat zurück. Nur lesbar [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Rückgabe:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Gibt das Diagramm zurück. Nur lesbar [IChart](../../com.aspose.slides/ichart).

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart)