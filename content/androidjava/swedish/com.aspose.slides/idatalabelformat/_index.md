---
title: IDataLabelFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar formateringsalternativ för DataLabel.
type: docs
url: /sv/com.aspose.slides/idatalabelformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Representerar formateringsalternativ för DataLabel.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Läs/skriv boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Läs/skriv boolean. |
| [getNumberFormat()](#getNumberFormat--) | Representerar formatsträngen för DataLabels-objektet. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Representerar formatsträngen för DataLabels-objektet. |
| [getFormat()](#getFormat--) | Representerar formatet för dataetiketten. |
| [getPosition()](#getPosition--) | Representerar positionen för dataetiketten. |
| [setPosition(int value)](#setPosition-int-) | Representerar positionen för dataetiketten. |
| [getShowLegendKey()](#getShowLegendKey--) | Representerar ett specificerat diagrammets dataetikett-legendnyckelvisningsbeteende. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Representerar ett specificerat diagrammets dataetikett-legendnyckelvisningsbeteende. |
| [getShowValue()](#getShowValue--) | Representerar ett specificerat diagrammets dataetikett-procentvärdesvisningsbeteende. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Representerar ett specificerat diagrammets dataetikett-procentvärdesvisningsbeteende. |
| [getShowCategoryName()](#getShowCategoryName--) | Representerar ett specificerat diagrammets dataetikett-kategorinamnsvisningsbeteende. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Representerar ett specificerat diagrammets dataetikett-kategorinamnsvisningsbeteende. |
| [getShowSeriesName()](#getShowSeriesName--) | Returnerar eller anger ett Boolean för att indikera visningsbeteendet för serienamnet för dataetiketterna i ett diagram. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Returnerar eller anger ett Boolean för att indikera visningsbeteendet för serienamnet för dataetiketterna i ett diagram. |
| [getShowPercentage()](#getShowPercentage--) | Representerar ett specificerat diagrammets dataetikett-procentvärdesvisningsbeteende. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Representerar ett specificerat diagrammets dataetikett-procentvärdesvisningsbeteende. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Representerar ett specificerat diagrammets dataetikett-bubblestorleksvärdesvisningsbeteende. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Representerar ett specificerat diagrammets dataetikett-bubblestorleksvärdesvisningsbeteende. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Representerar ett specificerat diagrammets dataetikett-pilstlinjevisningsbeteende. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Representerar ett specificerat diagrammets dataetikett-pilstlinjevisningsbeteende. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Bestämmer om ett specificerat diagrammets dataetikett visas som datapunkt eller som dataetikett. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Bestämmer om ett specificerat diagrammets dataetikett visas som datapunkt eller som dataetikett. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Representerar ett specificerat diagrammets dataetikett-cellvärdesvisningsbeteende. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Representerar ett specificerat diagrammets dataetikett-cellvärdesvisningsbeteende. |
| [getSeparator()](#getSeparator--) | Anger eller returnerar en Variant som representerar separatorn som används för dataetiketterna i ett diagram. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Anger eller returnerar en Variant som representerar separatorn som används för dataetiketterna i ett diagram. |
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```


Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för IsNumberFormatLinkedToSource-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för IsNumberFormatLinkedToSource-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" orsakar att alla DataLabels.get_Item(i).isNumberFormatLinkedToSource() är lika med val).

**Returnerar:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```


Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för IsNumberFormatLinkedToSource-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för IsNumberFormatLinkedToSource-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" orsakar att alla DataLabels.get_Item(i).isNumberFormatLinkedToSource() är lika med val).

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```


Representerar formatsträngen för DataLabels-objektet. Läs/skriv String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, så hämtar eller anger den här egenskapen standardvärdet för NumberFormat-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. När denna egenskap sätts med ett värde, sätts samma värde även för NumberFormat-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" gör att alla DataLabels.get_Item(i).getNumberFormat() blir lika med val).

**Returnerar:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```


Representerar formatsträngen för DataLabels-objektet. Läs/skriv String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, så hämtar eller anger den här egenskapen standardvärdet för NumberFormat-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. När denna egenskap sätts med ett värde, sätts samma värde även för NumberFormat-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" gör att alla DataLabels.get_Item(i).getNumberFormat() blir lika med val).

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Representerar formatet för dataetiketten. Endast läsning [IFormat](../../com.aspose.slides/iformat).

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så representerar denna egenskap standardformatet för de nya dataetiketterna i DataLabelCollection-samlingen.

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Representerar positionen för dataetiketten. Läs/skriv [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för Position-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Representerar positionen för DataLabel-objekten. Att sätta denna egenskap med ett värde sätter också detta värde för Position-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" orsakar att alla DataLabels.get_Item(i).getPosition() blir lika med val).

**Returnerar:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Representerar positionen för dataetiketten. Läs/skriv [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för Position-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Representerar positionen för DataLabel-objekten. Att sätta denna egenskap med ett värde sätter också detta värde för Position-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" orsakar att alla DataLabels.get_Item(i).getPosition() blir lika med val).

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```


Representerar ett specificerat diagrammets dataetikett-legendnyckelvisningsbeteende. True om legendnyckeln är synlig. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowLegendKey-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowLegendKey-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" orsakar att alla DataLabels.get_Item(i).getShowLegendKey() är lika med val).

**Returnerar:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```


Representerar ett specificerat diagrammets dataetikett-legendnyckelvisningsbeteende. True om legendnyckeln är synlig. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowLegendKey-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowLegendKey-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" orsakar att alla DataLabels.get_Item(i).getShowLegendKey() är lika med val).

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```


Representerar ett specificerat diagrammets dataetikett-procentvärdesvisningsbeteende. True visar procentvärdet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowValue-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowValue-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" orsakar att alla DataLabels.get_Item(i).getShowValue() är lika med val).

**Returnerar:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```


Representerar ett specificerat diagrammets dataetikett-procentvärdesvisningsbeteende. True visar procentvärdet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowValue-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowValue-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" orsakar att alla DataLabels.get_Item(i).getShowValue() är lika med val).

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```


Representerar ett specificerat diagrammets dataetikett-kategorinamnsvisningsbeteende. True visar kategorinamnet för dataetiketterna i ett diagram. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowCategoryName-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowCategoryName-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" orsakar att alla DataLabels.get_Item(i).getShowCategoryName() är lika med val).

**Returnerar:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```


Representerar ett specificerat diagrammets dataetikett-kategorinamnsvisningsbeteende. True visar kategorinamnet för dataetiketterna i ett diagram. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowCategoryName-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowCategoryName-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" orsakar att alla DataLabels.get_Item(i).getShowCategoryName() är lika med val).

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```


Returnerar eller anger ett Boolean för att indikera beteendet för visning av serienamnet för dataetiketterna i ett diagram. True visar serienamnet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowSeriesName-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowSeriesName-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" orsakar att alla DataLabels.get_Item(i).getShowSeriesName() är lika med val).

**Returnerar:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```


Returnerar eller anger ett Boolean för att indikera beteendet för visning av serienamnet för dataetiketterna i ett diagram. True visar serienamnet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowSeriesName-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowSeriesName-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" orsakar att alla DataLabels.get_Item(i).getShowSeriesName() är lika med val).

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```


Representerar ett specificerat diagrammets dataetikett-procentvärdesvisningsbeteende. True visar procentvärdet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowPercentage-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowPercentage-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" orsakar att alla DataLabels.get_Item(i).getShowPercentage() är lika med val).

**Returnerar:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```


Representerar ett specificerat diagrammets dataetikett-procentvärdesvisningsbeteende. True visar procentvärdet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowPercentage-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowPercentage-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" orsakar att alla DataLabels.get_Item(i).getShowPercentage() är lika med val).

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```


Representerar ett specificerat diagrammets dataetikett-bubblestorleksvärdesvisningsbeteende. True visar bubblestorleksvärdet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowBubbleSize-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowBubbleSize-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" orsakar att alla DataLabels.get_Item(i).getShowBubbleSize() är lika med val).

**Returnerar:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```


Representerar ett specificerat diagrammets dataetikett-bubblestorleksvärdesvisningsbeteende. True visar bubblestorleksvärdet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowBubbleSize-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowBubbleSize-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" orsakar att alla DataLabels.get_Item(i).getShowBubbleSize() är lika med val).

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```


Representerar ett specificerat diagrammets dataetikett-pilstlinjevisningsbeteende. True visar pilstlinjerna. False döljer dem. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowLeaderLines-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowLeaderLines-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" orsakar att alla DataLabels.get_Item(i).getShowLeaderLines() är lika med val).

**Returnerar:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```


Representerar ett specificerat diagrammets dataetikett-pilstlinjevisningsbeteende. True visar pilstlinjerna. False döljer dem. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowLeaderLines-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowLeaderLines-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" orsakar att alla DataLabels.get_Item(i).getShowLeaderLines() är lika med val).

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```


Bestämmer om ett specificerat diagrammets dataetikett ska visas som datapunkt eller som dataetikett.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowLabelAsDataCallout-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowLabelAsDataCallout-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" orsakar att alla DataLabels.get_Item(i).getShowLabelAsDataCallout() är lika med val).

**Returnerar:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```


Bestämmer om ett specificerat diagrammets dataetikett ska visas som datapunkt eller som dataetikett.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowLabelAsDataCallout-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowLabelAsDataCallout-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" orsakar att alla DataLabels.get_Item(i).getShowLabelAsDataCallout() är lika med val).

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```


Representerar ett specificerat diagrammets dataetikett-cellvärdesvisningsbeteende. True visar cellvärdet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowLabelValueFromCell-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowLabelValueFromCell-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" orsakar att alla DataLabels.get_Item(i).getShowLabelValueFromCell() är lika med val).

**Returnerar:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```


Representerar ett specificerat diagrammets dataetikett-cellvärdesvisningsbeteende. True visar cellvärdet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowLabelValueFromCell-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för ShowLabelValueFromCell-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" orsakar att alla DataLabels.get_Item(i).getShowLabelValueFromCell() är lika med val).

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```


Anger eller returnerar en Variant som representerar separatorn som används för dataetiketterna i ett diagram. Läs/skriv String.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för Separator-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för Separator-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" orsakar att alla DataLabels.get_Item(i).getSeparator() är lika med val).

**Returnerar:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```


Anger eller returnerar en Variant som representerar separatorn som används för dataetiketterna i ett diagram. Läs/skriv String.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för Separator-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde för Separator-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" orsakar att alla DataLabels.get_Item(i).getSeparator() är lika med val).

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |