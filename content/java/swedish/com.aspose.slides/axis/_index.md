---
title: Axis
second_title: Aspose.Slides för Java API-referens
description: Innesluter objektet som representerar ett diagramaxel.
type: docs
url: /sv/com.aspose.slides/axis/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Inkapslar objektet som representerar ett diagramaxel.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getChart()](#getChart--) | Returnerar det överordnade diagrammet. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Anger om värdeaxeln korsar kategoriaxeln mellan kategorier. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Anger om värdeaxeln korsar kategoriaxeln mellan kategorier. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Anger typen av kategoriaxeln. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Anger typen av kategoriaxeln. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Ställer in egenskapen IAxis.CategoryAxisType med ett värde som automatiskt bestäms baserat på axiadata. |
| [getCrossAt()](#getCrossAt--) | Anger punkten på axeln där den vinkelräta axilen korsar den. |
| [setCrossAt(float value)](#setCrossAt-float-) | Anger punkten på axeln där den vinkelräta axilen korsar den. |
| [getDisplayUnit()](#getDisplayUnit--) | Anger skalningsvärdet för visningsenheterna för värdeaxeln. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Anger skalningsvärdet för visningsenheterna för värdeaxeln. |
| [getActualMaxValue()](#getActualMaxValue--) | Anger faktiskt maximivärde på axeln. |
| [getActualMinValue()](#getActualMinValue--) | Anger faktiskt minimivärde på axeln. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Anger faktiskt huvud-enhet för axeln. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Anger faktiskt mindre enhet för axeln. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Anger faktiskt skala för huvud-enheten på axeln. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Anger faktiskt skala för mindre enhet på axeln. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Anger om maximivärdet tilldelas automatiskt. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Anger om maximivärdet tilldelas automatiskt. |
| [getMaxValue()](#getMaxValue--) | Representerar maximivärdet på värdeaxeln. |
| [setMaxValue(double value)](#setMaxValue-double-) | Representerar maximivärdet på värdeaxeln. |
| [getMinorUnit()](#getMinorUnit--) | Representerar de mindre enheterna för datum- eller värdeaxeln. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Representerar de mindre enheterna för datum- eller värdeaxeln. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Anger om den mindre enheten på axeln tilldelas automatiskt. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Anger om den mindre enheten på axeln tilldelas automatiskt. |
| [getMajorUnit()](#getMajorUnit--) | Representerar de större enheterna för datum- eller värdeaxeln. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Representerar de större enheterna för datum- eller värdeaxeln. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Anger om den större enheten på axeln tilldelas automatiskt. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Anger om den större enheten på axeln tilldelas automatiskt. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Anger om minimivärdet tilldelas automatiskt. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Anger om minimivärdet tilldelas automatiskt. |
| [getMinValue()](#getMinValue--) | Representerar minimivärdet på värdeaxeln. |
| [setMinValue(double value)](#setMinValue-double-) | Representerar minimivärdet på värdeaxeln. |
| [isLogarithmic()](#isLogarithmic--) | Anger om skalningstypen för värdeaxeln är logaritmisk eller inte. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Anger om skalningstypen för värdeaxeln är logaritmisk eller inte. |
| [getLogBase()](#getLogBase--) | Anger den logaritmiska basen. |
| [setLogBase(double value)](#setLogBase-double-) | Anger den logaritmiska basen. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Anger om MS PowerPoint plottar datapunkter från sista till första. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Anger om MS PowerPoint plottar datapunkter från sista till första. |
| [isVisible()](#isVisible--) | Anger om axeln är synlig. |
| [setVisible(boolean value)](#setVisible-boolean-) | Anger om axeln är synlig. |
| [getMajorTickMark()](#getMajorTickMark--) | Anger typen av huvud-stämpl för den angivna axeln. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Anger typen av huvud-stämpl för den angivna axeln. |
| [getMinorTickMark()](#getMinorTickMark--) | Anger typen av mindre stämpl för den angivna axeln. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Anger typen av mindre stämpl för den angivna axeln. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Anger positionen för stämpl-etiketter på den angivna axeln. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Anger positionen för stämpl-etiketter på den angivna axeln. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Anger skala för huvud-enheten för datumaxeln. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Anger skala för huvud-enheten för datumaxeln. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Anger skala för huvud-enheten för datumaxeln. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Anger skala för huvud-enheten för datumaxeln. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Anger den minsta tidsenheten som representeras på datumaxeln. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Anger den minsta tidsenheten som representeras på datumaxeln. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Representerar format för mindre rutnät på en diagramaxel. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Representerar format för större rutnät på en diagramaxel. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | För att dölja mindre rutnät, sätt MinorGridLinesFormat.Line.FillFormat.FillType till FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | För att dölja större rutnät, sätt MajorGridLinesFormat.Line.FillFormat.FillType till FillType.NoFill. |
| [getFormat()](#getFormat--) | Representerar format för axeln. |
| [getTextFormat()](#getTextFormat--) | Representerar format för text. |
| [getTitle()](#getTitle--) | Hämtar axelns titel. |
| [getCrossType()](#getCrossType--) | Representerar CrossType på den angivna axeln där den andra axeln korsar. |
| [setCrossType(int value)](#setCrossType-int-) | Representerar CrossType på den angivna axeln där den andra axeln korsar. |
| [getPosition()](#getPosition--) | Representerar positionen för axeln. |
| [setPosition(int value)](#setPosition-int-) | Representerar positionen för axeln. |
| [hasTitle()](#hasTitle--) | Avgör om en axel har en synlig titel. |
| [setTitle(boolean value)](#setTitle-boolean-) | Avgör om en axel har en synlig titel. |
| [getNumberFormat()](#getNumberFormat--) | Representerar formatsträngen för axel-etiketterna. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Representerar formatsträngen för axel-etiketterna. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Anger om formatet är länkat till källdata. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Anger om formatet är länkat till källdata. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Representerar rotationsvinkeln för stämpl-etiketter. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Representerar rotationsvinkeln för stämpl-etiketter. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Anger hur många stämpl-etiketter som ska hoppas över mellan etiketter som ritas. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Anger hur många stämpl-etiketter som ska hoppas över mellan etiketter som ritas. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Anger automatiskt avstånd mellan stämpl-etiketter. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Anger automatiskt avstånd mellan stämpl-etiketter. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Anger hur många stämpl-markeringar som ska hoppas över innan nästa ritas. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Anger hur många stämpl-markeringar som ska hoppas över innan nästa ritas. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Anger automatiskt avstånd mellan stämpl-markeringar. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Anger automatiskt avstånd mellan stämpl-markeringar. |
| [getLabelOffset()](#getLabelOffset--) | Anger avståndet för etiketter från axeln. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Anger avståndet för etiketter från axeln. |
| [getAggregationType()](#getAggregationType--) | Representerar aggregeringstyp för kategoriaxel (gruppering). |
| [setAggregationType(int value)](#setAggregationType-int-) | Representerar aggregeringstyp för kategoriaxel (gruppering). |
| [getBinWidth()](#getBinWidth--) | Anger bin-bredd när AggregationType-egenskapens värde är AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Anger bin-bredd när AggregationType-egenskapens värde är AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Anger antal bin när AggregationType-egenskapens värde är AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Anger antal bin när AggregationType-egenskapens värde är AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Anger om overflow-bin tillämpas. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Anger om overflow-bin tillämpas. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Anger automatiskt overflow-bin-värde. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Anger automatiskt overflow-bin-värde. |
| [getOverflowBin()](#getOverflowBin--) | Anger anpassat overflow-bin-värde. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Anger anpassat overflow-bin-värde. |
| [isUnderflowBin()](#isUnderflowBin--) | Anger om underflow-bin tillämpas. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Anger om underflow-bin tillämpas. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Anger automatiskt underflow-bin-värde. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Anger automatiskt underflow-bin-värde. |
| [getUnderflowBin()](#getUnderflowBin--) | Anger anpassat underflow-bin-värde. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Anger anpassat underflow-bin-värde. |
| [getSlide()](#getSlide--) | Returnerar den överordnade bilden för ett FillFormat. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för ett FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Returnerar det överordnade diagrammet. Skrivskyddad [IChart](../../com.aspose.slides/ichart).

**Returvärde:**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Anger om värdeaxeln korsar kategoriaxeln mellan kategorier. Denna egenskap gäller endast för kategoriaxlar och gäller inte för 3-D-diagram. Läs/skriv boolesk.

**Returvärde:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Anger om värdeaxeln korsar kategoriaxeln mellan kategorier. Denna egenskap gäller endast för kategoriaxlar och gäller inte för 3-D-diagram. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Anger typen av kategoriaxeln. Läs/skriv [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Returvärde:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Anger typen av kategoriaxeln. Läs/skriv [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Ställer in egenskapen IAxis.CategoryAxisType med ett värde som automatiskt bestäms baserat på axiadata.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Anger punkten på axeln där den vinkelräta axilen korsar den. Läs/skriv float.

**Returvärde:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Anger punkten på axeln där den vinkelräta axilen korsar den. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Anger skalningsvärdet för visningsenheterna för värdeaxeln. Läs/skriv [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Returvärde:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Anger skalningsvärdet för visningsenheterna för värdeaxeln. Läs/skriv [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Anger faktiskt maximivärde på axeln. Anropa metoden IChart.ValidateChartLayout() innan för att få det faktiska värdet.

**Returvärde:**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Anger faktiskt minimivärde på axeln. Anropa metoden IChart.ValidateChartLayout() innan för att få det faktiska värdet.

**Returvärde:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Anger faktiskt huvud-enhet för axeln. Anropa metoden IChart.ValidateChartLayout() innan för att få det faktiska värdet.

**Returvärde:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Anger faktiskt mindre enhet för axeln. Anropa metoden IChart.ValidateChartLayout() innan för att få det faktiska värdet.

**Returvärde:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Anger faktiskt skala för huvud-enheten på axeln. Anropa metoden IChart.ValidateChartLayout() innan för att få det faktiska värdet.

**Returvärde:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Anger faktiskt skala för mindre enhet på axeln. Anropa metoden IChart.ValidateChartLayout() innan för att få det faktiska värdet.

**Returvärde:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Anger om maximivärdet tilldelas automatiskt. Läs/skriv boolesk.

**Returvärde:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Anger om maximivärdet tilldelas automatiskt. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Representerar maximivärdet på värdeaxeln. Läs/skriv double.

**Returvärde:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Representerar maximivärdet på värdeaxeln. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Representerar de mindre enheterna för datum- eller värdeaxeln. Läs/skriv double.

**Returvärde:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Representerar de mindre enheterna för datum- eller värdeaxeln. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
Indikerar om den mindre enheten för axeln tilldelas automatiskt. Läs/skriv boolean.

**Returnerar:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```


Indikerar om den mindre enheten för axeln tilldelas automatiskt. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```


Representerar de stora enheterna för datum- eller värdeaxeln. Läs/skriv double.

**Returnerar:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```


Representerar de stora enheterna för datum- eller värdeaxeln. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```


Indikerar om den stora enheten för axeln tilldelas automatiskt. Läs/skriv boolean.

**Returnerar:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```


Indikerar om den stora enheten för axeln tilldelas automatiskt. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```


Indikerar om minimivärdet tilldelas automatiskt. Läs/skriv boolean.

**Returnerar:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```


Indikerar om minimivärdet tilldelas automatiskt. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```


Representerar minimivärdet på värdeaxeln. Läs/skriv double.

**Returnerar:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```


Representerar minimivärdet på värdeaxeln. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```


Representerar om värdeaxelns skala är logaritmisk eller inte. Läs/skriv boolean.

**Returnerar:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```


Representerar om värdeaxelns skala är logaritmisk eller inte. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```


Representerar den logaritmiska basen. Standardvärdet är 10. Läs/skriv double.

**Returnerar:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```


Representerar den logaritmiska basen. Standardvärdet är 10. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```


Representerar om MS PowerPoint ritar datapunkter från sista till första. Läs/skriv boolean.

**Returnerar:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```


Representerar om MS PowerPoint ritar datapunkter från sista till första. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Representerar om axeln är synlig. Läs/skriv boolean.

**Returnerar:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Representerar om axeln är synlig. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```


Representerar typen av major tick mark för den angivna axeln. Läs/skriv [TickMarkType](../../com.aspose.slides/tickmarktype).

**Returnerar:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```


Representerar typen av major tick mark för den angivna axeln. Läs/skriv [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```


Representerar typen av minor tick mark för den angivna axeln. Läs/skriv [TickMarkType](../../com.aspose.slides/tickmarktype).

**Returnerar:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```


Representerar typen av minor tick mark för den angivna axeln. Läs/skriv [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```


Representerar positionen för tick-etikettmarkeringar på den angivna axeln. Läs/skriv [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Returnerar:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```


Representerar positionen för tick-etikettmarkeringar på den angivna axeln. Läs/skriv [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```


Representerar den stora enhetsskalan för datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returnerar:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```


Representerar den stora enhetsskalan för datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```


Representerar den stora enhetsskalan för datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returnerar:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```


Representerar den stora enhetsskalan för datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```


Anger den minsta tidsenheten som representeras på datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returnerar:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```


Anger den minsta tidsenheten som representeras på datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


Representerar formatet för mindre rutnätlinjer på ett diagram. Endast läsning [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Returnerar:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```


Representerar formatet för större rutnätlinjer på ett diagram. Endast läsning [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Returnerar:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```


För att dölja mindre rutnätlinjer, sätt MinorGridLinesFormat.Line.FillFormat.FillType till FillType.NoFill. Endast läsning boolean.

**Returnerar:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```


För att dölja större rutnätlinjer, sätt MajorGridLinesFormat.Line.FillFormat.FillType till FillType.NoFill. Endast läsning boolean.

**Returnerar:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```


Representerar formatet för axeln. Endast läsning [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Returnerar:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Representerar formatet för text. Endast läsning [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returnerar:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```


Hämtar axelns titel. Endast läsning [IChartTitle](../../com.aspose.slides/icharttitle).

**Returnerar:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```


Representerar CrossType på den angivna axeln där den andra axeln korsar. Läs/skriv [CrossesType](../../com.aspose.slides/crossestype).

**Returnerar:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```


Representerar CrossType på den angivna axeln där den andra axeln korsar. Läs/skriv [CrossesType](../../com.aspose.slides/crossestype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


Representerar axelns position. Läs/skriv [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Returnerar:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Representerar axelns position. Läs/skriv [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


Avgör om en axel har en synlig titel. Läs/skriv boolean.

**Returnerar:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


Avgör om en axel har en synlig titel. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


Representerar formatsträngen för axelns etiketter. Läs/skriv String.

**Returnerar:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


Representerar formatsträngen för axelns etiketter. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


Indikerar om formatet är länkat till källdata. Läs/skriv boolean.

**Returnerar:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


Indikerar om formatet är länkat till källdata. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```


Representerar rotationsvinkeln för tick-etiketter. Läs/skriv float.

**Returnerar:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```


Representerar rotationsvinkeln för tick-etiketter. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```


Anger hur många tick-etiketter som ska hoppas över mellan etiketter som ritas. Tillämpas på kategori- eller serieregor. Läs/skriv long.

**Returnerar:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```


Anger hur många tick-etiketter som ska hoppas över mellan etiketter som ritas. Tillämpas på kategori- eller serieregor. Läs/skriv long.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```


Anger automatiskt värde för tick-etikettavstånd. Om falskt: använd TickLabelSpacing-egenskapen. Läs/skriv boolean.

**Returnerar:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```


Anger automatiskt värde för tick-etikettavstånd. Om falskt: använd TickLabelSpacing-egenskapen. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```


Anger hur många tick-markeringar som ska hoppas över innan nästa ritas. Tillämpas på kategori- eller serieregor. Läs/skriv int.

**Returnerar:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```


Anger hur många tick-markeringar som ska hoppas över innan nästa ritas. Tillämpas på kategori- eller serieregor. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```


Anger automatiskt värde för tick-markeringars avstånd. Om falskt: använd TickMarksSpacing-egenskapen. Läs/skriv boolean.

**Returnerar:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```


Anger automatiskt värde för tick-markeringars avstånd. Om falskt: använd TickMarksSpacing-egenskapen. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```


Anger avståndet för etiketter från axeln. Tillämpas på kategori- eller datumaxel. Värdet måste vara mellan 0 % och 1000 %. Läs/skriv int.

**Returnerar:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```


Anger avståndet för etiketter från axeln. Tillämpas på kategori- eller datumaxel. Värdet måste vara mellan 0 % och 1000 %. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Representerar aggregations typ för kategoriaxel (gruppering). Tillämpar på kategori. Används endast med Histogram- eller HistogramPareto-serier.

**Returnerar:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Representerar aggregations typ för kategoriaxel (gruppering). Tillämpar på kategori. Används endast med Histogram- eller HistogramPareto-serier.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Anger binbredd när AggregationType-egenskapens värde är satt till AxisAggregationType.ByBinWidth. Tillämpar på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier.

**Returnerar:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Anger binbredd när AggregationType-egenskapens värde är satt till AxisAggregationType.ByBinWidth. Tillämpar på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Anger antal bin när AggregationType-egenskapens värde är satt till AxisAggregationType.ByNumberOfBins. Tillämpar på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier.

**Returnerar:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Anger antal bin när AggregationType-egenskapens värde är satt till AxisAggregationType.ByNumberOfBins. Tillämpar på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |
### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Anger om overflow-bin tillämpas. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-binvärdet.

**Returnerar:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Anger om overflow-bin tillämpas. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-binvärdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Anger automatiskt overflow-binvärde. Om falskt: använd OverflowBin-egenskapen.

**Returnerar:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Anger automatiskt overflow-binvärde. Om falskt: använd OverflowBin-egenskapen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Anger anpassat värde för overflow-bin. Tillämpar när IsAutomaticOverflowBin-egenskapen är satt till falskt och IsOverflowBin-egenskapen är sann.

**Returnerar:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Anger anpassat värde för overflow-bin. Tillämpar när IsAutomaticOverflowBin-egenskapen är satt till falskt och IsOverflowBin-egenskapen är sann.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Anger om underflow-bin tillämpas. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-binvärdet.

**Returnerar:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Anger om underflow-bin tillämpas. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-binvärdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Anger automatiskt underflow-binvärde. Om falskt: använd UnderflowBin-egenskapen.

**Returnerar:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Anger automatiskt underflow-binvärde. Om falskt: använd UnderflowBin-egenskapen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Anger anpassat värde för underflow-bin. Tillämpar när IsAutomaticUnderflowBin-egenskapen är satt till falskt och IsUnderflowBin-egenskapen är sann.

**Returnerar:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Anger anpassat värde för underflow-bin. Tillämpar när IsAutomaticUnderflowBin-egenskapen är satt till falskt och IsUnderflowBin-egenskapen är sann.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar den överordnade bilden för ett FillFormat. Skrivskyddad [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar den överordnade presentationen för ett FillFormat. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)