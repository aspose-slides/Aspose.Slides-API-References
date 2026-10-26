---
title: Axis
second_title: Aspose.Slides voor Android via Java API-referentie
description: Omsluit het object dat een as van een diagram vertegenwoordigt.
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

Omsluit het object dat een as van een diagram vertegenwoordigt.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getChart()](#getChart--) | Retourneert het bovenliggende diagram. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Geeft aan of de waardenas de categorias kruist tussen categorieën. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Geeft aan of de waardenas de categorias kruist tussen categorieën. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Specificeert het type van de categorias. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Specificeert het type van de categorias. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Stelt de IAxis.CategoryAxisType eigenschap in met een waarde die automatisch wordt bepaald op basis van asgegevens. |
| [getCrossAt()](#getCrossAt--) | Geeft het punt op de as waar de loodrechte as deze kruist. |
| [setCrossAt(float value)](#setCrossAt-float-) | Geeft het punt op de as waar de loodrechte as deze kruist. |
| [getDisplayUnit()](#getDisplayUnit--) | Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. |
| [getActualMaxValue()](#getActualMaxValue--) | Specificeert de werkelijke maximale waarde op de as. |
| [getActualMinValue()](#getActualMinValue--) | Specificeert de werkelijke minimale waarde op de as. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Specificeert de werkelijke hoofd-eenheid van de as. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Specificeert de werkelijke sub-eenheid van de as. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Specificeert de werkelijke schaal van de hoofd-eenheid van de as. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Specificeert de werkelijke schaal van de sub-eenheid van de as. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Geeft aan of de maximale waarde automatisch wordt toegekend. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Geeft aan of de maximale waarde automatisch wordt toegekend. |
| [getMaxValue()](#getMaxValue--) | Geeft de maximale waarde op de waardenas weer. |
| [setMaxValue(double value)](#setMaxValue-double-) | Geeft de maximale waarde op de waardenas weer. |
| [getMinorUnit()](#getMinorUnit--) | Geeft de sub-eenheden voor de datum- of waardenas weer. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Geeft de sub-eenheden voor de datum- of waardenas weer. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Geeft aan of de sub-eenheid van de as automatisch wordt toegekend. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Geeft aan of de sub-eenheid van de as automatisch wordt toegekend. |
| [getMajorUnit()](#getMajorUnit--) | Geeft de hoofd-eenheden voor de datum- of waardenas weer. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Geeft de hoofd-eenheden voor de datum- of waardenas weer. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Geeft aan of de hoofd-eenheid van de as automatisch wordt toegekend. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Geeft aan of de hoofd-eenheid van de as automatisch wordt toegekend. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Geeft aan of de minimale waarde automatisch wordt toegekend. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Geeft aan of de minimale waarde automatisch wordt toegekend. |
| [getMinValue()](#getMinValue--) | Geeft de minimale waarde op de waardenas weer. |
| [setMinValue(double value)](#setMinValue-double-) | Geeft de minimale waarde op de waardenas weer. |
| [isLogarithmic()](#isLogarithmic--) | Geeft aan of het schaaltype van de waardenas logaritmisch is of niet. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Geeft aan of het schaaltype van de waardenas logaritmisch is of niet. |
| [getLogBase()](#getLogBase--) | Geeft de logaritmische basis weer. |
| [setLogBase(double value)](#setLogBase-double-) | Geeft de logaritmische basis weer. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Geeft aan of MS PowerPoint gegevenspunten van laatste naar eerste plot. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Geeft aan of MS PowerPoint gegevenspunten van laatste naar eerste plot. |
| [isVisible()](#isVisible--) | Geeft aan of de as zichtbaar is. |
| [setVisible(boolean value)](#setVisible-boolean-) | Geeft aan of de as zichtbaar is. |
| [getMajorTickMark()](#getMajorTickMark--) | Geeft het type van het hoofd-tickmark voor de opgegeven as weer. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Geeft het type van het hoofd-tickmark voor de opgegeven as weer. |
| [getMinorTickMark()](#getMinorTickMark--) | Geeft het type van het sub-tickmark voor de opgegeven as weer. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Geeft het type van het sub-tickmark voor de opgegeven as weer. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Geeft de positie van tick-label-labels op de opgegeven as weer. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Geeft de positie van tick-label-labels op de opgegeven as weer. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Geeft de schaal van de hoofd-eenheid voor de datum-as weer. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Geeft de schaal van de hoofd-eenheid voor de datum-as weer. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Geeft de schaal van de hoofd-eenheid voor de datum-as weer. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Geeft de schaal van de hoofd-eenheid voor de datum-as weer. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Specificeert de kleinste tijdseenheid die op de datum-as wordt weergegeven. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Specificeert de kleinste tijdseenheid die op de datum-as wordt weergegeven. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Geeft het formaat van de sub-rasterlijnen op een diagram-as weer. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Geeft het formaat van de hoofd-rasterlijnen op een diagram-as weer. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Om de sub-rasterlijn te verbergen, stel MinorGridLinesFormat.Line.FillFormat.FillType in op FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Om de hoofd-rasterlijn te verbergen, stel MajorGridLinesFormat.Line.FillFormat.FillType in op FillType.NoFill. |
| [getFormat()](#getFormat--) | Geeft het formaat van de as weer. |
| [getTextFormat()](#getTextFormat--) | Geeft het formaat van de tekst weer. |
| [getTitle()](#getTitle--) | Haalt de titel van de as op. |
| [getCrossType()](#getCrossType--) | Geeft het CrossType op de opgegeven as weer waar de andere as deze kruist. |
| [setCrossType(int value)](#setCrossType-int-) | Geeft het CrossType op de opgegeven as weer waar de andere as deze kruist. |
| [getPosition()](#getPosition--) | Geeft de positie van de as weer. |
| [setPosition(int value)](#setPosition-int-) | Geeft de positie van de as weer. |
| [hasTitle()](#hasTitle--) | Bepaalt of een as een zichtbare titel heeft. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bepaalt of een as een zichtbare titel heeft. |
| [getNumberFormat()](#getNumberFormat--) | Geeft de opmaakreeks voor de As-Labels weer. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Geeft de opmaakreeks voor de As-Labels weer. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Geeft aan of de opmaak is gekoppeld aan brongegevens. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Geeft aan of de opmaak is gekoppeld aan brongegevens. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Geeft de rotatiehoek van tick-labels weer. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Geeft de rotatiehoek van tick-labels weer. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Specificeert hoeveel tick-labels moeten worden overgeslagen tussen getekende labels. Toegepast op categorias of series-as. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Specificeert hoeveel tick-labels moeten worden overgeslagen tussen getekende labels. Toegepast op categorias of series-as. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Specificeert automatische tick-label-afstand. Indien false: gebruik de eigenschap TickLabelSpacing. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Specificeert automatische tick-label-afstand. Indien false: gebruik de eigenschap TickLabelSpacing. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Specificeert hoeveel tick-markeringen moeten worden overgeslagen voordat de volgende wordt getekend. Toegepast op categorias of series-as. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Specificeert hoeveel tick-markeringen moeten worden overgeslagen voordat de volgende wordt getekend. Toegepast op categorias of series-as. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Specificeert automatische tick-markering-afstand. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Specificeert automatische tick-markering-afstand. |
| [getLabelOffset()](#getLabelOffset--) | Specificeert de afstand van labels tot de as. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Specificeert de afstand van labels tot de as. |
| [getAggregationType()](#getAggregationType--) | Geeft het aggregatietype van de categorias (binning) weer. |
| [setAggregationType(int value)](#setAggregationType-int-) | Geeft het aggregatietype van de categorias (binning) weer. |
| [getBinWidth()](#getBinWidth--) | Specificeert de bin-breedte wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByBinWidth. Toegepast op categorias. Alleen gebruikt met Histogram- of HistogramPareto-series. |
| [setBinWidth(double value)](#setBinWidth-double-) | Specificeert de bin-breedte wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByBinWidth. Toegepast op categorias. Alleen gebruikt met Histogram- of HistogramPareto-series. |
| [getNumberOfBins()](#getNumberOfBins--) | Specificeert het aantal bins wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByNumberOfBins. Toegepast op categorias. Alleen gebruikt met Histogram- of HistogramPareto-series. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Specificeert het aantal bins wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByNumberOfBins. Toegepast op categorias. Alleen gebruikt met Histogram- of HistogramPareto-series. |
| [isOverflowBin()](#isOverflowBin--) | Geeft aan of een overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-bin-waarde aan te passen. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Geeft aan of een overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-bin-waarde aan te passen. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Specificeert de automatische overflow-bin-waarde. Indien false: gebruik de eigenschap OverflowBin. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Specificeert de automatische overflow-bin-waarde. Indien false: gebruik de eigenschap OverflowBin. |
| [getOverflowBin()](#getOverflowBin--) | Specificeert een aangepaste overflow-bin-waarde. Toegepast wanneer IsAutomaticOverflowBin false is en IsOverflowBin true is. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Specificeert een aangepaste overflow-bin-waarde. Toegepast wanneer IsAutomaticOverflowBin false is en IsOverflowBin true is. |
| [isUnderflowBin()](#isUnderflowBin--) | Geeft aan of een underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-bin-waarde aan te passen. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Geeft aan of een underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-bin-waarde aan te passen. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Specificeert de automatische underflow-bin-waarde. Indien false: gebruik de eigenschap UnderflowBin. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Specificeert de automatische underflow-bin-waarde. Indien false: gebruik de eigenschap UnderflowBin. |
| [getUnderflowBin()](#getUnderflowBin--) | Specificeert een aangepaste underflow-bin-waarde. Toegepast wanneer IsAutomaticUnderflowBin false is en IsUnderflowBin true is. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Specificeert een aangepaste underflow-bin-waarde. Toegepast wanneer IsAutomaticUnderflowBin false is en IsUnderflowBin true is. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende slide van een FillFormat. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Retourneert het bovenliggende diagram. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Retourneert:**
[IChart](../../com.aspose.slides/ichart)
### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Geeft aan of de waardenas de categorias kruist tussen categorieën. Deze eigenschap is alleen van toepassing op categorias en is niet van toepassing op 3-D-diagrammen. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Geeft aan of de waardenas de categorias kruist tussen categorieën. Deze eigenschap is alleen van toepassing op categorias en is niet van toepassing op 3-D-diagrammen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Specificeert het type van de categorias. Lezen/Schrijven [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Retourneert:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Specificeert het type van de categorias. Lezen/Schrijven [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Stelt de IAxis.CategoryAxisType eigenschap in met een waarde die automatisch wordt bepaald op basis van asgegevens.
### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Geeft het punt op de as waar de loodrechte as deze kruist. Lezen/Schrijven float.

**Retourneert:**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Geeft het punt op de as waar de loodrechte as deze kruist. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. Lezen/Schrijven [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Retourneert:**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. Lezen/Schrijven [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Specificeert de werkelijke maximale waarde op de as. Roep eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te krijgen.

**Retourneert:**
double
### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Specificeert de werkelijke minimale waarde op de as. Roep eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te krijgen.

**Retourneert:**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Specificeert de werkelijke hoofd-eenheid van de as. Roep eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te krijgen.

**Retourneert:**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Specificeert de werkelijke sub-eenheid van de as. Roep eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te krijgen.

**Retourneert:**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Specificeert de werkelijke schaal van de hoofd-eenheid van de as. Roep eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te krijgen.

**Retourneert:**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Specificeert de werkelijke schaal van de sub-eenheid van de as. Roep eerst de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te krijgen.

**Retourneert:**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Geeft aan of de maximale waarde automatisch wordt toegekend. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Geeft aan of de maximale waarde automatisch wordt toegekend. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Geeft de maximale waarde op de waardenas weer. Lezen/Schrijven double.

**Retourneert:**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Geeft de maximale waarde op de waardenas weer. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Geeft de sub-eenheden voor de datum- of waardenas weer. Lezen/Schrijven double.

**Retourneert:**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Geeft de sub-eenheden voor de datum- of waardenas weer. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

Geeft aan of de sub-eenheid van de as automatisch wordt toegekend. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

Geeft aan of de sub-eenheid van de as automatisch wordt toegekend. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

Geeft de hoofd-eenheden voor de datum- of waardenas weer. Lezen/Schrijven double.

**Retourneert:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

Geeft de hoofd-eenheden voor de datum- of waardenas weer. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

Geeft aan of de hoofd-eenheid van de as automatisch wordt toegekend. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

Geeft aan of de hoofd-eenheid van de as automatisch wordt toegekend. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

Geeft aan of de minimale waarde automatisch wordt toegekend. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

Geeft aan of de minimale waarde automatisch wordt toegekend. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

Geeft de minimale waarde op de waardenas weer. Lezen/Schrijven double.

**Retourneert:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

Geeft de minimale waarde op de waardenas weer. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

Geeft aan of het schaaltype van de waardenas logaritmisch is of niet. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

Geeft aan of het schaaltype van de waardenas logaritmisch is of niet. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

Geeft de logaritmische basis weer. Standaardwaarde is 10. Lezen/Schrijven double.

**Retourneert:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

Geeft de logaritmische basis weer. Standaardwaarde is 10. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public  {
  if (this.getAxes().length > name && nextAxes().length == name && this.getAxes() - 
}
```

Geeft aan of MS PowerPoint gegevenspunten van laatste naar eerste plot. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

Geeft aan of MS PowerPoint gegevenspunten van laatste naar eerste plot. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Geeft aan of de as zichtbaar is. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Geeft aan of de as zichtbaar is. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

Geeft het type van het hoofd-tickmark voor de opgegeven as weer. Lezen/Schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retourneert:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

Geeft het type van het hoofd-tickmark voor de opgegeven as weer. Lezen/Schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

Geeft het type van het sub-tickmark voor de opgegeven as weer. Lezen/Schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retourneert:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

Geeft het type van het sub-tickmark voor de opgegeven as weer. Lezen/Schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

Geeft de positie van tick-label-labels op de opgegeven as weer. Lezen/Schrijven [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Retourneert:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

Geeft de positie van tick-label-labels op de opgegeven as weer. Lezen/Schrijven [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

Geeft de schaal van de hoofd-eenheid voor de datum-as weer. Lezen/Schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retourneert:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

Geeft de schaal van de hoofd-eenheid voor de datum-as weer. Lezen/Schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

Geeft de schaal van de hoofd-eenheid voor de datum-as weer. Lezen/Schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retourneert:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

Geeft de schaal van de hoofd-eenheid voor de datum-as weer. Lezen/Schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

Specificeert de kleinste tijdseenheid die op de datum-as wordt weergegeven. Lezen/Schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retourneert:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

Specificeert de kleinste tijdseenheid die op de datum-as wordt weergegeven. Lezen/Schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Geeft het formaat van de sub-rasterlijnen op een diagram-as weer. Alleen-lezen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retourneert:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

Geeft het formaat van de hoofd-rasterlijnen op een diagram-as weer. Alleen-lezen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retourneert:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

Om de sub-rasterlijn te verbergen, stel MinorGridLinesFormat.Line.FillFormat.FillType in op FillType.NoFill. Alleen-lezen boolean.

**Retourneert:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

Om de hoofd-rasterlijn te verbergen, stel MajorGridLinesFormat.Line.FillFormat.FillType in op FillType.NoFill. Alleen-lezen boolean.

**Retourneert:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

Geeft het formaat van de as weer. Alleen-lezen [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Retourneert:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Geeft het formaat van de tekst weer. Alleen-lezen [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retourneert:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

Haalt de titel van de as op. Alleen-lezen [IChartTitle](../../com.aspose.slides/icharttitle).

**Retourneert:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

Geeft het CrossType op de opgegeven as weer waar de andere as deze kruist. Lezen/Schrijven [CrossesType](../../com.aspose.slides/crossestype).

**Retourneert:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

Geeft het CrossType op de opgegeven as weer waar de andere as deze kruist. Lezen/Schrijven [CrossesType](../../com.aspose.slides/crossestype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Geeft de positie van de as weer. Lezen/Schrijven [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Retourneert:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Geeft de positie van de as weer. Lezen/Schrijven [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Bepaalt of een as een zichtbare titel heeft. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Bepaalt of een as een zichtbare titel heeft. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Geeft de opmaakreeks voor de As-Labels weer. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Geeft de opmaakreeks voor de As-Labels weer. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Geeft aan of de opmaak is gekoppeld aan brongegevens. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Geeft aan of de opmaak is gekoppeld aan brongegevens. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

Geeft de rotatiehoek van tick-labels weer. Lezen/Schrijven float.

**Retourneert:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

Geeft de rotatiehoek van tick-labels weer. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

Specificeert hoeveel tick-labels moeten worden overgeslagen tussen getekende labels. Toegepast op categorias of series-as. Lezen/Schrijven long.

**Retourneert:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

Specificeert hoeveel tick-labels moeten worden overgeslagen tussen getekende labels. Toegepast op categorias of series-as. Lezen/Schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |
### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

Specificeert automatische tick-label-afstand. Indien false: gebruik de eigenschap TickLabelSpacing. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

Specificeert automatische tick-label-afstand. Indien false: gebruik de eigenschap TickLabelSpacing. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

Specificeert hoeveel tick-markeringen moeten worden overgeslagen voordat de volgende wordt getekend. Toegepast op categorias of series-as. Lezen/Schrijven int.

**Retourneert:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

Specificeert hoeveel tick-markeringen moeten worden overgeslagen voordat de volgende wordt getekend. Toegepast op categorias of series-as. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |
### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

Specificeert automatische tick-markering-afstand. Indien false: gebruik de eigenschap TickMarksSpacing. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

Specificeert automatische tick-markering-afstand. Indien false: gebruik de eigenschap TickMarksSpacing. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

Specificeert de afstand van labels tot de as. Toegepast op categorias of datum-as. Waarde moet tussen 0% en 1000% liggen. Lezen/Schrijven int.

**Retourneert:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

Specificeert de afstand van labels tot de as. Toegepast op categorias of datum-as. Waarde moet tussen 0% en 1000% liggen. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Geeft het aggregatietype van de categorias (binning) weer. Toegepast op categorie. Alleen gebruikt met Histogram- of HistogramPareto-series.

**Retourneert:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Geeft het aggregatietype van de categorias (binning) weer. Toegepast op categorie. Alleen gebruikt met Histogram- of HistogramPareto-series.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Specificeert de bin-breedte wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByBinWidth. Toegepast op categorias. Alleen gebruikt met Histogram- of HistogramPareto-series.

**Retourneert:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Specificeert de bin-breedte wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByBinWidth. Toegepast op categorias. Alleen gebruikt met Histogram- of HistogramPareto-series.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Specificeert het aantal bins wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByNumberOfBins. Toegepast op categorias. Alleen gebruikt met Histogram- of HistogramPareto-series.

**Retourneert:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public   <  {
   ä  </>
```

Specificeert het aantal bins wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByNumberOfBins. Toegepast op categorias. Alleen gebruikt met Histogram- of HistogramPareto-series.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |
### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Geeft aan of een overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-bin-waarde aan te passen.

**Retourneert:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Geeft aan of een overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-bin-waarde aan te passen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Specificeert de automatische overflow-bin-waarde. Indien false: gebruik de eigenschap OverflowBin.

**Retourneert:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Specificeert de automatische overflow-bin-waarde. Indien false: gebruik de eigenschap OverflowBin.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Specificeert een aangepaste overflow-bin-waarde. Toegepast wanneer IsAutomaticOverflowBin false is en IsOverflowBin true is.

**Retourneert:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Specificeert een aangepaste overflow-bin-waarde. Toegepast wanneer IsAutomaticOverflowBin false is en IsOverflowBin true is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Geeft aan of een underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-bin-waarde aan te passen.

**Retourneert:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Geeft aan of een underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-bin-waarde aan te passen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Specificeert de automatische underflow-bin-waarde. Indien false: gebruik de eigenschap UnderflowBin.

**Retourneert:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Specificeert de automatische underflow-bin-waarde. Indien false: gebruik de eigenschap UnderflowBin.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Specificeert een aangepaste underflow-bin-waarde. Toegepast wanneer IsAutomaticUnderflowBin false is en IsUnderflowBin true is.

**Retourneert:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Specificeert een aangepaste underflow-bin-waarde. Toegepast wanneer IsAutomaticUnderflowBin false is en IsUnderflowBin true is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende slide van een FillFormat. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een FillFormat. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)