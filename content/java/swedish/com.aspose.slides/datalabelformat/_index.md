---
title: DataLabelFormat
second_title: Aspose.Slides för Java API-referens
description: Representerar formateringsalternativ för DataLabel.
type: docs
url: /sv/com.aspose.slides/datalabelformat/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Representerar formateringsalternativ för DataLabel.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Läs/skriv boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Läs/skriv boolean. |
| [getNumberFormat()](#getNumberFormat--) | Representerar formatsträngen för DataLabels-objektet. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Representerar formatsträngen för DataLabels-objektet. |
| [getFormat()](#getFormat--) | Representerar formatet för dataetiketten. |
| [getPosition()](#getPosition--) | Representerar positionen för dataetiketten. |
| [setPosition(int value)](#setPosition-int-) | Representerar positionen för dataetiketten. |
| [getShowLegendKey()](#getShowLegendKey--) | Representerar ett specifikt diagrammets dataetikett legendnyckels visningsbeteende. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Representerar ett specifikt diagrammets dataetikett legendnyckels visningsbeteende. |
| [getShowValue()](#getShowValue--) | Representerar ett specifikt diagrammets dataetikett procentvärdes visningsbeteende. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Representerar ett specifikt diagrammets dataetikett procentvärdes visningsbeteende. |
| [getShowCategoryName()](#getShowCategoryName--) | Representerar ett specifikt diagrammets dataetikett kategorinamns visningsbeteende. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Representerar ett specifikt diagrammets dataetikett kategorinamns visningsbeteende. |
| [getShowSeriesName()](#getShowSeriesName--) | Returnerar eller anger en Boolean för att indikera serie namnets visningsbeteende för dataetiketterna i ett diagram. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Returnerar eller anger en Boolean för att indikera serie namnets visningsbeteende för dataetiketterna i ett diagram. |
| [getShowPercentage()](#getShowPercentage--) | Representerar ett specifikt diagrammets dataetikett procentvärdes visningsbeteende. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Representerar ett specifikt diagrammets dataetikett procentvärdes visningsbeteende. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Representerar ett specifikt diagrammets dataetikett bubbla storleksvärdes visningsbeteende. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Representerar ett specifikt diagrammets dataetikett bubbla storleksvärdes visningsbeteende. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Representerar ett specifikt diagrammets dataetikett ledarlinjers visningsbeteende. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Representerar ett specifikt diagrammets dataetikett ledarlinjers visningsbeteende. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Representerar ett specifikt diagrammets dataetikett cellvärdes visningsbeteende. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Representerar ett specifikt diagrammets dataetikett cellvärdes visningsbeteende. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Bestämmer om ett specifikt diagrammets dataetikett ska visas som en dataförklaring eller som en dataetikett. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Bestämmer om ett specifikt diagrammets dataetikett ska visas som en dataförklaring eller som en dataetikett. |
| [getSeparator()](#getSeparator--) | Sätter eller returnerar en Variant som representerar separatorn som används för dataetiketter i ett diagram. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Sätter eller returnerar en Variant som representerar separatorn som används för dataetiketter i ett diagram. |
| [getTextFormat()](#getTextFormat--) | Returnerar diagrammets textformat. |
| [getChart()](#getChart--) | Returnerar diagrammet. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Skrivskyddad long.

**Returnerar:**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för IsNumberFormatLinkedToSource-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på IsNumberFormatLinkedToSource-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" gör att alla DataLabels.get\_Item(i).isNumberFormatLinkedToSource() blir lika med val).

**Returnerar:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för IsNumberFormatLinkedToSource-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på IsNumberFormatLinkedToSource-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" gör att alla DataLabels.get\_Item(i).isNumberFormatLinkedToSource() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Representerar formatsträngen för DataLabels-objektet. Läs/skriv String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, så hämtar eller anger den här egenskapen standardvärdet för NumberFormat-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. När denna egenskap sätts med ett värde, sätts samma värde även för NumberFormat-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" gör att alla DataLabels.get\_Item(i).getNumberFormat() blir lika med val).

**Returnerar:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Representerar formatsträngen för DataLabels-objektet. Läs/skriv String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, så hämtar eller anger den här egenskapen standardvärdet för NumberFormat-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. När denna egenskap sätts med ett värde, sätts samma värde även för NumberFormat-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" gör att alla DataLabels.get\_Item(i).getNumberFormat() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Representerar formatet för dataetiketten. Skrivskyddad [IFormat](../../com.aspose.slides/iformat).

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, så representerar denna egenskap standardformatet för de nya dataetiketterna i DataLabelCollection-samlingen.

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Representerar positionen för dataetiketten. Läs/skriv [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för Position-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Representerar positionen för DataLabel-objekten. Att sätta denna egenskap med ett värde sätter också detta värde på Position-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" gör att alla DataLabels.get\_Item(i).getPosition() blir lika med val).

**Returnerar:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Representerar positionen för dataetiketten. Läs/skriv [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för Position-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Representerar positionen för DataLabel-objekten. Att sätta denna egenskap med ett värde sätter också detta värde på Position-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" gör att alla DataLabels.get\_Item(i).getPosition() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Representerar ett specifikt diagrammets dataetikett legendnyckels visningsbeteende. True om legendnyckeln för dataetiketten är synlig. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowLegendKey-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på ShowLegendKey-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" gör att alla DataLabels.get\_Item(i).getShowLegendKey() blir lika med val).

**Returnerar:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Representerar ett specifikt diagrammets dataetikett legendnyckels visningsbeteende. True om legendnyckeln för dataetiketten är synlig. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowLegendKey-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på ShowLegendKey-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" gör att alla DataLabels.get\_Item(i).getShowLegendKey() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Representerar ett specifikt diagrammets dataetikett procentvärdes visningsbeteende. True visar procentvärdet. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowValue-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på ShowValue-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" gör att alla DataLabels.get\_Item(i).getShowValue() blir lika med val).

**Returnerar:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Representerar ett specifikt diagrammets dataetikett procentvärdes visningsbeteende. True visar procentvärdet. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowValue-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på ShowValue-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" gör att alla DataLabels.get\_Item(i).getShowValue() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Representerar ett specifikt diagrammets dataetikett kategorinamns visningsbeteende. True för att visa kategorinamnet för dataetiketterna i ett diagram. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowCategoryName-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på ShowCategoryName-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" gör att alla DataLabels.get\_Item(i).getShowCategoryName() blir lika med val).

**Returnerar:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Representerar ett specifikt diagrammets dataetikett kategorinamns visningsbeteende. True för att visa kategorinamnet för dataetiketterna i ett diagram. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowCategoryName-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på ShowCategoryName-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" gör att alla DataLabels.get\_Item(i).getShowCategoryName() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter får den här egenskapen eller sätter standardvärdet för egenskapen ShowCategoryName för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde till egenskapen ShowCategoryName för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" gör att alla DataLabels.get_Item(i).getShowCategoryName() är lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Returnerar eller anger ett Boolean-värde för att indikera hur seriesnamnet visas för dataetiketterna på ett diagram. True för att visa seriesnamnet. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter får den här egenskapen eller sätter standardvärdet för egenskapen ShowSeriesName för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde till egenskapen ShowSeriesName för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" gör att alla DataLabels.get_Item(i).getShowSeriesName() är lika med val).

**Returnerar:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Returnerar eller anger ett Boolean-värde för att indikera hur seriesnamnet visas för dataetiketterna på ett diagram. True för att visa seriesnamnet. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter får den här egenskapen eller sätter standardvärdet för egenskapen ShowSeriesName för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde till egenskapen ShowSeriesName för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" gör att alla DataLabels.get_Item(i).getShowSeriesName() är lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Representerar hur procentvärdet för dataetiketten visas i ett specificerat diagram. True visar procentvärdet. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter får den här egenskapen eller sätter standardvärdet för egenskapen ShowPercentage för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde till egenskapen ShowPercentage för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" gör att alla DataLabels.get_Item(i).getShowPercentage() är lika med val).

**Returnerar:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Representerar hur procentvärdet för dataetiketten visas i ett specificerat diagram. True visar procentvärdet. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter får den här egenskapen eller sätter standardvärdet för egenskapen ShowPercentage för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde till egenskapen ShowPercentage för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" gör att alla DataLabels.get_Item(i).getShowPercentage() är lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Representerar hur bubbelstorleksvärdet för dataetiketten visas i ett specificerat diagram. True visar bubbelstorleksvärdet. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter får den här egenskapen eller sätter standardvärdet för egenskapen ShowBubbleSize för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde till egenskapen ShowBubbleSize för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" gör att alla DataLabels.get_Item(i).getShowBubbleSize() är lika med val).

**Returnerar:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Representerar hur bubbelstorleksvärdet för dataetiketten visas i ett specificerat diagram. True visar bubbelstorleksvärdet. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter får den här egenskapen eller sätter standardvärdet för egenskapen ShowBubbleSize för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde till egenskapen ShowBubbleSize för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" gör att alla DataLabels.get_Item(i).getShowBubbleSize() är lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Representerar hur ledlinjer för dataetiketten visas i ett specificerat diagram. True visar ledlinjerna. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter får den här egenskapen eller sätter standardvärdet för egenskapen ShowLeaderLines för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde till egenskapen ShowLeaderLines för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" gör att alla DataLabels.get_Item(i).getShowLeaderLines() är lika med val).

**Returnerar:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Representerar hur ledlinjer för dataetiketten visas i ett specificerat diagram. True visar ledlinjerna. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter får den här egenskapen eller sätter standardvärdet för egenskapen ShowLeaderLines för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde till egenskapen ShowLeaderLines för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" gör att alla DataLabels.get_Item(i).getShowLeaderLines() är lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Representerar hur cellvärdet för dataetiketten visas i ett specificerat diagram. True visar cellvärdet. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter får den här egenskapen eller sätter standardvärdet för egenskapen ShowLabelValueFromCell för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde till egenskapen ShowLabelValueFromCell för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" gör att alla DataLabels.get_Item(i).getShowLabelValueFromCell() är lika med val).

**Returnerar:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Representerar hur cellvärdet för dataetiketten visas i ett specificerat diagram. True visar cellvärdet. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter får den här egenskapen eller sätter standardvärdet för egenskapen ShowLabelValueFromCell för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde till egenskapen ShowLabelValueFromCell för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" gör att alla DataLabels.get_Item(i).getShowLabelValueFromCell() är lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Avgör om dataetiketten i ett specificerat diagram kommer att visas som data-callout eller som dataetikett.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter får den här egenskapen eller sätter standardvärdet för egenskapen ShowLabelAsDataCallout för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde till egenskapen ShowLabelAsDataCallout för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" gör att alla DataLabels.get_Item(i).getShowLabelAsDataCallout() är lika med val).

**Returnerar:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Avgör om dataetiketten i ett specificerat diagram kommer att visas som data-callout eller som dataetikett.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter får den här egenskapen eller sätter standardvärdet för egenskapen ShowLabelAsDataCallout för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde till egenskapen ShowLabelAsDataCallout för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" gör att alla DataLabels.get_Item(i).getShowLabelAsDataCallout() är lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Sätter eller returnerar en Variant som representerar separatorn som används för dataetiketterna på ett diagram. Läs/skriv String.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter får den här egenskapen eller sätter standardvärdet för egenskapen Separator för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde till egenskapen Separator för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" gör att alla DataLabels.get_Item(i).getSeparator() är lika med val).

**Returnerar:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Sätter eller returnerar en Variant som representerar separatorn som används för dataetiketterna på ett diagram. Läs/skriv String.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter får den här egenskapen eller sätter standardvärdet för egenskapen Separator för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde till egenskapen Separator för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" gör att alla DataLabels.get_Item(i).getSeparator() är lika med val).
**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Returnerar diagramtextformat. Skrivskyddad [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returnerar:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Returnerar diagrammet. Skrivskyddad [IChart](../../com.aspose.slides/ichart).

**Returnerar:**
[IChart](../../com.aspose.slides/ichart)