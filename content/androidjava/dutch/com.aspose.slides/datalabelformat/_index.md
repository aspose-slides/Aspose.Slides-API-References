---
title: DataLabelFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt opmaakopties voor DataLabel voor.
type: docs
url: /nl/com.aspose.slides/datalabelformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Stelt opmaakopties voor DataLabel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Lezen/schrijven boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Lezen/schrijven boolean. |
| [getNumberFormat()](#getNumberFormat--) | Stelt de opmaakreeks voor het DataLabels-object voor. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Stelt de opmaakreeks voor het DataLabels-object voor. |
| [getFormat()](#getFormat--) | Stelt het formaat van het gegevenslabel voor. |
| [getPosition()](#getPosition--) | Stelt de positie van het gegevenslabel voor. |
| [setPosition(int value)](#setPosition-int-) | Stelt de positie van het gegevenslabel voor. |
| [getShowLegendKey()](#getShowLegendKey--) | Stelt het weergavegedrag van de legende-sleutel van het gegevenslabel van een opgegeven grafiek voor. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Stelt het weergavegedrag van de legende-sleutel van het gegevenslabel van een opgegeven grafiek voor. |
| [getShowValue()](#getShowValue--) | Stelt het weergavegedrag van de procentwaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Stelt het weergavegedrag van de procentwaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [getShowCategoryName()](#getShowCategoryName--) | Stelt het weergavegedrag van de categorienaam van het gegevenslabel van een opgegeven grafiek voor. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Stelt het weergavegedrag van de categorienaam van het gegevenslabel van een opgegeven grafiek voor. |
| [getShowSeriesName()](#getShowSeriesName--) | Retourneert of stelt een Boolean in om het weergavegedrag van de serienaam voor de gegevenslabels op een grafiek aan te geven. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Retourneert of stelt een Boolean in om het weergavegedrag van de serienaam voor de gegevenslabels op een grafiek aan te geven. |
| [getShowPercentage()](#getShowPercentage--) | Stelt het weergavegedrag van de procentwaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Stelt het weergavegedrag van de procentwaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Stelt het weergavegedrag van de bubbelgroottewaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Stelt het weergavegedrag van de bubbelgroottewaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Stelt het weergavegedrag van de leidingslijnen van het gegevenslabel van een opgegeven grafiek voor. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Stelt het weergavegedrag van de leidingslijnen van het gegevenslabel van een opgegeven grafiek voor. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Stelt het weergavegedrag van de celwaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Stelt het weergavegedrag van de celwaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Bepaalt of het gegevenslabel van een opgegeven grafiek wordt weergegeven als data-callout of als gegevenslabel. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Bepaalt of het gegevenslabel van een opgegeven grafiek wordt weergegeven als data-callout of als gegevenslabel. |
| [getSeparator()](#getSeparator--) | Stelt in of retourneert een Variant die de scheidingsteken voor de gegevenslabels op een grafiek vertegenwoordigt. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Stelt in of retourneert een Variant die de scheidingsteken voor de gegevenslabels op een grafiek vertegenwoordigt. |
| [getTextFormat()](#getTextFormat--) | Retourneert tekstopmaak van de grafiek. |
| [getChart()](#getChart--) | Retourneert de grafiek. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versie. Alleen-lezen long.

**Retourneert:**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de IsNumberFormatLinkedToSource-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de IsNumberFormatLinkedToSource-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" zorgt ervoor dat alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() gelijk is aan val).

**Retourneert:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de IsNumberFormatLinkedToSource-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de IsNumberFormatLinkedToSource-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" zorgt ervoor dat alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Stelt de opmaakreeks voor het DataLabels-object voor. Lezen/schrijven String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de NumberFormat-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Wanneer deze eigenschap met een waarde wordt ingesteld, wordt diezelfde waarde ook ingesteld voor de NumberFormat-eigenschap van alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" zorgt dat alle DataLabels.get_Item(i).getNumberFormat() gelijk is aan val).

**Retourneert:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Stelt de opmaakreeks voor het DataLabels-object voor. Lezen/schrijven String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de NumberFormat-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Wanneer deze eigenschap met een waarde wordt ingesteld, wordt diezelfde waarde ook ingesteld voor de NumberFormat-eigenschap van alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" zorgt dat alle DataLabels.get_Item(i).getNumberFormat() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Stelt het formaat van het gegevenslabel voor. Alleen-lezen [IFormat](../../com.aspose.slides/iformat).

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan vertegenwoordigt deze eigenschap het standaardformaat voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling.

**Retourneert:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Stelt de positie van het gegevenslabel voor. Lezen/schrijven [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de Position-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stelt de positie in voor de DataLabel-objecten. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de Position-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" zorgt dat alle DataLabels.get_Item(i).getPosition() gelijk is aan val).

**Retourneert:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Stelt de positie van het gegevenslabel voor. Lezen/schrijven [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de Position-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stelt de positie in voor de DataLabel-objecten. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de Position-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" zorgt dat alle DataLabels.get_Item(i).getPosition() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Stelt het weergavegedrag van de legende-sleutel van het gegevenslabel van een opgegeven grafiek voor. True if the data label legend key is visible. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLegendKey-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowLegendKey-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" zorgt dat alle DataLabels.get_Item(i).getShowLegendKey() gelijk is aan val).

**Retourneert:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Stelt het weergavegedrag van de legende-sleutel van het gegevenslabel van een opgegeven grafiek voor. True if the data label legend key is visible. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLegendKey-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowLegendKey-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" zorgt dat alle DataLabels.get_Item(i).getShowLegendKey() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Stelt het weergavegedrag van de procentwaarde van het gegevenslabel van een opgegeven grafiek voor. True displays the percentage value. False to hide. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowValue-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowValue-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" zorgt dat alle DataLabels.get_Item(i).getShowValue() gelijk is aan val).

**Retourneert:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Stelt het weergavegedrag van de procentwaarde van het gegevenslabel van een opgegeven grafiek voor. True displays the percentage value. False to hide. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowValue-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowValue-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" zorgt dat alle DataLabels.get_Item(i).getShowValue() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Stelt het weergavegedrag van de categorienaam van het gegevenslabel van een opgegeven grafiek voor. True to display the category name for the data labels on a chart. False to hide. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowCategoryName-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowCategoryName-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" zorgt dat alle DataLabels.get_Item(i).getShowCategoryName() gelijk is aan val).

**Retourneert:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Stelt het weergavegedrag van de categorienaam van het gegevenslabel van een opgegeven grafiek voor. True to display the category name for the data labels on a chart. False to hide. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowCategoryName-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowCategoryName-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" zorgt dat alle DataLabels.get_Item(i).getShowCategoryName() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Retourneert of stelt een Boolean in om het weergavegedrag van de serienaam voor de gegevenslabels op een grafiek aan te geven. True to show the series name. False to hide. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowSeriesName-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowSeriesName-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" zorgt dat alle DataLabels.get_Item(i).getShowSeriesName() gelijk is aan val).

**Retourneert:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Retourneert of stelt een Boolean in om het weergavegedrag van de serienaam voor de gegevenslabels op een grafiek aan te geven. True to show the series name. False to hide. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowSeriesName-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowSeriesName-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" zorgt dat alle DataLabels.get_Item(i).getShowSeriesName() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Stelt het weergavegedrag van de procentwaarde van het gegevenslabel van een opgegeven grafiek voor. True displays the percentage value. False to hide. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowPercentage-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowPercentage-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" zorgt dat alle DataLabels.get_Item(i).getShowPercentage() gelijk is aan val).

**Retourneert:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Stelt het weergavegedrag van de procentwaarde van het gegevenslabel van een opgegeven grafiek voor. True displays the percentage value. False to hide. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowPercentage-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowPercentage-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" zorgt dat alle DataLabels.get_Item(i).getShowPercentage() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Stelt het weergavegedrag van de bubbelgroottewaarde van het gegevenslabel van een opgegeven grafiek voor. True displays the bubble size value. False to hide. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowBubbleSize-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowBubbleSize-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" zorgt dat alle DataLabels.get_Item(i).getShowBubbleSize() gelijk is aan val).

**Retourneert:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Stelt het weergavegedrag van de bubbelgroottewaarde van het gegevenslabel van een opgegeven grafiek voor. True displays the bubble size value. False to hide. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowBubbleSize-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowBubbleSize-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" zorgt dat alle DataLabels.get_Item(i).getShowBubbleSize() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Stelt het weergavegedrag van de leidingslijnen van het gegevenslabel van een opgegeven grafiek voor. True displays the leader lines. False to hide. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLeaderLines-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowLeaderLines-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" zorgt dat alle DataLabels.get_Item(i).getShowLeaderLines() gelijk is aan val).

**Retourneert:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Stelt het weergavegedrag van de leidingslijnen van het gegevenslabel van een opgegeven grafiek voor. True displays the leader lines. False to hide. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLeaderLines-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowLeaderLines-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" zorgt dat alle DataLabels.get_Item(i).getShowLeaderLines() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Stelt het weergavegedrag van de celwaarde van het gegevenslabel van een opgegeven grafiek voor. True displays cell value. False to hide. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLabelValueFromCell-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowLabelValueFromCell-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" zorgt dat alle DataLabels.get_Item(i).getShowLabelValueFromCell() gelijk is aan val).

**Retourneert:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Stelt het weergavegedrag van de celwaarde van het gegevenslabel van een opgegeven grafiek voor. True displays cell value. False to hide. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLabelValueFromCell-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowLabelValueFromCell-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" zorgt dat alle DataLabels.get_Item(i).getShowLabelValueFromCell() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Bepaalt of het gegevenslabel van een opgegeven grafiek wordt weergegeven als data-callout of als gegevenslabel.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLabelAsDataCallout-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowLabelAsDataCallout-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" zorgt dat alle DataLabels.get_Item(i).getShowLabelAsDataCallout() gelijk is aan val).

**Retourneert:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Bepaalt of het gegevenslabel van een opgegeven grafiek wordt weergegeven als data-callout of als gegevenslabel.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLabelAsDataCallout-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowLabelAsDataCallout-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" zorgt dat alle DataLabels.get_Item(i).getShowLabelAsDataCallout() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Stelt in of retourneert een Variant die de scheidingsteken voor de gegevenslabels op een grafiek vertegenwoordigt. Lezen/schrijven String.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de Separator-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de Separator-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" zorgt dat alle DataLabels.get_Item(i).getSeparator() gelijk is aan val).

**Retourneert:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Stelt in of retourneert een Variant die de scheidingsteken voor de gegevenslabels op een grafiek vertegenwoordigt. Lezen/schrijven String.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de Separator-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de Separator-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" zorgt dat alle DataLabels.get_Item(i).getSeparator() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Retourneert tekstopmaak van de grafiek. Alleen-lezen [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retourneert:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

Retourneert de grafiek. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Retourneert:**
[IChart](../../com.aspose.slides/ichart)