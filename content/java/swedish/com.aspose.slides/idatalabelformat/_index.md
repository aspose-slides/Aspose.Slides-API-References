---
title: IDataLabelFormat
second_title: Aspose.Slides för Java API-referens
description: Representerar formateringsalternativ för DataLabel.
type: docs
url: /sv/com.aspose.slides/idatalabelformat/
---
**Alla implementerade gränssnitt:**
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
| [getShowLegendKey()](#getShowLegendKey--) | Representerar ett specificerat diagramdataetiketts legendnyckelns visningsbeteende. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Representerar ett specificerat diagramdataetiketts legendnyckelns visningsbeteende. |
| [getShowValue()](#getShowValue--) | Representerar ett specificerat diagramdataetiketts procentvärdesvisningsbeteende. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Representerar ett specificerat diagramdataetiketts procentvärdesvisningsbeteende. |
| [getShowCategoryName()](#getShowCategoryName--) | Representerar ett specificerat diagramdataetiketts kategorinamns visningsbeteende. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Representerar ett specificerat diagramdataetiketts kategorinamns visningsbeteende. |
| [getShowSeriesName()](#getShowSeriesName--) | Returnerar eller ställer in ett Boolean för att indikera seriens namnvisningsbeteende för dataetiketterna på ett diagram. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Returnerar eller ställer in ett Boolean för att indikera seriens namnvisningsbeteende för dataetiketterna på ett diagram. |
| [getShowPercentage()](#getShowPercentage--) | Representerar ett specificerat diagramdataetiketts procentvärdesvisningsbeteende. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Representerar ett specificerat diagramdataetiketts procentvärdesvisningsbeteende. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Representerar ett specificerat diagramdataetiketts bubbelformatsvärdesvisningsbeteende. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Representerar ett specificerat diagramdataetiketts bubbelformatsvärdesvisningsbeteende. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Representerar ett specificerat diagramdataetiketts ledarlinjers visningsbeteende. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Representerar ett specificerat diagramdataetiketts ledarlinjers visningsbeteende. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Bestämmer om ett specificerat diagramdataetikett ska visas som datautrop eller som dataetikett. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Bestämmer om ett specificerat diagramdataetikett ska visas som datautrop eller som dataetikett. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Representerar ett specificerat diagramdataetiketts cellvärdesvisningsbeteende. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Representerar ett specificerat diagramdataetiketts cellvärdesvisningsbeteende. |
| [getSeparator()](#getSeparator--) | Ställer in eller returnerar en Variant som representerar separatorn som används för dataetiketterna på ett diagram. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Ställer in eller returnerar en Variant som representerar separatorn som används för dataetiketterna på ett diagram. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, får eller ställer denna egenskap in standardvärdet för IsNumberFormatLinkedToSource-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på IsNumberFormatLinkedToSource-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" får alla DataLabels.get_Item(i).isNumberFormatLinkedToSource() lika med val).

**Returnerar:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, får eller ställer denna egenskap in standardvärdet för IsNumberFormatLinkedToSource-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på IsNumberFormatLinkedToSource-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" får alla DataLabels.get_Item(i).isNumberFormatLinkedToSource() lika med val).

**Parametrar:**
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

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, får eller ställer denna egenskap in standardvärdet för NumberFormat-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. När denna egenskap sätts med ett värde, sätts samma värde på NumberFormat-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" får alla DataLabels.get_Item(i).getNumberFormat() lika med val).

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

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, får eller ställer denna egenskap in standardvärdet för NumberFormat-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. När denna egenskap sätts med ett värde, sätts samma värde på NumberFormat-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" får alla DataLabels.get_Item(i).getNumberFormat() lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Representerar formatet för dataetiketten. Skrivskyddad [IFormat](../../com.aspose.slides/iformat).

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, representerar denna egenskap standardformatet för de nya dataetiketterna i DataLabelCollection-samlingen.

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Representerar positionen för dataetiketten. Läs/skriv [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, får eller ställer denna egenskap in standardvärdet för Position-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Representerar positionen för DataLabel-objekten. Att sätta denna egenskap med ett värde sätter också detta värde på Position-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" får alla DataLabels.get_Item(i).getPosition() lika med val).

**Returnerar:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Representerar positionen för dataetiketten. Läs/skriv [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, får eller ställer denna egenskap in standardvärdet för Position-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Representerar positionen för DataLabel-objekten. Att sätta denna egenskap med ett värde sätter också detta värde på Position-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" får alla DataLabels.get_Item(i).getPosition() lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Representerar ett specificerat diagramdataetiketts legendnyckelns visningsbeteende. Sant om legendnyckeln för dataetiketten är synlig. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, får eller ställer denna egenskap in standardvärdet för ShowLegendKey-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på ShowLegendKey-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" får alla DataLabels.get_Item(i).getShowLegendKey() lika med val).

**Returnerar:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Representerar ett specificerat diagramdataetiketts legendnyckelns visningsbeteende. Sant om legendnyckeln för dataetiketten är synlig. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, får eller ställer denna egenskap in standardvärdet för ShowLegendKey-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på ShowLegendKey-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" får alla DataLabels.get_Item(i).getShowLegendKey() lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Representerar ett specificerat diagramdataetiketts procentvärdesvisningsbeteende. Sant visar procentvärdet. Falskt för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, får eller ställer denna egenskap in standardvärdet för ShowValue-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på ShowValue-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" får alla DataLabels.get_Item(i).getShowValue() lika med val).

**Returnerar:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Representerar ett specificerat diagramdataetiketts procentvärdesvisningsbeteende. Sant visar procentvärdet. Falskt för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, får eller ställer denna egenskap in standardvärdet för ShowValue-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på ShowValue-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" får alla DataLabels.get_Item(i).getShowValue() lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Representerar ett specificerat diagramdataetiketts kategorinamns visningsbeteende. Sant för att visa kategorinamnet för dataetiketterna på ett diagram. Falskt för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, får eller ställer denna egenskap in standardvärdet för ShowCategoryName-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde på ShowCategoryName-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" får alla DataLabels.get_Item(i).getShowCategoryName() lika med val).

**Returnerar:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Representerar ett specificerat diagramdataetiketts kategorinamns visningsbeteende. Sant för att visa kategorinamnet för dataetiketterna på ett diagram. Falskt för att dölja. Läs/skriv boolean.

--------------------
Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, får den här egenskapen eller ställer in standardvärdet för ShowCategoryName-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen. Sätt den här egenskapen med ett värde ställer också in detta värde på ShowCategoryName-egenskapen för alla datamärkningar i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" vilket gör att alla DataLabels.get_Item(i).getShowCategoryName() är lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Returnerar eller ställer in ett Boolean för att ange om serienamnet ska visas för datamärkningarna i ett diagram. True för att visa serienamnet. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, får den här egenskapen eller ställer in standardvärdet för ShowSeriesName-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen. Sätt den här egenskapen med ett värde ställer också in detta värde på ShowSeriesName-egenskapen för alla datamärkningar i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" vilket gör att alla DataLabels.get_Item(i).getShowSeriesName() är lika med val).

**Returnerar:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Returnerar eller ställer in ett Boolean för att ange om serienamnet ska visas för datamärkningarna i ett diagram. True för att visa serienamnet. False för att dölja. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, får den här egenskapen eller ställer in standardvärdet för ShowSeriesName-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen. Sätt den här egenskapen med ett värde ställer också in detta värde på ShowSeriesName-egenskapen för alla datamärkningar i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" vilket gör att alla DataLabels.get_Item(i).getShowSeriesName() är lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Representerar ett specificerat diagramms datamärkningsprocentvärdes visningsbeteende. True visar procentvärdet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, får den här egenskapen eller ställer in standardvärdet för ShowPercentage-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen. Sätt den här egenskapen med ett värde ställer också in detta värde på ShowPercentage-egenskapen för alla datamärkningar i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" vilket gör att alla DataLabels.get_Item(i).getShowPercentage() är lika med val).

**Returnerar:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Representerar ett specificerat diagramms datamärkningsprocentvärdes visningsbeteende. True visar procentvärdet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, får den här egenskapen eller ställer in standardvärdet för ShowPercentage-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen. Sätt den här egenskapen med ett värde ställer också in detta värde på ShowPercentage-egenskapen för alla datamärkningar i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" vilket gör att alla DataLabels.get_Item(i).getShowPercentage() är lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Representerar ett specificerat diagramms datamärkningsbubbelstorleksvärdes visningsbeteende. True visar bubbelstorleksvärdet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, får den här egenskapen eller ställer in standardvärdet för ShowBubbleSize-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen. Sätt den här egenskapen med ett värde ställer också in detta värde på ShowBubbleSize-egenskapen för alla datamärkningar i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" vilket gör att alla DataLabels.get_Item(i).getShowBubbleSize() är lika med val).

**Returnerar:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Representerar ett specificerat diagramms datamärkningsbubbelstorleksvärdes visningsbeteende. True visar bubbelstorleksvärdet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, får den här egenskapen eller ställer in standardvärdet för ShowBubbleSize-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen. Sätt den här egenskapen med ett värde ställer också in detta värde på ShowBubbleSize-egenskapen för alla datamärkningar i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" vilket gör att alla DataLabels.get_Item(i).getShowBubbleSize() är lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Representerar ett specificerat diagramms datamärkningsledarlinjers visningsbeteende. True visar ledarlinjerna. False döljer dem. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, får den här egenskapen eller ställer in standardvärdet för ShowLeaderLines-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen. Sätt den här egenskapen med ett värde ställer också in detta värde på ShowLeaderLines-egenskapen för alla datamärkningar i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" vilket gör att alla DataLabels.get_Item(i).getShowLeaderLines() är lika med val).

**Returnerar:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Representerar ett specificerat diagramms datamärkningsledarlinjers visningsbeteende. True visar ledarlinjerna. False döljer dem. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, får den här egenskapen eller ställer in standardvärdet för ShowLeaderLines-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen. Sätt den här egenskapen med ett värde ställer också in detta värde på ShowLeaderLines-egenskapen för alla datamärkningar i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" vilket gör att alla DataLabels.get_Item(i).getShowLeaderLines() är lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Bestämmer om en specificerad diagramdatas etikett visas som dataanrop eller som datamärkning.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, får den här egenskapen eller ställer in standardvärdet för ShowLabelAsDataCallout-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen. Sätt den här egenskapen med ett värde ställer också in detta värde på ShowLabelAsDataCallout-egenskapen för alla datamärkningar i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" vilket gör att alla DataLabels.get_Item(i).getShowLabelAsDataCallout() är lika med val).

