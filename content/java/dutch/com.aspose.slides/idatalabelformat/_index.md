---
title: IDataLabelFormat
second_title: Aspose.Slides voor Java API-referentie
description: Geeft de opmaakopties voor DataLabel weer.
type: docs
url: /nl/com.aspose.slides/idatalabelformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Stelt de opmaakopties voor DataLabel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Lezen/schrijven boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Lezen/schrijven boolean. |
| [getNumberFormat()](#getNumberFormat--) | Stelt de opmaaktekenreeks voor het DataLabels-object voor. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Stelt de opmaaktekenreeks voor het DataLabels-object voor. |
| [getFormat()](#getFormat--) | Stelt het formaat van het gegevenslabel voor. |
| [getPosition()](#getPosition--) | Stelt de positie van het gegevenslabel voor. |
| [setPosition(int value)](#setPosition-int-) | Stelt de positie van het gegevenslabel voor. |
| [getShowLegendKey()](#getShowLegendKey--) | Stelt het weergavegedrag van de legenda-sleutel van het gegevenslabel van een opgegeven grafiek voor. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Stelt het weergavegedrag van de legenda-sleutel van het gegevenslabel van een opgegeven grafiek voor. |
| [getShowValue()](#getShowValue--) | Stelt het weergavegedrag van de percentagewaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Stelt het weergavegedrag van de percentagewaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [getShowCategoryName()](#getShowCategoryName--) | Stelt het weergavegedrag van de categorienaam van het gegevenslabel van een opgegeven grafiek voor. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Stelt het weergavegedrag van de categorienaam van het gegevenslabel van een opgegeven grafiek voor. |
| [getShowSeriesName()](#getShowSeriesName--) | Geeft een Boolean terug of stelt deze in om het weergavegedrag van de serienaam voor de gegevenslabels op een grafiek aan te geven. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Geeft een Boolean terug of stelt deze in om het weergavegedrag van de serienaam voor de gegevenslabels op een grafiek aan te geven. |
| [getShowPercentage()](#getShowPercentage--) | Stelt het weergavegedrag van de percentagewaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Stelt het weergavegedrag van de percentagewaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Stelt het weergavegedrag van de bubbelgroottewaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Stelt het weergavegedrag van de bubbelgroottewaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Stelt het weergavegedrag van de leidende lijnen van het gegevenslabel van een opgegeven grafiek voor. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Stelt het weergavegedrag van de leidende lijnen van het gegevenslabel van een opgegeven grafiek voor. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Bepaalt of het gegevenslabel van een opgegeven grafiek wordt weergegeven als data-aanroep of als gegevenslabel. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Bepaalt of het gegevenslabel van een opgegeven grafiek wordt weergegeven als data-aanroep of als gegevenslabel. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Stelt het weergavegedrag van de celwaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Stelt het weergavegedrag van de celwaarde van het gegevenslabel van een opgegeven grafiek voor. |
| [getSeparator()](#getSeparator--) | Stelt een Variant in of geeft deze terug die de scheidingsteken vertegenwoordigt die wordt gebruikt voor de gegevenslabels op een grafiek. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Stelt een Variant in of geeft deze terug die de scheidingsteken vertegenwoordigt die wordt gebruikt voor de gegevenslabels op een grafiek. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, krijgt deze eigenschap of stelt deze de standaardwaarde van de IsNumberFormatLinkedToSource-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de IsNumberFormatLinkedToSource-eigenschap van alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" waardoor alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() gelijk is aan val).

**Retourneert:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, krijgt deze eigenschap of stelt deze de standaardwaarde van de IsNumberFormatLinkedToSource-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de IsNumberFormatLinkedToSource-eigenschap van alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" waardoor alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Stelt de opmaaktekenreeks voor het DataLabels-object voor. Lezen/schrijven String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, krijgt deze eigenschap of stelt deze de standaardwaarde van de NumberFormat-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Wanneer deze eigenschap wordt ingesteld met een waarde, wordt diezelfde waarde ook ingesteld voor de NumberFormat-eigenschap van alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" waardoor alle DataLabels.get_Item(i).getNumberFormat() gelijk is aan val).

**Retourneert:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Stelt de opmaaktekenreeks voor het DataLabels-object voor. Lezen/schrijven String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, krijgt deze eigenschap of stelt deze de standaardwaarde van de NumberFormat-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Wanneer deze eigenschap wordt ingesteld met een waarde, wordt diezelfde waarde ook ingesteld voor de NumberFormat-eigenschap van alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" waardoor alle DataLabels.get_Item(i).getNumberFormat() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Stelt het formaat van het gegevenslabel voor. Alleen-lezen [IFormat](../../com.aspose.slides/iformat).

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, vertegenwoordigt deze eigenschap het standaardformaat voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling.

**Retourneert:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Stelt de positie van het gegevenslabel voor. Lezen/schrijven [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, krijgt deze eigenschap of stelt deze de standaardwaarde van de Position-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stelt de positie in voor de DataLabel-objecten. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de Position-eigenschap van alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" waardoor alle DataLabels.get_Item(i).getPosition() gelijk is aan val).

**Retourneert:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Stelt de positie van het gegevenslabel voor. Lezen/schrijven [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, krijgt deze eigenschap of stelt deze de standaardwaarde van de Position-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stelt de positie in voor de DataLabel-objecten. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de Position-eigenschap van alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" waardoor alle DataLabels.get_Item(i).getPosition() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Stelt het weergavegedrag van de legenda-sleutel van het gegevenslabel van een opgegeven grafiek voor. Waar als de legenda-sleutel van het gegevenslabel zichtbaar is. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowLegendKey-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLegendKey-eigenschap van alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" waardoor alle DataLabels.get_Item(i).getShowLegendKey() gelijk is aan val).

**Retourneert:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Stelt het weergavegedrag van de legenda-sleutel van het gegevenslabel van een opgegeven grafiek voor. Waar als de legenda-sleutel van het gegevenslabel zichtbaar is. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowLegendKey-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLegendKey-eigenschap van alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" waardoor alle DataLabels.get_Item(i).getShowLegendKey() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Stelt het weergavegedrag van de percentagewaarde van het gegevenslabel van een opgegeven grafiek voor. Waar als de percentagewaarde wordt weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowValue-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowValue-eigenschap van alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" waardoor alle DataLabels.get_Item(i).getShowValue() gelijk is aan val).

**Retourneert:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Stelt het weergavegedrag van de percentagewaarde van het gegevenslabel van een opgegeven grafiek voor. Waar als de percentagewaarde wordt weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowValue-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowValue-eigenschap van alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" waardoor alle DataLabels.get_Item(i).getShowValue() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Stelt het weergavegedrag van de categorienaam van het gegevenslabel van een opgegeven grafiek voor. Waar als de categorienaam voor de gegevenslabels op een grafiek wordt weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowCategoryName-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowCategoryName-eigenschap van alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" waardoor alle DataLabels.get_Item(i).getShowCategoryName() gelijk is aan val).

**Retourneert:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Stelt het weergavegedrag van de categorienaam van het gegevenslabel van een opgegeven grafiek voor. Waar als de categorienaam voor de gegevenslabels op een grafiek wordt weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------
Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowCategoryName-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stel deze eigenschap in met een waarde, dan wordt die waarde ook ingesteld op de ShowCategoryName-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" waardoor alle DataLabels.get_Item(i).getShowCategoryName() gelijk aan val is).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Retourneert of stelt een Boolean in om het weergavegedrag van de serienaam voor de gegevenslabels in een grafiek aan te geven. True om de serienaam weer te geven. False om te verbergen. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowSeriesName-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stel deze eigenschap in met een waarde, dan wordt die waarde ook ingesteld op de ShowSeriesName-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" waardoor alle DataLabels.get_Item(i).getShowSeriesName() gelijk aan val is).

**Retour:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Retourneert of stelt een Boolean in om het weergavegedrag van de serienaam voor de gegevenslabels in een grafiek aan te geven. True om de serienaam weer te geven. False om te verbergen. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowSeriesName-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stel deze eigenschap in met een waarde, dan wordt die waarde ook ingesteld op de ShowSeriesName-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" waardoor alle DataLabels.get_Item(i).getShowSeriesName() gelijk aan val is).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Geeft het weergavegedrag van het percentage-waarde van een gegevenslabel in een opgegeven grafiek weer. True toont de percentagetekst. False verbergt deze. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowPercentage-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stel deze eigenschap in met een waarde, dan wordt die waarde ook ingesteld op de ShowPercentage-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" waardoor alle DataLabels.get_Item(i).getShowPercentage() gelijk aan val is).

**Retour:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Geeft het weergavegedrag van het percentage-waarde van een gegevenslabel in een opgegeven grafiek weer. True toont de percentagetekst. False verbergt deze. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowPercentage-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stel deze eigenschap in met een waarde, dan wordt die waarde ook ingesteld op de ShowPercentage-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" waardoor alle DataLabels.get_Item(i).getShowPercentage() gelijk aan val is).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Geeft het weergavegedrag van de bubbelgrootte-waarde van een gegevenslabel in een opgegeven grafiek weer. True toont de bubbelgrootte. False verbergt deze. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowBubbleSize-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stel deze eigenschap in met een waarde, dan wordt die waarde ook ingesteld op de ShowBubbleSize-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" waardoor alle DataLabels.get_Item(i).getShowBubbleSize() gelijk aan val is).

**Retour:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Geeft het weergavegedrag van de bubbelgrootte-waarde van een gegevenslabel in een opgegeven grafiek weer. True toont de bubbelgrootte. False verbergt deze. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowBubbleSize-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stel deze eigenschap in met een waarde, dan wordt die waarde ook ingesteld op de ShowBubbleSize-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" waardoor alle DataLabels.get_Item(i).getShowBubbleSize() gelijk aan val is).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Geeft het weergavegedrag van de hulplijnen van een gegevenslabel in een opgegeven grafiek weer. True toont de hulplijnen. False verbergt deze. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLeaderLines-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stel deze eigenschap in met een waarde, dan wordt die waarde ook ingesteld op de ShowLeaderLines-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" waardoor alle DataLabels.get_Item(i).getShowLeaderLines() gelijk aan val is).

**Retour:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Geeft het weergavegedrag van de hulplijnen van een gegevenslabel in een opgegeven grafiek weer. True toont de hulplijnen. False verbergt deze. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLeaderLines-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stel deze eigenschap in met een waarde, dan wordt die waarde ook ingesteld op de ShowLeaderLines-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" waardoor alle DataLabels.get_Item(i).getShowLeaderLines() gelijk aan val is).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Bepaalt of een opgegeven grafiek-gegevenslabel wordt weergegeven als data-callout of als gegevenslabel.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLabelAsDataCallout-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stel deze eigenschap in met een waarde, dan wordt die waarde ook ingesteld op de ShowLabelAsDataCallout-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" waardoor alle DataLabels.get_Item(i).getShowLabelAsDataCallout() gelijk aan val is).

**Retour:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Bepaalt of een opgegeven grafiek-gegevenslabel wordt weergegeven als data-callout of als gegevenslabel.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLabelAsDataCallout-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stel deze eigenschap in met een waarde, dan wordt die waarde ook ingesteld op de ShowLabelAsDataCallout-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" waardoor alle DataLabels.get_Item(i).getShowLabelAsDataCallout() gelijk aan val is).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Geeft het weergavegedrag van de celwaarde van een gegevenslabel in een opgegeven grafiek weer. True toont de celwaarde. False verbergt deze. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLabelValueFromCell-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stel deze eigenschap in met een waarde, dan wordt die waarde ook ingesteld op de ShowLabelValueFromCell-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" waardoor alle DataLabels.get_Item(i).getShowLabelValueFromCell() gelijk aan val is).

**Retour:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Geeft het weergavegedrag van de celwaarde van een gegevenslabel in een opgegeven grafiek weer. True toont de celwaarde. False verbergt deze. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLabelValueFromCell-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stel deze eigenschap in met een waarde, dan wordt die waarde ook ingesteld op de ShowLabelValueFromCell-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" waardoor alle DataLabels.get_Item(i).getShowLabelValueFromCell() gelijk aan val is).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Stelt een Variant in of retourneert deze die de scheidingsteken vertegenwoordigt dat wordt gebruikt voor de gegevenslabels in een grafiek. Lezen/schrijven String.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de Separator-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stel deze eigenschap in met een waarde, dan wordt die waarde ook ingesteld op de Separator-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" waardoor alle DataLabels.get_Item(i).getSeparator() gelijk aan val is).

**Retour:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Stelt een Variant in of retourneert deze die de scheidingsteken vertegenwoordigt dat wordt gebruikt voor de gegevenslabels in een grafiek. Lezen/schrijven String.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de Separator-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling. Stel deze eigenschap in met een waarde, dan wordt die waarde ook ingesteld op de Separator-eigenschap voor alle gegevenslabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" waardoor alle DataLabels.get_Item(i).getSeparator() gelijk aan val is).
**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |