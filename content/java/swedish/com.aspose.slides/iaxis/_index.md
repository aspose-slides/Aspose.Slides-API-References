---
title: IAxis
second_title: Aspose.Slides för Java API-referens
description: Inkapslar objektet som representerar ett diagramaxel.
type: docs
url: /sv/com.aspose.slides/iaxis/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Inkapslar objektet som representerar ett diagramaxel.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Representerar om värdeaxeln korsar kategoriaxeln mellan kategorier. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Representerar om värdeaxeln korsar kategoriaxeln mellan kategorier. |
| [getCrossAt()](#getCrossAt--) | Representerar punkten på axeln där den vinkelräta axeln korsar den. |
| [setCrossAt(float value)](#setCrossAt-float-) | Representerar punkten på axeln där den vinkelräta axeln korsar den. |
| [getDisplayUnit()](#getDisplayUnit--) | Anger skalningsvärdet för displayenheterna för värdeaxeln. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Anger skalningsvärdet för displayenheterna för värdeaxeln. |
| [getActualMaxValue()](#getActualMaxValue--) | Anger det faktiska maximala värdet på axeln. |
| [getActualMinValue()](#getActualMinValue--) | Anger det faktiska minimala värdet på axeln. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Anger den faktiska huvudenheten för axeln. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Anger den faktiska sekundära enheten för axeln. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Anger den faktiska skalan för huvudenheten på axeln. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Anger den faktiska skalan för sekundära enheten på axeln. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Indikerar om maxvärdet tilldelas automatiskt. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Indikerar om maxvärdet tilldelas automatiskt. |
| [getMaxValue()](#getMaxValue--) | Representerar det maximala värdet på värdeaxeln. |
| [setMaxValue(double value)](#setMaxValue-double-) | Representerar det maximala värdet på värdeaxeln. |
| [getMinorUnit()](#getMinorUnit--) | Representerar de sekundära enheterna för datum- eller värdeaxeln. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Representerar de sekundära enheterna för datum- eller värdeaxeln. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indikerar om den sekundära enheten för axeln tilldelas automatiskt. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indikerar om den sekundära enheten för axeln tilldelas automatiskt. |
| [getMajorUnit()](#getMajorUnit--) | Representerar huvudenheterna för datum- eller värdeaxeln. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Representerar huvudenheterna för datum- eller värdeaxeln. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Indikerar om huvudenheten för axeln tilldelas automatiskt. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Indikerar om huvudenheten för axeln tilldelas automatiskt. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Indikerar om minvärdet tilldelas automatiskt. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Indikerar om minvärdet tilldelas automatiskt. |
| [getMinValue()](#getMinValue--) | Representerar det minsta värdet på värdeaxeln. |
| [setMinValue(double value)](#setMinValue-double-) | Representerar det minsta värdet på värdeaxeln. |
| [isLogarithmic()](#isLogarithmic--) | Representerar om skaletypen för värdeaxeln är logaritmisk eller ej. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Representerar om skaletypen för värdeaxeln är logaritmisk eller ej. |
| [getLogBase()](#getLogBase--) | Representerar den logaritmiska basen. |
| [setLogBase(double value)](#setLogBase-double-) | Representerar den logaritmiska basen. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Representerar om MS PowerPoint ritar datapunkter från sista till första. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Representerar om MS PowerPoint ritar datapunkter från sista till första. |
| [isVisible()](#isVisible--) | Representerar om axeln är synlig. |
| [setVisible(boolean value)](#setVisible-boolean-) | Representerar om axeln är synlig. |
| [getMajorTickMark()](#getMajorTickMark--) | Representerar typen av huvudstopp för den angivna axeln. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Representerar typen av huvudstopp för den angivna axeln. |
| [getMinorTickMark()](#getMinorTickMark--) | Representerar typen av sekundär stopp för den angivna axeln. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Representerar typen av sekundär stopp för den angivna axeln. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Representerar positionen för stapelmärkningarnas etiketter på den angivna axeln. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Representerar positionen för stapelmärkningarnas etiketter på den angivna axeln. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Representerar huvudenhetsskalan för datumaxeln. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Representerar huvudenhetsskalan för datumaxeln. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Representerar huvudenhetsskalan för datumaxeln. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Representerar huvudenhetsskalan för datumaxeln. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Anger den minsta tidsenheten som representeras på datumaxeln. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Anger den minsta tidsenheten som representeras på datumaxeln. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Representerar formatet för mindre rutnät på ett diagramaxel. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Representerar formatet för huvudrutnät på ett diagramaxel. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Representerar om de mindre rutnäten visas. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Representerar om huvudrutnäten visas. |
| [getFormat()](#getFormat--) | Representerar formatet för axeln. |
| [getTitle()](#getTitle--) | Hämtar axelns titel. |
| [getCrossType()](#getCrossType--) | Representerar CrossType på den angivna axeln där den andra axeln korsar. |
| [setCrossType(int value)](#setCrossType-int-) | Representerar CrossType på den angivna axeln där den andra axeln korsar. |
| [getPosition()](#getPosition--) | Representerar axelns position. |
| [setPosition(int value)](#setPosition-int-) | Representerar axelns position. |
| [hasTitle()](#hasTitle--) | Bestämmer om en axel har en synlig titel. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bestämmer om en axel har en synlig titel. |
| [getNumberFormat()](#getNumberFormat--) | Representerar formatsträngen för axelrubrikerna. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Representerar formatsträngen för axelrubrikerna. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Indikerar om formatet är länkat till källdata. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Indikerar om formatet är länkat till källdata. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Representerar rotationsvinkeln för stapelmärken. Läs/skriv float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Representerar rotationsvinkeln för stapelmärken. Läs/skriv float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Anger hur många stapelmärken som ska hoppas över mellan de som ritas. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Anger hur många stapelmärken som ska hoppas över mellan de som ritas. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Anger värdet för automatisk stapelmärkesspacing. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Anger värdet för automatisk stapelmärkesspacing. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Anger hur många stapelmarkeringar som ska hoppas över innan nästa ritas. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Anger hur många stapelmarkeringar som ska hoppas över innan nästa ritas. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Anger värdet för automatisk stapelmarkering spacing. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Anger värdet för automatisk stapelmarkering spacing. |
| [getLabelOffset()](#getLabelOffset--) | Anger avståndet för etiketter från axeln. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Anger avståndet för etiketter från axeln. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Anger typen av kategoriaxel. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Anger typen av kategoriaxel. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Sätter IAxis.CategoryAxisType-egenskapen med ett värde som bestäms automatiskt baserat på axeldata. |
| [getAggregationType()](#getAggregationType--) | Representerar aggregeringstyp för kategoriaxel (binning). |
| [setAggregationType(int value)](#setAggregationType-int-) | Representerar aggregeringstyp för kategoriaxel (binning). |
| [getBinWidth()](#getBinWidth--) | Anger binbredd när AggregationType-egenskapens värde är satt till AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Anger binbredd när AggregationType-egenskapens värde är satt till AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Anger antalet bins när AggregationType-egenskapens värde är satt till AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Anger antalet bins när AggregationType-egenskapens värde är satt till AxisAggregationType.ByNumberOfBins. |
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

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Representerar om värdeaxeln korsar kategoriaxeln mellan kategorier. Denna egenskap gäller endast för kategoriaxlar och gäller inte för 3-D-diagram. Läs/skriv boolean.

**Returnerar:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Representerar om värdeaxeln korsar kategoriaxeln mellan kategorier. Denna egenskap gäller endast för kategoriaxlar och gäller inte för 3-D-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Representerar punkten på axeln där den vinkelräta axeln korsar den. Läs/skriv float.

**Returnerar:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Representerar punkten på axeln där den vinkelräta axeln korsar den. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Anger skalningsvärdet för displayenheterna för värdeaxeln. Läs/skriv [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Returnerar:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Anger skalningsvärdet för displayenheterna för värdeaxeln. Läs/skriv [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Anger det faktiska maximala värdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet.

**Returnerar:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Anger det faktiska minimala värdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet.

**Returnerar:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Anger den faktiska huvudenheten för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet.

**Returnerar:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Anger den faktiska sekundära enheten för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet.

**Returnerar:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Anger den faktiska skalan för huvudenheten på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet.

**Returnerar:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Anger den faktiska skalan för sekundära enheten på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet.

**Returnerar:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Indikerar om maxvärdet tilldelas automatiskt. Läs/skriv boolean.

**Returnerar:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Indikerar om maxvärdet tilldelas automatiskt. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Representerar det maximala värdet på värdeaxeln. Läs/skriv double.

**Returnerar:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Representerar det maximala värdet på värdeaxeln. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Representerar de sekundära enheterna för datum- eller värdeaxeln. Läs/skriv double.

**Returnerar:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Representerar de sekundära enheterna för datum- eller värdeaxeln. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Indikerar om den sekundära enheten för axeln tilldelas automatiskt. Läs/skriv boolean.

**Returnerar:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Indikerar om den sekundära enheten för axeln tilldelas automatiskt. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Representerar huvudenheterna för datum- eller värdeaxeln. Läs/skriv double.

**Returnerar:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Representerar huvudenheterna för datum- eller värdeaxeln. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Indikerar om huvudenheten för axeln tilldelas automatiskt. Läs/skriv boolean.

**Returnerar:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Anger om huvudvärdet för axeln tilldelas automatiskt. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Anger om minvärdet tilldelas automatiskt. Läs/skriv boolean.

**Returnerar:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Anger om minvärdet tilldelas automatiskt. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Representerar det minsta värdet på värdeaxeln. Läs/skriv double.

**Returnerar:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Representerar det minsta värdet på värdeaxeln. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Representerar om skalan för värdeaxeln är logaritmisk eller inte. Läs/skriv boolean.

**Returnerar:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Representerar om skalan för värdeaxeln är logaritmisk eller inte. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Representerar den logaritmiska basen. Standardvärdet är 10. Läs/skriv double.

**Returnerar:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Representerar den logaritmiska basen. Standardvärdet är 10. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Representerar om MS PowerPoint ritar datapunkter från sista till första. Läs/skriv boolean.

**Returnerar:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Representerar om MS PowerPoint ritar datapunkter från sista till första. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Representerar om axeln är synlig. Läs/skriv boolean.

**Returnerar:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Representerar om axeln är synlig. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Representerar typen av huvudtickmarkering för den angivna axeln. Läs/skriv [TickMarkType](../../com.aspose.slides/tickmarktype).

**Returnerar:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Representerar typen av huvudtickmarkering för den angivna axeln. Läs/skriv [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Representerar typen av sekundär tickmarkering för den angivna axeln. Läs/skriv [TickMarkType](../../com.aspose.slides/tickmarktype).

**Returnerar:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Representerar typen av sekundär tickmarkering för den angivna axeln. Läs/skriv [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Representerar positionen för tick-etikettmarkeringar på den angivna axeln. Läs/skriv [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Returnerar:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Representerar positionen för tick-etikettmarkeringar på den angivna axeln. Läs/skriv [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Representerar huvud-enhetsskalan för datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returnerar:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Representerar huvud-enhetsskalan för datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Representerar huvud-enhetsskalan för datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returnerar:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Representerar huvud-enhetsskalan för datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Specificerar den minsta tidsenheten som representeras på datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returnerar:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Specificerar den minsta tidsenheten som representeras på datumaxeln. Läs/skriv [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Representerar formatet för sekundära rutnät på ett diagram-axis. Endast läs [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Returnerar:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Representerar formatet för huvudrutnät på ett diagram-axis. Endast läs [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Returnerar:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Representerar om sekundära rutnät visas. Endast läs boolean.

**Returnerar:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Representerar om huvudrutnät visas. Endast läs boolean.

**Returnerar:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Representerar formatet för axeln. Endast läs [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Returnerar:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Hämtar axelns titel. Endast läs [IChartTitle](../../com.aspose.slides/icharttitle).

**Returnerar:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Representerar CrossType på den angivna axeln där den andra axeln korsar. Läs/skriv [CrossesType](../../com.aspose.slides/crossestype).

**Returnerar:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Representerar CrossType på den angivna axeln där den andra axeln korsar. Läs/skriv [CrossesType](../../com.aspose.slides/crossestype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Representerar axelns position. Läs/skriv [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Returnerar:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Representerar axelns position. Läs/skriv [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Avgör om en axel har en synlig titel. Läs/skriv boolean.

**Returnerar:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Avgör om en axel har en synlig titel. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Representerar formatsträngen för axelvärdena. Läs/skriv String.

**Returnerar:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Representerar formatsträngen för axelvärdena. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Anger om formatet är länkat till källdata. Läs/skriv boolean.

**Returnerar:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Anger om formatet är länkat till källdata. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Representerar rotationsvinkeln för tick-etiketter. Läs/skriv float.

**Returnerar:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Representerar rotationsvinkeln för tick-etiketter. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Specificerar hur många tick-etiketter som ska hoppas över mellan etiketter som ritas. Läs/skriv long.

**Returnerar:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Specificerar hur många tick-etiketter som ska hoppas över mellan etiketter som ritas. Läs/skriv long.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Specificerar automatiskt avstånd för tick-etiketter. Om falskt: använd TickLabelSpacing-egenskapen. Läs/skriv boolean.

**Returnerar:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Specificerar automatiskt avstånd för tick-etiketter. Om falskt: använd TickLabelSpacing-egenskapen. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Specificerar hur många tick-markeringar som ska hoppas över innan nästa ritas. Gäller för kategori- eller serieraxel. Läs/skriv int.

**Returnerar:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Specificerar hur många tick-markeringar som ska hoppas över innan nästa ritas. Gäller för kategori- eller serieraxel. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Specificerar automatiskt avstånd för tick-markeringar. Om falskt: använd TickMarksSpacing-egenskapen. Läs/skriv boolean.

**Returnerar:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Specificerar automatiskt avstånd för tick-markeringar. Om falskt: använd TickMarksSpacing-egenskapen. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Specificerar avståndet för etiketter från axeln. Gäller för kategori- eller datumaxel. Värdet måste ligga mellan 0 % och 1000 %. Läs/skriv int.

**Returnerar:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Specificerar avståndet för etiketter från axeln. Gäller för kategori- eller datumaxel. Värdet måste ligga mellan 0 % och 1000 %. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Specificerar typen av kategori-axel. Läs/skriv [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Returnerar:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Specificerar typen av kategori-axel. Läs/skriv [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Ställer in IAxis.CategoryAxisType-egenskapen med ett värde som bestäms automatiskt utifrån axeldata.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Representerar aggregeringstyp för kategori-axeln (gruppering). Gäller för kategori. Används endast med Histogram- eller HistogramPareto-serier.

**Returnerar:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Representerar aggregeringstyp för kategori-axeln (gruppering). Gäller för kategori. Används endast med Histogram- eller HistogramPareto-serier.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Anger binbredd när egenskapens värde AggregationType är satt till AxisAggregationType.ByBinWidth. Tillämpas på kategoriska axlar. Används endast med Histogram- eller HistogramPareto-serier.

**Returnerar:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Anger binbredd när egenskapens värde AggregationType är satt till AxisAggregationType.ByBinWidth. Tillämpas på kategoriska axlar. Används endast med Histogram- eller HistogramPareto-serier.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Anger antal bin när egenskapens värde AggregationType är satt till AxisAggregationType.ByNumberOfBins. Tillämpas på kategoriska axlar. Används endast med Histogram- eller HistogramPareto-serier.

**Returnerar:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Anger antal bin när egenskapens värde AggregationType är satt till AxisAggregationType.ByNumberOfBins. Tillämpas på kategoriska axlar. Används endast med Histogram- eller HistogramPareto-serier.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Anger om overflow-bin används. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-bin-värdet.

**Returnerar:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Anger om overflow-bin används. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-bin-värdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Anger automatiskt overflow-bin-värde. Om false: använd OverflowBin-egenskapen.

**Returnerar:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```java
public abstract void setAutomaticOverflowBin(boolean value)
```

Anger automatiskt overflow-bin-värde. Om false: använd OverflowBin-egenskapen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Anger anpassat overflow-bin-värde. Tillämpas när IsAutomaticOverflowBin-egenskapen är satt till false och IsOverflowBin-egenskapen är true.

**Returnerar:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```java
public abstract void setOverflowBin(double value)
```

Anger anpassat overflow-bin-värde. Tillämpas när IsAutomaticOverflowBin-egenskapen är satt till false och IsOverflowBin-egenskapen är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Anger om underflow-bin används. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-bin-värdet.

**Returnerar:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Anger om underflow-bin används. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-bin-värdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Anger automatiskt underflow-bin-värde. Om false: använd UnderflowBin-egenskapen.

**Returnerar:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Anger automatiskt underflow-bin-värde. Om false: använd UnderflowBin-egenskapen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Anger anpassat underflow-bin-värde. Tillämpas när IsAutomaticUnderflowBin-egenskapen är satt till false och IsUnderflowBin-egenskapen är true.

**Returnerar:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Anger anpassat underflow-bin-värde. Tillämpas när IsAutomaticUnderflowBin-egenskapen är satt till false och IsUnderflowBin-egenskapen är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |