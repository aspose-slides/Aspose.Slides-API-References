---
title: DataLabelFormat
second_title: Aspose.Slides för Android via Java API-referens
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

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Läs/skriv boolesk. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Läs/skriv boolesk. |
| [getNumberFormat()](#getNumberFormat--) | Representerar formatsträngen för DataLabels-objektet. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Representerar formatsträngen för DataLabels-objektet. |
| [getFormat()](#getFormat--) | Representerar formatet för datamärket. |
| [getPosition()](#getPosition--) | Representerar positionen för datamärket. |
| [setPosition(int value)](#setPosition-int-) | Representerar positionen för datamärket. |
| [getShowLegendKey()](#getShowLegendKey--) | Representerar ett specificerat diagrammets datamärkes legendnyckelns visningsbeteende. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Representerar ett specificerat diagrammets datamärkes legendnyckelns visningsbeteende. |
| [getShowValue()](#getShowValue--) | Representerar ett specificerat diagrammets procentsats för datamärket. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Representerar ett specificerat diagrammets procentsats för datamärket. |
| [getShowCategoryName()](#getShowCategoryName--) | Representerar ett specificerat diagrammets kategori-namns visningsbeteende för datamärket. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Representerar ett specificerat diagrammets kategori-namns visningsbeteende för datamärket. |
| [getShowSeriesName()](#getShowSeriesName--) | Returnerar eller anger en Boolean för att indikera serienamns visningsbeteende för datamärken på ett diagram. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Returnerar eller anger en Boolean för att indikera serienamns visningsbeteende för datamärken på ett diagram. |
| [getShowPercentage()](#getShowPercentage--) | Representerar ett specificerat diagrammets procentsats för datamärket. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Representerar ett specificerat diagrammets procentsats för datamärket. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Representerar ett specificerat diagrammets bubbelstorleksvärde för datamärket. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Representerar ett specificerat diagrammets bubbelstorleksvärde för datamärket. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Representerar ett specificerat diagrammets ledarlinjers visningsbeteende för datamärket. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Representerar ett specificerat diagrammets ledarlinjers visningsbeteende för datamärket. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Representerar ett specificerat diagrammets cellvärde för datamärket. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Representerar ett specificerat diagrammets cellvärde för datamärket. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Bestämmer om ett specificerat diagrammets datamärke ska visas som datautrop eller som datamärke. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Bestämmer om ett specificerat diagrammets datamärke ska visas som datautrop eller som datamärke. |
| [getSeparator()](#getSeparator--) | Anger eller returnerar en Variant som representerar separatorn som används för datamärken på ett diagram. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Anger eller returnerar en Variant som representerar separatorn som används för datamärken på ett diagram. |
| [getTextFormat()](#getTextFormat--) | Returnerar diagramtextformat. |
| [getChart()](#getChart--) | Returnerar diagrammet. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Endast läsning long.

**Returnerar:**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken, får denna egenskap eller sätter standardvärdet för IsNumberFormatLinkedToSource-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på IsNumberFormatLinkedToSource-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" får alla DataLabels.get_Item(i).isNumberFormatLinkedToSource() lika med val).

**Returnerar:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken, får denna egenskap eller sätter standardvärdet för IsNumberFormatLinkedToSource-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på IsNumberFormatLinkedToSource-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" får alla DataLabels.get_Item(i).isNumberFormatLinkedToSource() lika med val).

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

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken, får denna egenskap eller sätter standardvärdet för NumberFormat-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. När egenskapen sätts med ett värde, sätts samma värde även för NumberFormat-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" gör att alla DataLabels.get_Item(i).getNumberFormat() blir lika med val).

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

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken, får denna egenskap eller sätter standardvärdet för NumberFormat-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. När egenskapen sätts med ett värde, sätts samma värde även för NumberFormat-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" gör att alla DataLabels.get_Item(i).getNumberFormat() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Representerar formatet för datamärket. Endast läsning [IFormat](../../com.aspose.slides/iformat).

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken representerar denna egenskap standardformatet för de nya datamärkena i DataLabelCollection-samlingen.

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Representerar positionen för datamärket. Läs/skriv [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för Position-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Representerar positionen för DataLabel-objekten. Att sätta denna egenskap med ett värde sätter även detta värde på Position-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" gör att alla DataLabels.get_Item(i).getPosition() blir lika med val).

**Returnerar:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Representerar positionen för datamärket. Läs/skriv [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för Position-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Representerar positionen för DataLabel-objekten. Att sätta denna egenskap med ett värde sätter även detta värde på Position-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" gör att alla DataLabels.get_Item(i).getPosition() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Representerar ett specificerat diagrammets datamärkes legendnyckelns visningsbeteende. Sant om legendnyckeln för datamärket är synlig. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowLegendKey-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowLegendKey-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" gör att alla DataLabels.get_Item(i).getShowLegendKey() blir lika med val).

**Returnerar:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Representerar ett specificerat diagrammets datamärkes legendnyckelns visningsbeteende. Sant om legendnyckeln för datamärket är synlig. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowLegendKey-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowLegendKey-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" gör att alla DataLabels.get_Item(i).getShowLegendKey() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Representerar ett specificerat diagrammets datamärkes procentsatsvisningsbeteende. Sant visar procentsatsen. Falskt för att dölja. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowValue-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowValue-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" gör att alla DataLabels.get_Item(i).getShowValue() blir lika med val).

**Returnerar:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Representerar ett specificerat diagrammets datamärkes procentsatsvisningsbeteende. Sant visar procentsatsen. Falskt för att dölja. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowValue-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowValue-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" gör att alla DataLabels.get_Item(i).getShowValue() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Representerar ett specificerat diagrammets datamärkes kategori-namns visningsbeteende. Sant för att visa kategorinamnet för datamärkena på ett diagram. Falskt för att dölja. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowCategoryName-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowCategoryName-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" gör att alla DataLabels.get_Item(i).getShowCategoryName() blir lika med val).

**Returnerar:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Representerar ett specificerat diagrammets datamärkes kategori-namns visningsbeteende. Sant för att visa kategorinamnet för datamärkena på ett diagram. Falskt för att dölja. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowCategoryName-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowCategoryName-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" gör att alla DataLabels.get_Item(i).getShowCategoryName() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Returnerar eller anger en Boolean för att indikera serienamns visningsbeteende för datamärken på ett diagram. Sant för att visa serienamnet. Falskt för att dölja. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowSeriesName-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowSeriesName-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" gör att alla DataLabels.get_Item(i).getShowSeriesName() blir lika med val).

**Returnerar:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Returnerar eller anger en Boolean för att indikera serienamns visningsbeteende för datamärken på ett diagram. Sant för att visa serienamnet. Falskt för att dölja. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowSeriesName-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowSeriesName-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" gör att alla DataLabels.get_Item(i).getShowSeriesName() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Representerar ett specificerat diagrammets datamärkes procentsatsvisningsbeteende. Sant visar procentsatsen. Falskt för att dölja. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowPercentage-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowPercentage-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" gör att alla DataLabels.get_Item(i).getShowPercentage() blir lika med val).

**Returnerar:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Representerar ett specificerat diagrammets datamärkes procentsatsvisningsbeteende. Sant visar procentsatsen. Falskt för att dölja. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowPercentage-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowPercentage-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" gör att alla DataLabels.get_Item(i).getShowPercentage() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Representerar ett specificerat diagrammets datamärkes bubbelstorleksvärdesvisningsbeteende. Sant visar bubbelstorleksvärdet. Falskt för att dölja. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowBubbleSize-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowBubbleSize-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" gör att alla DataLabels.get_Item(i).getShowBubbleSize() blir lika med val).

**Returnerar:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Representerar ett specificerat diagrammets datamärkes bubbelstorleksvärdesvisningsbeteende. Sant visar bubbelstorleksvärdet. Falskt för att dölja. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowBubbleSize-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowBubbleSize-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" gör att alla DataLabels.get_Item(i).getShowBubbleSize() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Representerar ett specificerat diagrammets datamärkes ledarlinjers visningsbeteende. Sant visar ledarlinjerna. Falskt för att dölja. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowLeaderLines-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowLeaderLines-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" gör att alla DataLabels.get_Item(i).getShowLeaderLines() blir lika med val).

**Returnerar:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Representerar ett specificerat diagrammets datamärkes ledarlinjers visningsbeteende. Sant visar ledarlinjerna. Falskt för att dölja. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowLeaderLines-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowLeaderLines-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" gör att alla DataLabels.get_Item(i).getShowLeaderLines() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Representerar ett specificerat diagrammets datamärkes cellvärdesvisningsbeteende. Sant visar cellvärdet. Falskt för att dölja. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowLabelValueFromCell-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowLabelValueFromCell-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" gör att alla DataLabels.get_Item(i).getShowLabelValueFromCell() blir lika med val).

**Returnerar:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Representerar ett specificerat diagrammets datamärkes cellvärdesvisningsbeteende. Sant visar cellvärdet. Falskt för att dölja. Läs/skriv boolesk.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowLabelValueFromCell-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowLabelValueFromCell-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" gör att alla DataLabels.get_Item(i).getShowLabelValueFromCell() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Bestämmer om ett specificerat diagrammets datamärke ska visas som datautrop eller som datamärke.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowLabelAsDataCallout-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowLabelAsDataCallout-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" gör att alla DataLabels.get_Item(i).getShowLabelAsDataCallout() blir lika med val).

**Returnerar:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Bestämmer om ett specificerat diagrammets datamärke ska visas som datautrop eller som datamärke.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för ShowLabelAsDataCallout-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på ShowLabelAsDataCallout-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" gör att alla DataLabels.get_Item(i).getShowLabelAsDataCallout() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Ställer in eller returnerar en Variant som representerar separatorn som används för datamärken på ett diagram. Läs/skriv String.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för Separator-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på Separator-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" gör att alla DataLabels.get_Item(i).getSeparator() blir lika med val).

**Returnerar:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Ställer in eller returnerar en Variant som representerar separatorn som används för datamärken på ett diagram. Läs/skriv String.

--------------------

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken får denna egenskap eller sätter standardvärdet för Separator-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter även detta värde på Separator-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" gör att alla DataLabels.get_Item(i).getSeparator() blir lika med val).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Returnerar diagramtextformat. Endast läsning [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returnerar:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

Returnerar diagrammet. Endast läsning [IChart](../../com.aspose.slides/ichart).

**Returnerar:**
[IChart](../../com.aspose.slides/ichart)