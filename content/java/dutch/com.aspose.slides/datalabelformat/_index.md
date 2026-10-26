---
title: DataLabelFormat
second_title: Aspose.Slides voor Java API-referentie
description: Biedt opmaakopties voor DataLabel.
type: docs
url: /nl/com.aspose.slides/datalabelformat/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
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
| [getShowLegendKey()](#getShowLegendKey--) | Stelt het weergavegedrag van de legende-sleutel van het gegevensetiket van een opgegeven diagram voor. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Stelt het weergavegedrag van de legende-sleutel van het gegevensetiket van een opgegeven diagram voor. |
| [getShowValue()](#getShowValue--) | Stelt het weergavegedrag van de percentage-waarde van het gegevensetiket van een opgegeven diagram voor. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Stelt het weergavegedrag van de percentage-waarde van het gegevensetiket van een opgegeven diagram voor. |
| [getShowCategoryName()](#getShowCategoryName--) | Stelt het weergavegedrag van de categorienaam van het gegevensetiket van een opgegeven diagram voor. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Stelt het weergavegedrag van de categorienaam van het gegevensetiket van een opgegeven diagram voor. |
| [getShowSeriesName()](#getShowSeriesName--) | Geeft een Boolean terug of stelt deze in om het weergavegedrag van de serienaam voor de gegevensetiketten op een diagram aan te geven. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Geeft een Boolean terug of stelt deze in om het weergavegedrag van de serienaam voor de gegevensetiketten op een diagram aan te geven. |
| [getShowPercentage()](#getShowPercentage--) | Stelt het weergavegedrag van de percentage-waarde van het gegevensetiket van een opgegeven diagram voor. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Stelt het weergavegedrag van de percentage-waarde van het gegevensetiket van een opgegeven diagram voor. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Stelt het weergavegedrag van de bubbelgrootte-waarde van het gegevensetiket van een opgegeven diagram voor. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Stelt het weergavegedrag van de bubbelgrootte-waarde van het gegevensetiket van een opgegeven diagram voor. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Stelt het weergavegedrag van de leidende lijnen van het gegevensetiket van een opgegeven diagram voor. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Stelt het weergavegedrag van de leidende lijnen van het gegevensetiket van een opgegeven diagram voor. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Stelt het weergavegedrag van de celwaarde van het gegevensetiket van een opgegeven diagram voor. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Stelt het weergavegedrag van de celwaarde van het gegevensetiket van een opgegeven diagram voor. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Bepaalt of het gegevensetiket van een opgegeven diagram wordt weergegeven als gegevensbijschrift of als gegevensetiket. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Bepaalt of het gegevensetiket van een opgegeven diagram wordt weergegeven als gegevensbijschrift of als gegevensetiket. |
| [getSeparator()](#getSeparator--) | Stelt een Variant in of geeft deze terug die de scheidingsteken voor de gegevensetiketten op een diagram voorstelt. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Stelt een Variant in of geeft deze terug die de scheidingsteken voor de gegevensetiketten op een diagram voorstelt. |
| [getTextFormat()](#getTextFormat--) | Geeft het tekstformaat van het diagram terug. |
| [getChart()](#getChart--) | Geeft het diagram terug. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versie. Alleen-lezen long.

**Retour:**
long
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevensetiketten is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de IsNumberFormatLinkedToSource-eigenschap in voor de nieuwe gegevensetiketten in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de IsNumberFormatLinkedToSource-eigenschap van alle gegevensetiketten in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" veroorzaakt dat alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() gelijk is aan val).

**Retour:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevensetiketten is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de IsNumberFormatLinkedToSource-eigenschap in voor de nieuwe gegevensetiketten in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de IsNumberFormatLinkedToSource-eigenschap van alle gegevensetiketten in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" veroorzaakt dat alle DataLabels.get_Item(i).isNumberFormatLinkedToSource() gelijk is aan val).

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

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevensetiketten is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de NumberFormat-eigenschap in voor de nieuwe gegevensetiketten in de DataLabelCollection-collectie. Wanneer deze eigenschap met een waarde wordt ingesteld, wordt die waarde ook ingesteld voor de NumberFormat-eigenschap van alle gegevensetiketten in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" veroorzaakt dat alle DataLabels.get_Item(i).getNumberFormat() gelijk is aan val).

**Retour:**
java.lang.String
### setNumberFormat(java.lang.String value) {#setNumberFormat-java.lang.String-}
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

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevensetiketten is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de NumberFormat-eigenschap in voor de nieuwe gegevensetiketten in de DataLabelCollection-collectie. Wanneer deze eigenschap met een waarde wordt ingesteld, wordt die waarde ook ingesteld voor de NumberFormat-eigenschap van alle gegevensetiketten in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" veroorzaakt dat alle DataLabels.get_Item(i).getNumberFormat() gelijk is aan val).

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

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevensetiketten is, dan vertegenwoordigt deze eigenschap het standaardformaat voor de nieuwe gegevensetiketten in de DataLabelCollection-collectie.

**Retour:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Stelt de positie van het gegevenslabel voor. Lezen/schrijven [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevensetiketten is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de Position-eigenschap in voor de nieuwe gegevensetiketten in de DataLabelCollection-collectie. Stelt de positie in voor de DataLabel-objecten. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de Position-eigenschap van alle gegevensetiketten in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" veroorzaakt dat alle DataLabels.get_Item(i).getPosition() gelijk is aan val).

**Retour:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Stelt de positie van het gegevenslabel voor. Lezen/schrijven [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevensetiketten is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de Position-eigenschap in voor de nieuwe gegevensetiketten in de DataLabelCollection-collectie. Stelt de positie in voor de DataLabel-objecten. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de Position-eigenschap van alle gegevensetiketten in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" veroorzaakt dat alle DataLabels.get_Item(i).getPosition() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Stelt het weergavegedrag van de legende-sleutel van het gegevensetiket van een opgegeven diagram voor. Waar als de legende-sleutel van het gegevensetiket zichtbaar is. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevensetiketten is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowLegendKey-eigenschap in voor de nieuwe gegevensetiketten in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLegendKey-eigenschap van alle gegevensetiketten in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" veroorzaakt dat alle DataLabels.get_Item(i).getShowLegendKey() gelijk is aan val).

**Retour:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Stelt het weergavegedrag van de legende-sleutel van het gegevensetiket van een opgegeven diagram voor. Waar als de legende-sleutel van het gegevensetiket zichtbaar is. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevensetiketten is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowLegendKey-eigenschap in voor de nieuwe gegevensetiketten in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLegendKey-eigenschap van alle gegevensetiketten in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" veroorzaakt dat alle DataLabels.get_Item(i).getShowLegendKey() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Stelt het weergavegedrag van de percentage-waarde van het gegevensetiket van een opgegeven diagram voor. Waar toont de percentage-waarde. Onwaar verbergt deze. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevensetiketten is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowValue-eigenschap in voor de nieuwe gegevensetiketten in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowValue-eigenschap van alle gegevensetiketten in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" veroorzaakt dat alle DataLabels.get_Item(i).getShowValue() gelijk is aan val).

**Retour:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Stelt het weergavegedrag van de percentage-waarde van het gegevensetiket van een opgegeven diagram voor. Waar toont de percentage-waarde. Onwaar verbergt deze. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevensetiketten is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowValue-eigenschap in voor de nieuwe gegevensetiketten in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowValue-eigenschap van alle gegevensetiketten in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" veroorzaakt dat alle DataLabels.get_Item(i).getShowValue() gelijk is aan val).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Stelt het weergavegedrag van de categorienaam van het gegevensetiket van een opgegeven diagram voor. Waar toont de categorienaam voor de gegevensetiketten op een diagram. Onwaar verbergt deze. Lezen/schrijven boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevensetiketten is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowCategoryName-eigenschap in voor de nieuwe gegevensetiketten in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowCategoryName-eigenschap van alle gegevensetiketten in de DataLabelCollection-collectie (bijv. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" veroorzaakt dat alle DataLabels.get_Item(i).getShowCategoryName() gelijk is aan val).

**Retour:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Stelt het weergavegedrag van de categorienaam van het gegevensetiket van een opgegeven diagram voor. Waar toont de categorienaam voor de gegevensetiketten op een diagram. Onwaar verbergt deze. Lezen/schrijven boolean.
Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van datalabels is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowCategoryName-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowCategoryName-eigenschap van alle datalabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" waardoor alle DataLabels.get_Item(i).getShowCategoryName() gelijk is aan val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Retourneert of stelt een Boolean in om het weergavegedrag van de serienaam voor de datalabels in een diagram aan te geven. True om de serienaam weer te geven. False om te verbergen. Lezen/schrijven Boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van datalabels is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowSeriesName-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowSeriesName-eigenschap van alle datalabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" waardoor alle DataLabels.get_Item(i).getShowSeriesName() gelijk is aan val).

**Returns:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Retourneert of stelt een Boolean in om het weergavegedrag van de serienaam voor de datalabels in een diagram aan te geven. True om de serienaam weer te geven. False om te verbergen. Lezen/schrijven Boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van datalabels is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowSeriesName-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowSeriesName-eigenschap van alle datalabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" waardoor alle DataLabels.get_Item(i).getShowSeriesName() gelijk is aan val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Geeft het weergavegedrag van het percentage van de datalabel van een opgegeven diagram weer. True om het percentage weer te geven. False om te verbergen. Lezen/schrijven Boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van datalabels is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowPercentage-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowPercentage-eigenschap van alle datalabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" waardoor alle DataLabels.get_Item(i).getShowPercentage() gelijk is aan val).

**Returns:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Geeft het weergavegedrag van het percentage van de datalabel van een opgegeven diagram weer. True om het percentage weer te geven. False om te verbergen. Lezen/schrijven Boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van datalabels is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowPercentage-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowPercentage-eigenschap van alle datalabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" waardoor alle DataLabels.get_Item(i).getShowPercentage() gelijk is aan val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Geeft het weergavegedrag van de bubbelgrootte van de datalabel van een opgegeven diagram weer. True om de bubbelgrootte weer te geven. False om te verbergen. Lezen/schrijven Boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van datalabels is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowBubbleSize-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowBubbleSize-eigenschap van alle datalabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" waardoor alle DataLabels.get_Item(i).getShowBubbleSize() gelijk is aan val).

**Returns:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Geeft het weergavegedrag van de bubbelgrootte van de datalabel van een opgegeven diagram weer. True om de bubbelgrootte weer te geven. False om te verbergen. Lezen/schrijven Boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van datalabels is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowBubbleSize-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowBubbleSize-eigenschap van alle datalabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" waardoor alle DataLabels.get_Item(i).getShowBubbleSize() gelijk is aan val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Geeft het weergavegedrag van de hulplijnen van de datalabel van een opgegeven diagram weer. True om de hulplijnen weer te geven. False om te verbergen. Lezen/schrijven Boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van datalabels is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowLeaderLines-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLeaderLines-eigenschap van alle datalabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" waardoor alle DataLabels.get_Item(i).getShowLeaderLines() gelijk is aan val).

**Returns:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Geeft het weergavegedrag van de hulplijnen van de datalabel van een opgegeven diagram weer. True om de hulplijnen weer te geven. False om te verbergen. Lezen/schrijven Boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van datalabels is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowLeaderLines-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLeaderLines-eigenschap van alle datalabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" waardoor alle DataLabels.get_Item(i).getShowLeaderLines() gelijk is aan val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Geeft het weergavegedrag van de celwaarde van de datalabel van een opgegeven diagram weer. True om de celwaarde weer te geven. False om te verbergen. Lezen/schrijven Boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van datalabels is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowLabelValueFromCell-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLabelValueFromCell-eigenschap van alle datalabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" waardoor alle DataLabels.get_Item(i).getShowLabelValueFromCell() gelijk is aan val).

**Returns:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Geeft het weergavegedrag van de celwaarde van de datalabel van een opgegeven diagram weer. True om de celwaarde weer te geven. False om te verbergen. Lezen/schrijven Boolean.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van datalabels is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowLabelValueFromCell-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLabelValueFromCell-eigenschap van alle datalabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" waardoor alle DataLabels.get_Item(i).getShowLabelValueFromCell() gelijk is aan val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Bepaalt of een datalabel van een opgegeven diagram wordt weergegeven als data-callout of als datalabel.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van datalabels is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowLabelAsDataCallout-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLabelAsDataCallout-eigenschap van alle datalabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" waardoor alle DataLabels.get_Item(i).getShowLabelAsDataCallout() gelijk is aan val).

**Returns:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Bepaalt of een datalabel van een opgegeven diagram wordt weergegeven als data-callout of als datalabel.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van datalabels is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowLabelAsDataCallout-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLabelAsDataCallout-eigenschap van alle datalabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" waardoor alle DataLabels.get_Item(i).getShowLabelAsDataCallout() gelijk is aan val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Stelt een Variant in of retourneert deze die de scheidingsteken vertegenwoordigt dat wordt gebruikt voor de datalabels in een diagram. Lezen/schrijven String.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van datalabels is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de Separator-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de Separator-eigenschap van alle datalabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" waardoor alle DataLabels.get_Item(i).getSeparator() gelijk is aan val).

**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Stelt een Variant in of retourneert deze die de scheidingsteken vertegenwoordigt dat wordt gebruikt voor de datalabels in een diagram. Lezen/schrijven String.

--------------------

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van datalabels is, dan krijgt deze eigenschap of stelt deze de standaardwaarde van de Separator-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-verzameling. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de Separator-eigenschap van alle datalabels in de DataLabelCollection-verzameling (bijv. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" waardoor alle DataLabels.get_Item(i).getSeparator() gelijk is aan val).
**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Retourneert het tekstformaat van de grafiek. Alleen-lezen [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retour:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Retourneert de grafiek. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Retour:**
[IChart](../../com.aspose.slides/ichart)