**Returnerar:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Bestämmer om en specificerad diagramdatas etikett visas som dataanrop eller som datamärkning.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, får den här egenskapen eller ställer in standardvärdet för ShowLabelAsDataCallout-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen. Sätt den här egenskapen med ett värde ställer också in detta värde på ShowLabelAsDataCallout-egenskapen för alla datamärkningar i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" vilket gör att alla DataLabels.get_Item(i).getShowLabelAsDataCallout() är lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Representerar ett specificerat diagramms datamärkningscellvärdes visningsbeteende. True visar cellvärdet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, får den här egenskapen eller ställer in standardvärdet för ShowLabelValueFromCell-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen. Sätt den här egenskapen med ett värde ställer också in detta värde på ShowLabelValueFromCell-egenskapen för alla datamärkningar i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" vilket gör att alla DataLabels.get_Item(i).getShowLabelValueFromCell() är lika med val).

**Returnerar:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Representerar ett specificerat diagramms datamärkningscellvärdes visningsbeteende. True visar cellvärdet. False döljer det. Läs/skriv boolean.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, får den här egenskapen eller ställer in standardvärdet för ShowLabelValueFromCell-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen. Sätt den här egenskapen med ett värde ställer också in detta värde på ShowLabelValueFromCell-egenskapen för alla datamärkningar i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" vilket gör att alla DataLabels.get_Item(i).getShowLabelValueFromCell() är lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Ställer in eller returnerar en Variant som representerar separatorn som används för datamärkningarna i ett diagram. Läs/skriv String.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, får den här egenskapen eller ställer in standardvärdet för Separator-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen. Sätt den här egenskapen med ett värde ställer också in detta värde på Separator-egenskapen för alla datamärkningar i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" vilket gör att alla DataLabels.get_Item(i).getSeparator() är lika med val).

**Returnerar:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Ställer in eller returnerar en Variant som representerar separatorn som används för datamärkningarna i ett diagram. Läs/skriv String.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, får den här egenskapen eller ställer in standardvärdet för Separator-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen. Sätt den här egenskapen med ett värde ställer också in detta värde på Separator-egenskapen för alla datamärkningar i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" vilket gör att alla DataLabels.get_Item(i).getSeparator() är lika med val).
**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |