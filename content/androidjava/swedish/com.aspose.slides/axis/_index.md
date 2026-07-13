---
title: Axis
second_title: Aspose.Slides för Android via Java API-referens
description: Inkapslar objektet som representerar ett diagramaxel.
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
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Representerar om värdeaxeln korsar kategoriaxeln mellan kategorier. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Representerar om värdeaxeln korsar kategoriaxeln mellan kategorier. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Anger typen av kategoriaxeln. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Anger typen av kategoriaxeln. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Sätter IAxis.CategoryAxisType-egenskapen med ett värde som automatiskt bestäms baserat på axis data. |
| [getCrossAt()](#getCrossAt--) | Representerar punkten på axeln där den vinkelräta axeln korsar den. |
| [setCrossAt(float value)](#setCrossAt-float-) | Representerar punkten på axeln där den vinkelräta axeln korsar den. |
| [getDisplayUnit()](#getDisplayUnit--) | Anger skalningsvärdet för displayenheterna för värdeaxeln. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Anger skalningsvärdet för displayenheterna för värdeaxeln. |
| [getActualMaxValue()](#getActualMaxValue--) | Anger det faktiska maximala värdet på axeln. |
| [getActualMinValue()](#getActualMinValue--) | Anger det faktiska minimala värdet på axeln. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Anger den faktiska huvudenheten för axeln. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Anger den faktiska mindre enheten för axeln. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Anger den faktiska huvudenhetsskalan för axeln. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Anger den faktiska mindre enhetsskalan för axeln. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Indikerar om maxvärdet tilldelas automatiskt. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Indikerar om maxvärdet tilldelas automatiskt. |
| [getMaxValue()](#getMaxValue--) | Representerar det maximala värdet på värdeaxeln. |
| [setMaxValue(double value)](#setMaxValue-double-) | Representerar det maximala värdet på värdeaxeln. |
| [getMinorUnit()](#getMinorUnit--) | Representerar de mindre enheterna för datum- eller värdeaxeln. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Representerar de mindre enheterna för datum- eller värdeaxeln. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indikerar om den mindre enheten för axeln tilldelas automatiskt. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indikerar om den mindre enheten för axeln tilldelas automatiskt. |
| [getMajorUnit()](#getMajorUnit--) | Representerar huvudenheterna för datum- eller värdeaxeln. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Representerar huvudenheterna för datum- eller värdeaxeln. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Indikerar om huvudenheten för axeln tilldelas automatiskt. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Indikerar om huvudenheten för axeln tilldelas automatiskt. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Indikerar om minvärdet tilldelas automatiskt. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Indikerar om minvärdet tilldelas automatiskt. |
| [getMinValue()](#getMinValue--) | Representerar det minimala värdet på värdeaxeln. |
| [setMinValue(double value)](#setMinValue-double-) | Representerar det minimala värdet på värdeaxeln. |
| [isLogarithmic()](#isLogarithmic--) | Representerar om skaletypen för värdeaxeln är logaritmisk eller inte. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Representerar om skaletypen för värdeaxeln är logaritmisk eller inte. |
| [getLogBase()](#getLogBase--) | Representerar den logaritmiska basen. |
| [setLogBase(double value)](#setLogBase-double-) | Representerar den logaritmiska basen. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Representerar om MS PowerPoint ritar datapunkter från sista till första. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Representerar om MS PowerPoint ritar datapunkter från sista till första. |
| [isVisible()](#isVisible--) | Representerar om axeln är synlig. |
| [setVisible(boolean value)](#setVisible-boolean-) | Representerar om axeln är synlig. |
| [getMajorTickMark()](#getMajorTickMark--) | Representerar typen av huvudtickmarkering för den angivna axeln. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Representerar typen av huvudtickmarkering för den angivna axeln. |
| [getMinorTickMark()](#getMinorTickMark--) | Representerar typen av mindre tickmarkering för den angivna axeln. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Representerar typen av mindre tickmarkering för den angivna axeln. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Representerar positionen för tick-etikettmarkeringar på den angivna axeln. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Representerar positionen för tick-etikettmarkeringar på den angivna axeln. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Representerar huvudenhetsskalan för datumaxeln. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Representerar huvudenhetsskalan för datumaxeln. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Representerar huvudenhetsskalan för datumaxeln. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Representerar huvudenhetsskalan för datumaxeln. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Anger den minsta tidsenheten som representeras på datumaxeln. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Anger den minsta tidsenheten som representeras på datumaxeln. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Representerar formatet för mindre rutnätlinjer på en diagramaxel. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Representerar formatet för större rutnätlinjer på en diagramaxel. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | För att dölja mindre rutnätlinje, sätt MinorGridLinesFormat.Line.FillFormat.FillType till FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | För att dölja större rutnätlinje, sätt MajorGridLinesFormat.Line.FillFormat.FillType till FillType.NoFill. |
| [getFormat()](#getFormat--) | Representerar formatet för axeln. |
| [getTextFormat()](#getTextFormat--) | Representerar formatet för text. |
| [getTitle()](#getTitle--) | Hämtar axelns titel. |
| [getCrossType()](#getCrossType--) | Representerar CrossType på den angivna axeln där den andra axeln korsar. |
| [setCrossType(int value)](#setCrossType-int-) | Representerar CrossType på den angivna axeln där den andra axeln korsar. |
| [getPosition()](#getPosition--) | Representerar positionen för axeln. |
| [setPosition(int value)](#setPosition-int-) | Representerar positionen för axeln. |
| [hasTitle()](#hasTitle--) | Avgör om en axel har en synlig titel. |
| [setTitle(boolean value)](#setTitle-boolean-) | Avgör om en axel har en synlig titel. |
| [getNumberFormat()](#getNumberFormat--) | Representerar formatsträngen för axelrubrikerna. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Representerar formatsträngen för axelrubrikerna. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Indikerar om formatet är länkat till källdata. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Indikerar om formatet är länkat till källdata. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Representerar rotationsvinkeln för tick-etiketterna. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Representerar rotationsvinkeln för tick-etiketterna. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Anger hur många tick-etiketter som ska hoppas över mellan de som ritas. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Anger hur många tick-etiketter som ska hoppas över mellan de som ritas. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Anger automatiskt avstånd för tick-etiketter. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Anger automatiskt avstånd för tick-etiketter. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Anger hur många tick-markeringar som ska hoppas över innan nästa ritas. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Anger hur många tick-markeringar som ska hoppas över innan nästa ritas. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Anger automatiskt avstånd för tick-markeringar. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Anger automatiskt avstånd för tick-markeringar. |
| [getLabelOffset()](#getLabelOffset--) | Anger avståndet för etiketter från axeln. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Anger avståndet för etiketter från axeln. |
| [getAggregationType()](#getAggregationType--) | Representerar aggregeringstyp för kategoriaxeln (binning). |
| [setAggregationType(int value)](#setAggregationType-int-) | Representerar aggregeringstyp för kategoriaxeln (binning). |
| [getBinWidth()](#getBinWidth--) | Anger binbredd när AggregationType-egenskapens värde är satt till AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Anger binbredd när AggregationType-egenskapens värde är satt till AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Anger antal bins när AggregationType-egenskapens värde är satt till AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Anger antal bins när AggregationType-egenskapens värde är satt till AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Anger om overflow-bin används. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Anger om overflow-bin används. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Anger automatiskt overflow-bin-värde. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Anger automatiskt overflow-bin-värde. |
| [getOverflowBin()](#getOverflowBin--) | Anger anpassat värde för overflow-bin. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Anger anpassat värde för overflow-bin. |
| [isUnderflowBin()](#isUnderflowBin--) | Anger om underflow-bin används. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Anger om underflow-bin används. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Anger automatiskt underflow-bin-värde. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Anger automatiskt underflow-bin-värde. |
| [getUnderflowBin()](#getUnderflowBin--) | Anger anpassat värde för underflow-bin. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Anger anpassat värde för underflow-bin. |
| [getSlide()](#getSlide--) | Returnerar den överordnade bilden för ett FillFormat. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för ett FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Returnerar det överordnade diagrammet. Endast läsning [IChart](../../com.aspose.slides/ichart).

**Returnerar:**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Representerar om värdeaxeln korsar kategoriaxeln mellan kategorier. Denna egenskap gäller endast för kategoriaxlar och gäller inte för 3-D-diagram. Läs/skriv boolesk.

**Returnerar:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Representerar om värdeaxeln korsar kategoriaxeln mellan kategorier. Denna egenskap gäller endast för kategoriaxlar och gäller inte för 3-D-diagram. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Anger typen av kategoriaxeln. Läs/skriv [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Returnerar:**
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

Sätter IAxis.CategoryAxisType-egenskapen med ett värde som automatiskt bestäms baserat på axis data.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Representerar punkten på axeln där den vinkelräta axeln korsar den. Läs/skriv float.

**Returnerar:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Representerar punkten på axeln där den vinkelräta axeln korsar den. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Anger skalningsvärdet för displayenheterna för värdeaxeln. Läs/skriv [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Returnerar:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Anger skalningsvärdet för displayenheterna för värdeaxeln. Läs/skriv [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Anger det faktiska maximala värdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet.

**Returnerar:**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Anger det faktiska minimala värdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet.

**Returnerar:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Anger den faktiska huvudenheten för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet.

**Returnerar:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Anger den faktiska mindre enheten för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet.

**Returnerar:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Anger den faktiska huvudenhetsskalan för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet.

**Returnerar:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Anger den faktiska mindre enhetsskalan för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet.

**Returnerar:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Indikerar om maxvärdet tilldelas automatiskt. Läs/skriv boolesk.

**Returnerar:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Indikerar om maxvärdet tilldelas automatiskt. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Representerar det maximala värdet på värdeaxeln. Läs/skriv double.

**Returnerar:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Representerar det maximala värdet på värdeaxeln. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Representerar de mindre enheterna för datum- eller värdeaxeln. Läs/skriv double.

**Returnerar:**
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

Indikerar om den mindre enheten för axeln tilldelas automatiskt. Läs/skriv boolesk.

**Returnerar:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

Indikerar om den mindre enheten för axeln tilldelas automatiskt. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

Representerar huvudenheterna för datum- eller värdeaxeln. Läs/skriv double.

**Returnerar:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

Representerar huvudenheterna för datum- eller värdeaxeln. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

Indikerar om huvudenheten för axeln tilldelas automatiskt. Läs/skriv boolesk.

**Returnerar:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

Indikerar om huvudenheten för axeln tilldelas automatiskt. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

Indikerar om minvärdet tilldelas automatiskt. Läs/skriv boolesk.

**Returnerar:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

Indikerar om minvärdet tilldelas automatiskt. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

Representerar det minimala värdet på värdeaxeln. Läs/skriv double.

**Returnerar:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

Representerar det minimala värdet på värdeaxeln. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

Representerar om skaletypen för värdeaxeln är logaritmisk eller inte. Läs/skriv boolesk.

**Returnerar:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

Representerar om skaletypen för värdeaxeln är logaritmisk eller inte. Läs/skriv boolesk.

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

Representerar om MS PowerPoint ritar datapunkter från sista till första. Läs/skriv boolesk.

**Returnerar:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

Representerar om MS PowerPoint ritar datapunkter från sista till första. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Representerar om axeln är synlig. Läs/skriv boolesk.

**Returnerar:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Representerar om axeln är synlig. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

Representerar typen av huvudtickmarkering för den angivna axeln. Läs/skriv [TickMarkType](../../com.aspose.slides/tickmarktype).

**Returnerar:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

Representerar typen av huvudtickmarkering för den angivna axeln. Läs/skriv [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

Representerar typen av mindre tickmarkering för den angivna axeln. Läs/skriv [TickMarkType](../../com.aspose.slides/tickmarktype).

**Returnerar:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public



```

Representerar typen av mindre tickmarkering för den angivna axeln. Läs/skriv [TickMarkType](../../com.aspose.slides/tickmarktype).

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

Representerar huvudenhetsskalan för datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returnerar:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

Representerar huvudenhetsskalan för datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

Representerar huvudenhetsskalan för datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returnerar:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

Representerar huvudenhetsskalan för datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

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

Representerar formatet för mindre rutnätlinjer på en diagramaxel. Endast läsning [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Returnerar:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

Representerar formatet för större rutnätlinjer på en diagramaxel. Endast läsning [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Returnerar:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

För att dölja mindre rutnätlinje, sätt MinorGridLinesFormat.Line.FillFormat.FillType till FillType.NoFill. Endast läsning boolesk.

**Returnerar:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

För att dölja större rutnätlinje, sätt MajorGridLinesFormat.Line.FillFormat.FillType till FillType.NoFill. Endast läsning boolesk.

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

Representerar positionen för axeln. Läs/skriv [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Returnerar:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Representerar positionen för axeln. Läs/skriv [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Avgör om en axel har en synlig titel. Läs/skriv boolesk.

**Returnerar:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Avgör om en axel har en synlig titel. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Representerar formatsträngen för axelrubrikerna. Läs/skriv String.

**Returnerar:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Representerar formatsträngen för axelrubrikerna. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Indikerar om formatet är länkat till källdata. Läs/skriv boolesk.

**Returnerar:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Indikerar om formatet är länkat till källdata. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

Representerar rotationsvinkeln för tick-etiketterna. Läs/skriv float.

**Returnerar:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

Representerar rotationsvinkeln för tick-etiketterna. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

Anger hur många tick-etiketter som ska hoppas över mellan de som ritas. Tillämpas på kategori- eller seriesaxlar. Läs/skriv long.

**Returnerar:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

Anger hur många tick-etiketter som ska hoppas över mellan de som ritas. Tillämpas på kategori- eller seriesaxlar. Läs/skriv long.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

Anger automatiskt avstånd för tick-etiketter. Om falskt: använd TickLabelSpacing-egenskapen. Läs/skriv boolesk.

**Returnerar:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

Anger automatiskt avstånd för tick-etiketter. Om falskt: använd TickLabelSpacing-egenskapen. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

Anger hur många tick-markeringar som ska hoppas över innan nästa ritas. Tillämpas på kategori- eller seriesaxlar. Läs/skriv int.

**Returnerar:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

Anger hur många tick-markeringar som ska hoppas över innan nästa ritas. Tillämpas på kategori- eller seriesaxlar. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

Anger automatiskt avstånd för tick-markeringar. Om falskt: använd TickMarksSpacing-egenskapen. Läs/skriv boolesk.

**Returnerar:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

Anger automatiskt avstånd för tick-markeringar. Om falskt: använd TickMarksSpacing-egenskapen. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

Anger avståndet för etiketter från axeln. Tillämpas på kategori- eller datumaxlar. Värdet måste vara mellan 0 % och 1000 %. Läs/skriv int.

**Returnerar:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

Anger avståndet för etiketter från axeln. Tillämpas på kategori- eller datumaxlar. Värdet måste vara mellan 0 % och 1000 %. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Representerar aggregeringstyp för kategoriaxeln (binning). Tillämpas på kategori. Används endast med Histogram- eller HistogramPareto-serier.

**Returnerar:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Representerar aggregeringstyp för kategoriaxeln (binning). Tillämpas på kategori. Används endast med Histogram- eller HistogramPareto-serier.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Anger binbredd när AggregationType-egenskapens värde är satt till AxisAggregationType.ByBinWidth. Tillämpas på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier.

**Returnerar:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Anger binbredd när AggregationType-egenskapens värde är satt till AxisAggregationType.ByBinWidth. Tillämpas på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Anger antal bins när AggregationType-egenskapens värde är satt till AxisAggregationType.ByNumberOfBins. Tillämpas på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier.

**Returnerar:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Anger antal bins när AggregationType-egenskapens värde är satt till AxisAggregationType.ByNumberOfBins. Tillämpas på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Anger om overflow-bin används. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-bin-värdet.

**Returnerar:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Anger om overflow-bin används. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-bin-värdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Anger automatiskt overflow-bin-värde. Om falskt: använd OverflowBin-egenskapen.

**Returnerar:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Anger automatiskt overflow-bin-värde. Om falskt: använd OverflowBin-egenskapen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Anger overflow-bin-anpassat värde. Tillämpas när IsAutomaticOverflowBin-egenskapen är falsk och IsOverflowBin-egenskapen är sann.

**Returnerar:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Anger overflow-bin-anpassat värde. Tillämpas när IsAutomaticOverflowBin-egenskapen är falsk och IsOverflowBin-egenskapen är sann.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Anger om underflow-bin används. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-bin-värdet.

**Returnerar:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Anger om underflow-bin används. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-bin-värdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Anger automatiskt underflow-bin-värde. Om falskt: använd UnderflowBin-egenskapen.

**Returnerar:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Anger automatiskt underflow-bin-värde. Om falskt: använd UnderflowBin-egenskapen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Anger underflow-bin-anpassat värde. Tillämpas när IsAutomaticUnderflowBin-egenskapen är falsk och IsUnderflowBin-egenskapen är sann.

**Returnerar:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Anger underflow-bin-anpassat värde. Tillämpas när IsAutomaticUnderflowBin-egenskapen är falsk och IsUnderflowBin-egenskapen är sann.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar den överordnade bilden för ett FillFormat. Endast läsning [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar den överordnade presentationen för ett FillFormat. Endänd läsning [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)