---
title: Axis
second_title: Aspose.Slides voor Java API-referentie
description: Omsluit het object dat een grafiekas vertegenwoordigt.
type: docs
url: /nl/com.aspose.slides/axis/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Omsluit het object dat een as van een grafiek vertegenwoordigt.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getChart()](#getChart--) | Retourneert de bovenliggende grafiek. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Geeft aan of de waardenas de categoriasas tussen categorieën kruist. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Geeft aan of de waardenas de categoriasas tussen categorieën kruist. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Specificeert het type van de categoriasas. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Specificeert het type van de categoriasas. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Stelt de IAxis.CategoryAxisType-eigenschap in met een waarde die automatisch wordt bepaald op basis van as-gegevens. |
| [getCrossAt()](#getCrossAt--) | Geeft het punt op de as weer waar de loodrechte as deze kruist. |
| [setCrossAt(float value)](#setCrossAt-float-) | Geeft het punt op de as weer waar de loodrechte as deze kruist. |
| [getDisplayUnit()](#getDisplayUnit--) | Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. |
| [getActualMaxValue()](#getActualMaxValue--) | Specificeert de werkelijke maximale waarde op de as. |
| [getActualMinValue()](#getActualMinValue--) | Specificeert de werkelijke minimale waarde op de as. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Specificeert de werkelijke hoofd-eenheid van de as. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Specificeert de werkelijke subeenheid van de as. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Specificeert de werkelijke schaal van de hoofd-eenheid van de as. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Specificeert de werkelijke schaal van de subeenheid van de as. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Geeft aan of de maximale waarde automatisch wordt toegewezen. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Geeft aan of de maximale waarde automatisch wordt toegewezen. |
| [getMaxValue()](#getMaxValue--) | Geeft de maximale waarde op de waardenas weer. |
| [setMaxValue(double value)](#setMaxValue-double-) | Geeft de maximale waarde op de waardenas weer. |
| [getMinorUnit()](#getMinorUnit--) | Geeft de subeenheden voor de datum- of waardenas weer. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Geeft de subeenheden voor de datum- of waardenas weer. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Geeft aan of de subeenheid van de as automatisch wordt toegewezen. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Geeft aan of de subeenheid van de as automatisch wordt toegewezen. |
| [getMajorUnit()](#getMajorUnit--) | Geeft de hoofd-eenheden voor de datum- of waardenas weer. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Geeft de hoofd-eenheden voor de datum- of waardenas weer. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Geeft aan of de hoofd-eenheid van de as automatisch wordt toegewezen. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Geeft aan of de hoofd-eenheid van de as automatisch wordt toegewezen. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Geeft aan of de minimale waarde automatisch wordt toegewezen. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Geeft aan of de minimale waarde automatisch wordt toegewezen. |
| [getMinValue()](#getMinValue--) | Geeft de minimale waarde op de waardenas weer. |
| [setMinValue(double value)](#setMinValue-double-) | Geeft de minimale waarde op de waardenas weer. |
| [isLogarithmic()](#isLogarithmic--) | Geeft aan of het schaaltype van de waardenas logaritmisch is of niet. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Geeft aan of het schaaltype van de waardenas logaritmisch is of niet. |
| [getLogBase()](#getLogBase--) | Geeft de logaritmische basis weer. |
| [setLogBase(double value)](#setLogBase-double-) | Geeft de logaritmische basis weer. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Geeft aan of MS PowerPoint gegevenspunten van laatst naar eerst plot. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Geeft aan of MS PowerPoint gegevenspunten van laatst naar eerst plot. |
| [isVisible()](#isVisible--) | Geeft aan of de as zichtbaar is. |
| [setVisible(boolean value)](#setVisible-boolean-) | Geeft aan of de as zichtbaar is. |
| [getMajorTickMark()](#getMajorTickMark--) | Geeft het type van de hoofd-tikker voor de opgegeven as weer. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Geeft het type van de hoofd-tikker voor de opgegeven as weer. |
| [getMinorTickMark()](#getMinorTickMark--) | Geeft het type van de sub-tikker voor de opgegeven as weer. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Geeft het type van de sub-tikker voor de opgegeven as weer. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Geeft de positie van de tick-label-teksten op de opgegeven as weer. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Geeft de positie van de tick-label-teksten op de opgegeven as weer. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Geeft de schaal van de hoofd-eenheid voor de datum-as weer. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Geeft de schaal van de hoofd-eenheid voor de datum-as weer. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Geeft de schaal van de hoofd-eenheid voor de datum-as weer. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Geeft de schaal van de hoofd-eenheid voor de datum-as weer. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Specificeert de kleinste tijdseenheid die op de datum-as wordt weergegeven. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Specificeert de kleinste tijdseenheid die op de datum-as wordt weergegeven. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Geeft het formaat van de sub-roosterlijnen op een grafiekas weer. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Geeft het formaat van de hoofd-roosterlijnen op een grafiekas weer. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Om de sub-roosterlijn te verbergen, stel MinorGridLinesFormat.Line.FillFormat.FillType in op FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Om de hoofd-roosterlijn te verbergen, stel MajorGridLinesFormat.Line.FillFormat.FillType in op FillType.NoFill. |
| [getFormat()](#getFormat--) | Geeft het formaat van de as weer. |
| [getTextFormat()](#getTextFormat--) | Geeft het formaat van de tekst weer. |
| [getTitle()](#getTitle--) | Haalt de titel van de as op. |
| [getCrossType()](#getCrossType--) | Geeft het CrossType op de opgegeven as weer waar de andere as kruist. |
| [setCrossType(int value)](#setCrossType-int-) | Geeft het CrossType op de opgegeven as weer waar de andere as kruist. |
| [getPosition()](#getPosition--) | Geeft de positie van de as weer. |
| [setPosition(int value)](#setPosition-int-) | Geeft de positie van de as weer. |
| [hasTitle()](#hasTitle--) | Bepaalt of een as een zichtbare titel heeft. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bepaalt of een as een zichtbare titel heeft. |
| [getNumberFormat()](#getNumberFormat--) | Geeft de opmaakreeks voor de As-Labels weer. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Geeft de opmaakreeks voor de As-Labels weer. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Geeft aan of de opmaak gekoppeld is aan brongegevens. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Geeft aan of de opmaak gekoppeld is aan brongegevens. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Geeft de rotatiehoek van de tick-labels weer. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Geeft de rotatiehoek van de tick-labels weer. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Specificeert hoeveel tick-labels overgeslagen moeten worden tussen getekende labels. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Specificeert hoeveel tick-labels overgeslagen moeten worden tussen getekende labels. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Specificeert de automatische afstand tussen tick-labels. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Specificeert de automatische afstand tussen tick-labels. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Specificeert hoeveel tick-markeringen overgeslagen moeten worden voordat de volgende getekend wordt. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Specificeert hoeveel tick-markeringen overgeslagen moeten worden voordat de volgende getekend wordt. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Specificeert de automatische afstand tussen tick-markeringen. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Specificeert de automatische afstand tussen tick-markeringen. |
| [getLabelOffset()](#getLabelOffset--) | Specificeert de afstand van de labels tot de as. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Specificeert de afstand van de labels tot de as. |
| [getAggregationType()](#getAggregationType--) | Geeft het aggregatietype van de categoriasas weer (binnendorpeling). |
| [setAggregationType(int value)](#setAggregationType-int-) | Geeft het aggregatietype van de categoriasas weer (binnendorpeling). |
| [getBinWidth()](#getBinWidth--) | Specificeert de breedte van de bak wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Specificeert de breedte van de bak wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Specificeert het aantal bakken wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Specificeert het aantal bakken wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Geeft aan of een overflow-bak wordt toegepast. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Geeft aan of een overflow-bak wordt toegepast. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Specificeert de automatische overflow-bakwaarde. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Specificeert de automatische overflow-bakwaarde. |
| [getOverflowBin()](#getOverflowBin--) | Specificeert een aangepaste overflow-bakwaarde. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Specificeert een aangepaste overflow-bakwaarde. |
| [isUnderflowBin()](#isUnderflowBin--) | Geeft aan of een underflow-bak wordt toegepast. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Geeft aan of een underflow-bak wordt toegepast. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Specificeert de automatische underflow-bakwaarde. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Specificeert de automatische underflow-bakwaarde. |
| [getUnderflowBin()](#getUnderflowBin--) | Specificeert een aangepaste underflow-bakwaarde. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Specificeert een aangepaste underflow-bakwaarde. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een FillFormat. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Retourneert de bovenliggende grafiek. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Retourneert:**
[IChart](../../com.aspose.slides/ichart)
### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Geeft aan of de waardenas de categoriasas tussen categorieën kruist. Deze eigenschap is alleen van toepassing op categoriasassen en niet op 3-D-grafieken. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Geeft aan of de waardenas de categoriasas tussen categorieën kruist. Deze eigenschap is alleen van toepassing op categoriasassen en niet op 3-D-grafieken. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Specificeert het type van de categoriasas. Lezen/schrijven [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Retourneert:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Specificeert het type van de categoriasas. Lezen/schrijven [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Stelt de IAxis.CategoryAxisType-eigenschap in met een waarde die automatisch wordt bepaald op basis van as-gegevens.
### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Geeft het punt op de as weer waar de loodrechte as deze kruist. Lezen/schrijven float.

**Retourneert:**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Geeft het punt op de as weer waar de loodrechte as deze kruist. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. Lezen/schrijven [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Retourneert:**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. Lezen/schrijven [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Specificeert de werkelijke maximale waarde op de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen.

**Retourneert:**
double
### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Specificeert de werkelijke minimale waarde op de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen.

**Retourneert:**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Specificeert de werkelijke hoofd-eenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen.

**Retourneert:**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Specificeert de werkelijke subeenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen.

**Retourneert:**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Specificeert de werkelijke schaal van de hoofd-eenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen.

**Retourneert:**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Specificeert de werkelijke schaal van de subeenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen.

**Retourneert:**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Geeft aan of de maximale waarde automatisch wordt toegewezen. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Geeft aan of de maximale waarde automatisch wordt toegewezen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Geeft de maximale waarde op de waardenas weer. Lezen/schrijven double.

**Retourneert:**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Geeft de maximale waarde op de waardenas weer. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Geeft de subeenheden voor de datum- of waardenas weer. Lezen/schrijven double.

**Retourneert:**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Geeft de subeenheden voor de datum- of waardenas weer. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
Geeft aan of de kleine eenheid van de as automatisch wordt toegewezen. Lezen/schrijven boolean.

**Retour:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```


Geeft aan of de kleine eenheid van de as automatisch wordt toegewezen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```


Stelt de grote eenheden voor de datum- of waardenas. Lezen/schrijven double.

**Retour:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```


Stelt de grote eenheden voor de datum- of waardenas. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```


Geeft aan of de grote eenheid van de as automatisch wordt toegewezen. Lezen/schrijven boolean.

**Retour:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```


Geeft aan of de grote eenheid van de as automatisch wordt toegewezen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```


Geeft aan of de minimale waarde automatisch wordt toegewezen. Lezen/schrijven boolean.

**Retour:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```


Geeft aan of de minimale waarde automatisch wordt toegewezen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```


Stelt de minimale waarde op de waardenas voor. Lezen/schrijven double.

**Retour:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```


Stelt de minimale waarde op de waardenas voor. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```


Geeft aan of het schaaltype van de waardenas logaritmisch is. Lezen/schrijven boolean.

**Retour:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```


Geeft aan of het schaaltype van de waardenas logaritmisch is. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```


Stelt de logaritmische basis voor. Standaardwaarde is 10. Lezen/schrijven double.

**Retour:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```


Stelt de logaritmische basis voor. Standaardwaarde is 10. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```


Geeft aan of MS PowerPoint gegevenspunten van laatste naar eerste plotst. Lezen/schrijven boolean.

**Retour:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```


Geeft aan of MS PowerPoint gegevenspunten van laatste naar eerste plotst. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Geeft aan of de as zichtbaar is. Lezen/schrijven boolean.

**Retour:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Geeft aan of de as zichtbaar is. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```


Stelt het type van het grote tick-mark voor de opgegeven as voor. Lezen/schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retour:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```


Stelt het type van het grote tick-mark voor de opgegeven as voor. Lezen/schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```


Stelt het type van het kleine tick-mark voor de opgegeven as voor. Lezen/schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retour:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```


Stelt het type van het kleine tick-mark voor de opgegeven as voor. Lezen/schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```


Stelt de positie van tick-label-tekst op de opgegeven as voor. Lezen/schrijven [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Retour:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```


Stelt de positie van tick-label-tekst op de opgegeven as voor. Lezen/schrijven [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```


Stelt de schaal van de grote eenheid voor de datumas voor. Lezen/schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retour:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```


Stelt de schaal van de grote eenheid voor de datumas voor. Lezen/schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```


Stelt de schaal van de grote eenheid voor de datumas voor. Lezen/schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retour:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```


Stelt de schaal van de grote eenheid voor de datumas voor. Lezen/schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```


Specificeert de kleinste tijdseenheid die op de datumas wordt weergegeven. Lezen/schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retour:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```


Specificeert de kleinste tijdseenheid die op de datumas wordt weergegeven. Lezen/schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


Stelt het formaat van de kleine rasterlijnen van een diagramas voor. Alleen-lezen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retour:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```


Stelt het formaat van de grote rasterlijnen van een diagramas voor. Alleen-lezen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retour:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```


Om kleine rasterlijnen te verbergen, stel MinorGridLinesFormat.Line.FillFormat.FillType in op FillType.NoFill. Alleen-lezen boolean.

**Retour:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```


Om grote rasterlijnen te verbergen, stel MajorGridLinesFormat.Line.FillFormat.FillType in op FillType.NoFill. Alleen-lezen boolean.

**Retour:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```


Stelt het formaat van de as voor. Alleen-lezen [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Retour:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Stelt het tekstopmaak van de as voor. Alleen-lezen [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retour:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```


Haalt de titel van de as op. Alleen-lezen [IChartTitle](../../com.aspose.slides/icharttitle).

**Retour:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```


Stelt de CrossType op de opgegeven as voor waar de andere as kruist. Lezen/schrijven [CrossesType](../../com.aspose.slides/crossestype).

**Retour:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```


Stelt de CrossType op de opgegeven as voor waar de andere as kruist. Lezen/schrijven [CrossesType](../../com.aspose.slides/crossestype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


Stelt de positie van de as voor. Lezen/schrijven [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Retour:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Stelt de positie van de as voor. Lezen/schrijven [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


Bepaalt of een as een zichtbare titel heeft. Lezen/schrijven boolean.

**Retour:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


Bepaalt of een as een zichtbare titel heeft. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


Stelt de opmaakstring voor de as-labels voor. Lezen/schrijven String.

**Retour:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


Stelt de opmaakstring voor de as-labels voor. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


Geeft aan of de opmaak is gekoppeld aan brongegevens. Lezen/schrijven boolean.

**Retour:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


Geeft aan of de opmaak is gekoppeld aan brongegevens. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```


Stelt de rotatiehoek van tick-labels voor. Lezen/schrijven float.

**Retour:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```


Stelt de rotatiehoek van tick-labels voor. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```


Specificeert hoeveel tick-labels moeten worden overgeslagen tussen de getekende labels. Toegepast op categorie- of seriesas. Lezen/schrijven long.

**Retour:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```


Specificeert hoeveel tick-labels moeten worden overgeslagen tussen de getekende labels. Toegepast op categorie- of seriesas. Lezen/schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```


Specificeert een automatische tick-label-spaciëringswaarde. Indien false: gebruik de eigenschap TickLabelSpacing. Lezen/schrijven boolean.

**Retour:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```


Specificeert een automatische tick-label-spaciëringswaarde. Indien false: gebruik de eigenschap TickLabelSpacing. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```


Specificeert hoeveel tick-marks moeten worden overgeslagen voordat de volgende wordt getekend. Toegepast op categorie- of seriesas. Lezen/schrijven int.

**Retour:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```


Specificeert hoeveel tick-marks moeten worden overgeslagen voordat de volgende wordt getekend. Toegepast op categorie- of seriesas. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```


Specificeert een automatische tick-marks-spaciëringswaarde. Indien false: gebruik de eigenschap TickMarksSpacing. Lezen/schrijven boolean.

**Retour:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```


Specificeert een automatische tick-marks-spaciëringswaarde. Indien false: gebruik de eigenschap TickMarksSpacing. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```


Specificeert de afstand van labels tot de as. Toegepast op categorie- of datumas. Waarde moet tussen 0 % en 1000 % liggen. Lezen/schrijven int.

**Retour:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```


Specificeert de afstand van labels tot de as. Toegepast op categorie- of datumas. Waarde moet tussen 0 % en 1000 % liggen. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Stelt het aggregatietype van de categorie-as (binning) voor. Toegepast op categorie. Alleen gebruikt met Histogram- of HistogramPareto-reeksen.

**Retour:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Stelt het aggregatietype van de categorie-as (binning) voor. Toegepast op categorie. Alleen gebruikt met Histogram- of HistogramPareto-reeksen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Specificeert de breedte van de bin wanneer de AggregationType-eigenschapwaarde is ingesteld op AxisAggregationType.ByBinWidth. Toegepast op categorie-assen. Alleen gebruikt met Histogram- of HistogramPareto-reeksen.

**Retour:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Specificeert de breedte van de bin wanneer de AggregationType-eigenschapwaarde is ingesteld op AxisAggregationType.ByBinWidth. Toegepast op categorie-assen. Alleen gebruikt met Histogram- of HistogramPareto-reeksen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Specificeert het aantal bins wanneer de AggregationType-eigenschapwaarde is ingesteld op AxisAggregationType.ByNumberOfBins. Toegepast op categorie-assen. Alleen gebruikt met Histogram- of HistogramPareto-reeksen.

**Retour:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Specificeert het aantal bins wanneer de AggregationType-eigenschapwaarde is ingesteld op AxisAggregationType.ByNumberOfBins. Toegepast op categorie-assen. Alleen gebruikt met Histogram- of HistogramPareto-reeksen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |
### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Specificeert of de overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-binwaarde aan te passen.

**Retour:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Specificeert of de overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-binwaarde aan te passen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Specificeert de automatische overflow-binwaarde. Indien false: gebruik de OverflowBin-eigenschap.

**Retour:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Specificeert de automatische overflow-binwaarde. Indien false: gebruik de OverflowBin-eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Specificeert een aangepaste waarde voor de overflow-bin. Toegepast wanneer de IsAutomaticOverflowBin-eigenschap is ingesteld op false en de IsOverflowBin-eigenschap gelijk is aan true.

**Retour:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Specificeert een aangepaste waarde voor de overflow-bin. Toegepast wanneer de IsAutomaticOverflowBin-eigenschap is ingesteld op false en de IsOverflowBin-eigenschap gelijk is aan true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Specificeert of de underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-binwaarde aan te passen.

**Retour:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Specificeert of de underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-binwaarde aan te passen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Specificeert de automatische underflow-binwaarde. Indien false: gebruik de UnderflowBin-eigenschap.

**Retour:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Specificeert de automatische underflow-binwaarde. Indien false: gebruik de UnderflowBin-eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Specificeert een aangepaste waarde voor de underflow-bin. Toegepast wanneer de IsAutomaticUnderflowBin-eigenschap is ingesteld op false en de IsUnderflowBin-eigenschap gelijk is aan true.

**Retour:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Specificeert een aangepaste waarde voor de underflow-bin. Toegepast wanneer de IsAutomaticUnderflowBin-eigenschap is ingesteld op false en de IsUnderflowBin-eigenschap gelijk is aan true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende dia van een FillFormat. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Retour:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een FillFormat. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation)