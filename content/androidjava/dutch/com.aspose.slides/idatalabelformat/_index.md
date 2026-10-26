---
title: IDataLabelFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt opmaakopties voor DataLabel.
type: docs
url: /nl/com.aspose.slides/idatalabelformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Geeft de opmaakopties voor DataLabel weer.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Lezen/schrijven boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Lezen/schrijven boolean. |
| [getNumberFormat()](#getNumberFormat--) | Geeft de opmaakreeks weer voor het DataLabels-object. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Geeft de opmaakreeks weer voor het DataLabels-object. |
| [getFormat()](#getFormat--) | Geeft de opmaak van het gegevenslabel weer. |
| [getPosition()](#getPosition--) | Geeft de positie van het gegevenslabel weer. |
| [setPosition(int value)](#setPosition-int-) | Geeft de positie van het gegevenslabel weer. |
| [getShowLegendKey()](#getShowLegendKey--) | Geeft het weergavegedrag van de legenda-sleutel van het gegevenslabel voor een opgegeven diagram weer. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Geeft het weergavegedrag van de legenda-sleutel van het gegevenslabel voor een opgegeven diagram weer. |
| [getShowValue()](#getShowValue--) | Geeft het weergavegedrag van de percentage-waarde van het gegevenslabel voor een opgegeven diagram weer. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Geeft het weergavegedrag van de percentage-waarde van het gegevenslabel voor een opgegeven diagram weer. |
| [getShowCategoryName()](#getShowCategoryName--) | Geeft het weergavegedrag van de categorienaam van het gegevenslabel voor een opgegeven diagram weer. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Geeft het weergavegedrag van de categorienaam van het gegevenslabel voor een opgegeven diagram weer. |
| [getShowSeriesName()](#getShowSeriesName--) | Geeft een Boolean terug of stelt deze in om het weergavegedrag van de serienaam voor de gegevenslabels op een diagram aan te geven. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Geeft een Boolean terug of stelt deze in om het weergavegedrag van de serienaam voor de gegevenslabels op een diagram aan te geven. |
| [getShowPercentage()](#getShowPercentage--) | Geeft het weergavegedrag van de percentage-waarde van het gegevenslabel voor een opgegeven diagram weer. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Geeft het weergavegedrag van de percentage-waarde van het gegevenslabel voor een opgegeven diagram weer. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Geeft het weergavegedrag van de bubbelgrootte-waarde van het gegevenslabel voor een opgegeven diagram weer. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Geeft het weergavegedrag van de bubbelgrootte-waarde van het gegevenslabel voor een opgegeven diagram weer. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Geeft het weergavegedrag van de leidinglijnen van het gegevenslabel voor een opgegeven diagram weer. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Geeft het weergavegedrag van de leidinglijnen van het gegevenslabel voor een opgegeven diagram weer. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Bepaalt of het gegevenslabel van een opgegeven diagram wordt weergegeven als gegevens-callout of als gegevenslabel. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Bepaalt of het gegevenslabel van een opgegeven diagram wordt weergegeven als gegevens-callout of als gegevenslabel. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Geeft het weergavegedrag van de celwaarde van het gegevenslabel voor een opgegeven diagram weer. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Geeft het weergavegedrag van de celwaarde van het gegevenslabel voor een opgegeven diagram weer. |
| [getSeparator()](#getSeparator--) | Stelt een Variant in of geeft deze terug die de scheidingsteken vertegenwoordigt dat wordt gebruikt voor de gegevenslabels op een diagram. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Stelt een Variant in of geeft deze terug die de scheidingsteken vertegenwoordigt dat wordt gebruikt voor de gegevenslabels op een diagram. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de IsNumberFormatLinkedToSource-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de IsNumberFormatLinkedToSource-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" waardoor alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() gelijk is aan val).

**Retourneert:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de IsNumberFormatLinkedToSource-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de IsNumberFormatLinkedToSource-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" waardoor alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Geeft de opmaakreeks weer voor het DataLabels-object. Lezen/schrijven String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de NumberFormat-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Wanneer deze eigenschap wordt ingesteld met een waarde, wordt die waarde ook ingesteld voor de NumberFormat-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" waardoor alle DataLabels.get_Item(i).getNumberFormat() gelijk is aan val).

**Retourneert:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Geeft de opmaakreeks weer voor het DataLabels-object. Lezen/schrijven String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de NumberFormat-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Wanneer deze eigenschap wordt ingesteld met een waarde, wordt die waarde ook ingesteld voor de NumberFormat-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" waardoor alle DataLabels.get_Item(i).getNumberFormat() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Geeft de opmaak van het gegevenslabel weer. Alleen-lezen [IFormat](../../com.aspose.slides/iformat).

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan geeft deze eigenschap de standaardopmaak weer voor de nieuwe gegevenslabels in de DataLabelCollection-collectie.

**Retourneert:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Geeft de positie van het gegevenslabel weer. Lezen/schrijven [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de Position-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Geeft de positie weer voor de DataLabel-objecten. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de Position-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" waardoor alle DataLabels.get_Item(i).getPosition() gelijk is aan val).

**Retourneert:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Geeft de positie van het gegevenslabel weer. Lezen/schrijven [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de Position-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Geeft de positie weer voor de DataLabel-objecten. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de Position-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" waardoor alle DataLabels.get_Item(i).getPosition() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Geeft het weergavegedrag van de legenda-sleutel van het gegevenslabel voor een opgegeven diagram weer. Waar als de legenda-sleutel van het gegevenslabel zichtbaar is. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowLegendKey-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLegendKey-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" waardoor alle DataLabels.get_Item(i).getShowLegendKey() gelijk is aan val).

**Retourneert:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Geeft het weergavegedrag van de legenda-sleutel van het gegevenslabel voor een opgegeven diagram weer. Waar als de legenda-sleutel van het gegevenslabel zichtbaar is. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowLegendKey-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLegendKey-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" waardoor alle DataLabels.get_Item(i).getShowLegendKey() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Geeft het weergavegedrag van de percentage-waarde van het gegevenslabel voor een opgegeven diagram weer. Waar als de percentage-waarde wordt weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowValue-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowValue-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" waardoor alle DataLabels.get_Item(i).getShowValue() gelijk is aan val).

**Retourneert:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Geeft het weergavegedrag van de percentage-waarde van het gegevenslabel voor een opgegeven diagram weer. Waar als de percentage-waarde wordt weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowValue-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowValue-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" waardoor alle DataLabels.get_Item(i).getShowValue() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Geeft het weergavegedrag van de categorienaam van het gegevenslabel voor een opgegeven diagram weer. Waar als de categorienaam wordt weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowCategoryName-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowCategoryName-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" waardoor alle DataLabels.get_Item(i).getShowCategoryName() gelijk is aan val).

**Retourneert:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Geeft het weergavegedrag van de categorienaam van het gegevenslabel voor een opgegeven diagram weer. Waar als de categorienaam wordt weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowCategoryName-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowCategoryName-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" waardoor alle DataLabels.get_Item(i).getShowCategoryName() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Geeft een Boolean terug of stelt deze in om het weergavegedrag van de serienaam voor de gegevenslabels op een diagram aan te geven. Waar om de serienaam te tonen. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowSeriesName-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowSeriesName-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" waardoor alle DataLabels.get_Item(i).getShowSeriesName() gelijk is aan val).

**Retourneert:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Geeft een Boolean terug of stelt deze in om het weergavegedrag van de serienaam voor de gegevenslabels op een diagram aan te geven. Waar om de serienaam te tonen. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowSeriesName-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowSeriesName-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" waardoor alle DataLabels.get_Item(i).getShowSeriesName() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Geeft het weergavegedrag van de percentage-waarde van het gegevenslabel voor een opgegeven diagram weer. Waar als de percentage-waarde wordt weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowPercentage-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowPercentage-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" waardoor alle DataLabels.get_Item(i).getShowPercentage() gelijk is aan val).

**Retourneert:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Geeft het weergavegedrag van de percentage-waarde van het gegevenslabel voor een opgegeven diagram weer. Waar als de percentage-waarde wordt weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowPercentage-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowPercentage-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" waardoor alle DataLabels.get_Item(i).getShowPercentage() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Geeft het weergavegedrag van de bubbelgrootte-waarde van het gegevenslabel voor een opgegeven diagram weer. Waar als de bubbelgrootte-waarde wordt weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowBubbleSize-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowBubbleSize-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" waardoor alle DataLabels.get_Item(i).getShowBubbleSize() gelijk is aan val).

**Retourneert:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Geeft het weergavegedrag van de bubbelgrootte-waarde van het gegevenslabel voor een opgegeven diagram weer. Waar als de bubbelgrootte-waarde wordt weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowBubbleSize-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowBubbleSize-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" waardoor alle DataLabels.get_Item(i).getShowBubbleSize() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Geeft het weergavegedrag van de leidinglijnen van het gegevenslabel voor een opgegeven diagram weer. Waar als de leidinglijnen worden weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowLeaderLines-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLeaderLines-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" waardoor alle DataLabels.get_Item(i).getShowLeaderLines() gelijk is aan val).

**Retourneert:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Geeft het weergavegedrag van de leidinglijnen van het gegevenslabel voor een opgegeven diagram weer. Waar als de leidinglijnen worden weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowLeaderLines-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLeaderLines-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" waardoor alle DataLabels.get_Item(i).getShowLeaderLines() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Bepaalt of het gegevenslabel van een opgegeven diagram wordt weergegeven als gegevens-callout of als gegevenslabel.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowLabelAsDataCallout-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLabelAsDataCallout-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" waardoor alle DataLabels.get_Item(i).getShowLabelAsDataCallout() gelijk is aan val).

**Retourneert:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Bepaalt of het gegevenslabel van een opgegeven diagram wordt weergegeven als gegevens-callout of als gegevenslabel.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowLabelAsDataCallout-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLabelAsDataCallout-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" waardoor alle DataLabels.get_Item(i).getShowLabelAsDataCallout() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Geeft het weergavegedrag van de celwaarde van het gegevenslabel voor een opgegeven diagram weer. Waar als de celwaarde wordt weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowLabelValueFromCell-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLabelValueFromCell-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" waardoor alle DataLabels.get_Item(i).getShowLabelValueFromCell() gelijk is aan val).

**Retourneert:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Geeft het weergavegedrag van de celwaarde van het gegevenslabel voor een opgegeven diagram weer. Waar als de celwaarde wordt weergegeven. Onwaar om te verbergen. Lezen/schrijven boolean.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowLabelValueFromCell-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLabelValueFromCell-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" waardoor alle DataLabels.get_Item(i).getShowLabelValueFromCell() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Stelt een Variant in of geeft deze terug die de scheidingsteken vertegenwoordigt dat wordt gebruikt voor de gegevenslabels op een diagram. Lezen/schrijven String.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de Separator-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de Separator-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" waardoor alle DataLabels.get_Item(i).getSeparator() gelijk is aan val).

**Retourneert:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Stelt een Variant in of geeft deze terug die de scheidingsteken vertegenwoordigt dat wordt gebruikt voor de gegevenslabels op een diagram. Lezen/schrijven String.

--------------------

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de Separator-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de Separator-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" waardoor alle DataLabels.get_Item(i).getSeparator() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |