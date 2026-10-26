---
title: IAxis
second_title: Aspose.Slides voor Android via Java API-referentie
description: Omsluit het object dat een as van een grafiek vertegenwoordigt.
type: docs
url: /nl/com.aspose.slides/iaxis/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Omsluit het object dat een as van een grafiek vertegenwoordigt.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Geeft aan of de waardas de categorieas tussen categorieën kruist. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Geeft aan of de waardas de categorieas tussen categorieën kruist. |
| [getCrossAt()](#getCrossAt--) | Geeft het punt op de as weer waar de loodrechte as deze kruist. |
| [setCrossAt(float value)](#setCrossAt-float-) | Geeft het punt op de as weer waar de loodrechte as deze kruist. |
| [getDisplayUnit()](#getDisplayUnit--) | Specificeert de schaalwaarde van de weergave-eenheden voor de waardas. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Specificeert de schaalwaarde van de weergave-eenheden voor de waardas. |
| [getActualMaxValue()](#getActualMaxValue--) | Specificeert de daadwerkelijke maximale waarde op de as. |
| [getActualMinValue()](#getActualMinValue--) | Specificeert de daadwerkelijke minimale waarde op de as. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Specificeert de daadwerkelijke hoofd-eenheid van de as. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Specificeert de daadwerkelijke onder-eenheid van de as. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Specificeert de schaal van de daadwerkelijke hoofd-eenheid van de as. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Specificeert de schaal van de daadwerkelijke onder-eenheid van de as. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Geeft aan of de maximale waarde automatisch wordt toegewezen. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Geeft aan of de maximale waarde automatisch wordt toegewezen. |
| [getMaxValue()](#getMaxValue--) | Geeft de maximale waarde op de waardas weer. |
| [setMaxValue(double value)](#setMaxValue-double-) | Geeft de maximale waarde op de waardas weer. |
| [getMinorUnit()](#getMinorUnit--) | Geeft de onder-eenheden weer voor de datum- of waardas. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Geeft de onder-eenheden weer voor de datum- of waardas. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Geeft aan of de onder-eenheid van de as automatisch wordt toegewezen. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Geeft aan of de onder-eenheid van de as automatisch wordt toegewezen. |
| [getMajorUnit()](#getMajorUnit--) | Geeft de hoofd-eenheden weer voor de datum- of waardas. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Geeft de hoofd-eenheden weer voor de datum- of waardas. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Geeft aan of de hoofd-eenheid van de as automatisch wordt toegewezen. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Geeft aan of de hoofd-eenheid van de as automatisch wordt toegewezen. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Geeft aan of de minimale waarde automatisch wordt toegewezen. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Geeft aan of de minimale waarde automatisch wordt toegewezen. |
| [getMinValue()](#getMinValue--) | Geeft de minimale waarde op de waardas weer. |
| [setMinValue(double value)](#setMinValue-double-) | Geeft de minimale waarde op de waardas weer. |
| [isLogarithmic()](#isLogarithmic--) | Geeft aan of het schaaltype van de waardas logaritmisch is of niet. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Geeft aan of het schaaltype van de waardas logaritmisch is of niet. |
| [getLogBase()](#getLogBase--) | Geeft de logaritmische basis weer. |
| [setLogBase(double value)](#setLogBase-double-) | Geeft de logaritmische basis weer. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Geeft aan of MS PowerPoint gegevenspunten van laatste naar eerste plot. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Geeft aan of MS PowerPoint gegevenspunten van laatste naar eerste plot. |
| [isVisible()](#isVisible--) | Geeft aan of de as zichtbaar is. |
| [setVisible(boolean value)](#setVisible-boolean-) | Geeft aan of de as zichtbaar is. |
| [getMajorTickMark()](#getMajorTickMark--) | Geeft het type hoofd-tikmarkering weer voor de opgegeven as. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Geeft het type hoofd-tikmarkering weer voor de opgegeven as. |
| [getMinorTickMark()](#getMinorTickMark--) | Geeft het type onder-tikmarkering weer voor de opgegeven as. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Geeft het type onder-tikmarkering weer voor de opgegeven as. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Geeft de positie van tikmarkering-labels weer op de opgegeven as. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Geeft de positie van tikmarkering-labels weer op de opgegeven as. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Geeft de schaal van de hoofd-eenheid weer voor de datumas. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Geeft de schaal van de hoofd-eenheid weer voor de datumas. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Geeft de schaal van de hoofd-eenheid weer voor de datumas. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Geeft de schaal van de hoofd-eenheid weer voor de datumas. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Specificeert de kleinste tijdseenheid die op de datumas wordt weergegeven. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Specificeert de kleinste tijdseenheid die op de datumas wordt weergegeven. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Geeft het formaat van de onder-rasterlijnen weer op een grafiekas. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Geeft het formaat van de hoofd-rasterlijnen weer op een grafiekas. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Geeft aan of de onder-rasterlijnen worden weergegeven. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Geeft aan of de hoofd-rasterlijnen worden weergegeven. |
| [getFormat()](#getFormat--) | Geeft het formaat van de as weer. |
| [getTitle()](#getTitle--) | Haalt de titel van de as op. |
| [getCrossType()](#getCrossType--) | Geeft het kruistype weer op de opgegeven as waar de andere as kruist. |
| [setCrossType(int value)](#setCrossType-int-) | Geeft het kruistype weer op de opgegeven as waar de andere as kruist. |
| [getPosition()](#getPosition--) | Geeft de positie van de as weer. |
| [setPosition(int value)](#setPosition-int-) | Geeft de positie van de as weer. |
| [hasTitle()](#hasTitle--) | Bepaalt of een as een zichtbare titel heeft. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bepaalt of een as een zichtbare titel heeft. |
| [getNumberFormat()](#getNumberFormat--) | Geeft de opmaakreeks voor de as-labels weer. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Geeft de opmaakreeks voor de as-labels weer. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Geeft aan of de opmaak gekoppeld is aan brongegevens. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Geeft aan of de opmaak gekoppeld is aan brongegevens. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Geeft de rotatiehoek van tik-labels weer. Lezen/Schrijven float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Geeft de rotatiehoek van tik-labels weer. Lezen/Schrijven float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Specificeert hoeveel tik-labels moeten worden overgeslagen tussen getekende labels. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Specificeert hoeveel tik-labels moeten worden overgeslagen tussen getekende labels. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Specificeert de automatische waarde voor de spatiëring van tik-labels. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Specificeert de automatische waarde voor de spatiëring van tik-labels. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Specificeert hoeveel tik-markeringen moeten worden overgeslagen voordat de volgende getekend wordt. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Specificeert hoeveel tik-markeringen moeten worden overgeslagen voordat de volgende getekend wordt. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Specificeert de automatische spatiëring van tik-markeringen. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Specificeert de automatische spatiëring van tik-markeringen. |
| [getLabelOffset()](#getLabelOffset--) | Specificeert de afstand van labels tot de as. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Specificeert de afstand van labels tot de as. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Specificeert het type van de categorie-as. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Specificeert het type van de categorie-as. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Stelt de eigenschap IAxis.CategoryAxisType in met een waarde die automatisch wordt bepaald op basis van as-data. |
| [getAggregationType()](#getAggregationType--) | Geeft het aggregatietype van de categorie-as weer (binning). |
| [setAggregationType(int value)](#setAggregationType-int-) | Geeft het aggregatietype van de categorie-as weer (binning). |
| [getBinWidth()](#getBinWidth--) | Specificeert de bin-breedte wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Specificeert de bin-breedte wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Specificeert het aantal bins wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Specificeert het aantal bins wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Geeft aan of een overflow-bin wordt toegepast. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Geeft aan of een overflow-bin wordt toegepast. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Specificeert de automatische overflow-bin-waarde. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Specificeert de automatische overflow-bin-waarde. |
| [getOverflowBin()](#getOverflowBin--) | Specificeert een aangepaste overflow-bin-waarde. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Specificeert een aangepaste overflow-bin-waarde. |
| [isUnderflowBin()](#isUnderflowBin--) | Geeft aan of een underflow-bin wordt toegepast. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Geeft aan of een underflow-bin wordt toegepast. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Specificeert de automatische underflow-bin-waarde. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Specificeert de automatische underflow-bin-waarde. |
| [getUnderflowBin()](#getUnderflowBin--) | Specificeert een aangepaste underflow-bin-waarde. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Specificeert een aangepaste underflow-bin-waarde. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Geeft aan of de waardas de categorieas tussen categorieën kruist. Deze eigenschap is alleen van toepassing op categorie-assen en geldt niet voor 3-D-grafieken. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Geeft aan of de waardas de categorieas tussen categorieën kruist. Deze eigenschap is alleen van toepassing op categorie-assen en geldt niet voor 3-D-grafieken. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Geeft het punt op de as weer waar de loodrechte as deze kruist. Lezen/Schrijven float.

**Retourneert:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Geeft het punt op de as weer waar de loodrechte as deze kruist. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Specificeert de schaalwaarde van de weergave-eenheden voor de waardas. Lezen/Schrijven [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Retourneert:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Specificeert de schaalwaarde van de weergave-eenheden voor de waardas. Lezen/Schrijven [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Specificeert de daadwerkelijke maximale waarde op de as. Roep eerst IChart.ValidateChartLayout() aan om de daadwerkelijke waarde te verkrijgen.

**Retourneert:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Specificeert de daadwerkelijke minimale waarde op de as. Roep eerst IChart.ValidateChartLayout() aan om de daadwerkelijke waarde te verkrijgen.

**Retourneert:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Specificeert de daadwerkelijke hoofd-eenheid van de as. Roep eerst IChart.ValidateChartLayout() aan om de daadwerkelijke waarde te verkrijgen.

**Retourneert:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Specificeert de daadwerkelijke onder-eenheid van de as. Roep eerst IChart.ValidateChartLayout() aan om de daadwerkelijke waarde te verkrijgen.

**Retourneert:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Specificeert de schaal van de daadwerkelijke hoofd-eenheid van de as. Roep eerst IChart.ValidateChartLayout() aan om de daadwerkelijke waarde te verkrijgen.

**Retourneert:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Specificeert de schaal van de daadwerkelijke onder-eenheid van de as. Roep eerst IChart.ValidateChartLayout() aan om de daadwerkelijke waarde te verkrijgen.

**Retourneert:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Geeft aan of de maximale waarde automatisch wordt toegewezen. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Geeft aan of de maximale waarde automatisch wordt toegewezen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Geeft de maximale waarde op de waardas weer. Lezen/Schrijven double.

**Retourneert:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Geeft de maximale waarde op de waardas weer. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Geeft de onder-eenheden weer voor de datum- of waardas. Lezen/Schrijven double.

**Retourneert:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Geeft de onder-eenheden weer voor de datum- of waardas. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Geeft aan of de onder-eenheid van de as automatisch wordt toegewezen. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Geeft aan of de onder-eenheid van de as automatisch wordt toegewezen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Geeft de hoofd-eenheden weer voor de datum- of waardas. Lezen/Schrijven double.

**Retourneert:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Geeft de hoofd-eenheden weer voor de datum- of waardas. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Geeft aan of de hoofd-eenheid van de as automatisch wordt toegewezen. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Geeft aan of de hoofd-eenheid van de as automatisch wordt toegewezen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Geeft aan of de minimale waarde automatisch wordt toegewezen. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Geeft aan of de minimale waarde automatisch wordt toegewezen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Geeft de minimale waarde op de waardas weer. Lezen/Schrijven double.

**Retourneert:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Geeft de minimale waarde op de waardas weer. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Geeft aan of het schaaltype van de waardas logaritmisch is of niet. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Geeft aan of het schaaltype van de waardas logaritmisch is of niet. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Geeft de logaritmische basis weer. Standaardwaarde is 10. Lezen/Schrijven double.

**Retourneert:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Geeft de logaritmische basis weer. Standaardwaarde is 10. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Geeft aan of MS PowerPoint gegevenspunten van laatste naar eerste plot. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Geeft aan of MS PowerPoint gegevenspunten van laatste naar eerste plot. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Geeft aan of de as zichtbaar is. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Geeft aan of de as zichtbaar is. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Geeft het type hoofd-tikmarkering weer voor de opgegeven as. Lezen/Schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retourneert:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Geeft het type hoofd-tikmarkering weer voor de opgegeven as. Lezen/Schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Geeft het type onder-tikmarkering weer voor de opgegeven as. Lezen/Schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retourneert:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Geeft het type onder-tikmarkering weer voor de opgegeven as. Lezen/Schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Geeft de positie van tik-label-markeringen weer op de opgegeven as. Lezen/Schrijven [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Retourneert:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Geeft de positie van tik-label-markeringen weer op de opgegeven as. Lezen/Schrijven [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Geeft de schaal van de hoofd-eenheid weer voor de datumas. Lezen/Schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retourneert:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Geeft de schaal van de hoofd-eenheid weer voor de datumas. Lezen/Schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Geeft de schaal van de hoofd-eenheid weer voor de datumas. Lezen/Schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retourneert:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Geeft de schaal van de hoofd-eenheid weer voor de datumas. Lezen/Schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Specificeert de kleinste tijdseenheid die op de datumas wordt weergegeven. Lezen/Schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retourneert:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Specificeert de kleinste tijdseenheid die op de datumas wordt weergegeven. Lezen/Schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Geeft het formaat van de onder-rasterlijnen weer op een grafiekas. Alleen-lezen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retourneert:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Geeft het formaat van de hoofd-rasterlijnen weer op een grafiekas. Alleen-lezen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retourneert:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Geeft aan of de onder-rasterlijnen worden weergegeven. Alleen-lezen boolean.

**Retourneert:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Geeft aan of de hoofd-rasterlijnen worden weergegeven. Alleen-lezen boolean.

**Retourneert:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Geeft het formaat van de as weer. Alleen-lezen [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Retourneert:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Haalt de titel van de as op. Alleen-lezen [IChartTitle](../../com.aspose.slides/icharttitle).

**Retourneert:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Geeft het kruistype weer op de opgegeven as waar de andere as kruist. Lezen/Schrijven [CrossesType](../../com.aspose.slides/crossestype).

**Retourneert:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Geeft het kruistype weer op de opgegeven as waar de andere as kruist. Lezen/Schrijven [CrossesType](../../com.aspose.slides/crossestype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Geeft de positie van de as weer. Lezen/Schrijven [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Retourneert:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Geeft de positie van de as weer. Lezen/Schrijven [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Bepaalt of een as een zichtbare titel heeft. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Bepaalt of een as een zichtbare titel heeft. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Geeft de opmaakreeks voor de as-labels weer. Lezen/Schrijven String.

**Retourneert:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Geeft de opmaakreeks voor de as-labels weer. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Geeft aan of de opmaak gekoppeld is aan brongegevens. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Geeft aan of de opmaak gekoppeld is aan brongegevens. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Geeft de rotatiehoek van tik-labels weer. Lezen/Schrijven float.

**Retourneert:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Geeft de rotatiehoek van tik-labels weer. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Specificeert hoeveel tik-labels moeten worden overgeslagen tussen getekende labels. Lezen/Schrijven long.

**Retourneert:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Specificeert hoeveel tik-labels moeten worden overgeslagen tussen getekende labels. Lezen/Schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Specificeert de automatische waarde voor de spatiëring van tik-labels. Als false: gebruik de eigenschap TickLabelSpacing. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Specificeert de automatische waarde voor de spatiëring van tik-labels. Als false: gebruik de eigenschap TickLabelSpacing. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Specificeert hoeveel tik-markeringen moeten worden overgeslagen voordat de volgende getekend wordt. Van toepassing op categorie- of serie-as. Lezen/Schrijven int.

**Retourneert:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Specificeert hoeveel tik-markeringen moeten worden overgeslagen voordat de volgende getekend wordt. Van toepassing op categorie- of serie-as. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Specificeert de automatische waarde voor de spatiëring van tik-markeringen. Als false: gebruik de eigenschap TickMarksSpacing. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Specificeert de automatische waarde voor de spatiëring van tik-markeringen. Als false: gebruik de eigenschap TickMarksSpacing. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Specificeert de afstand van labels tot de as. Van toepassing op categorie- of datum-as. Waarde moet tussen 0 % en 1000 % liggen. Lezen/Schrijven int.

**Retourneert:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Specificeert de afstand van labels tot de as. Van toepassing op categorie- of datum-as. Waarde moet tussen 0 % en 1000 % liggen. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Specificeert het type van de categorie-as. Lezen/Schrijven [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Retourneert:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Specificeert het type van de categorie-as. Lezen/Schrijven [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Stelt de eigenschap IAxis.CategoryAxisType in met een automatisch bepaalde waarde op basis van as-data.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Geeft het aggregatietype van de categorie-as weer (binning). Van toepassing op categorie. Alleen te gebruiken met Histogram- of HistogramPareto-series.

**Retourneert:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Geeft het aggregatietype van de categorie-as weer (binning). Van toepassing op categorie. Alleen te gebruiken met Histogram- of HistogramPareto-series.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Specificeert de bin-breedte wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByBinWidth. Van toepassing op categorie-assen. Alleen te gebruiken met Histogram- of HistogramPareto-series.

**Retourneert:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Specificeert de bin-breedte wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByBinWidth. Van toepassing op categorie-assen. Alleen te gebruiken met Histogram- of HistogramPareto-series.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Specificeert het aantal bins wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByNumberOfBins. Van toepassing op categorie-assen. Alleen te gebruiken met Histogram- of HistogramPareto-series.

**Retourneert:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Specificeert het aantal bins wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByNumberOfBins. Van toepassing op categorie-assen. Alleen te gebruiken met Histogram- of HistogramPareto-series.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Geeft aan of een overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-bin-waarde aan te passen.

**Retourneert:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Geeft aan of een overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-bin-waarde aan te passen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Specificeert de automatische overflow-bin-waarde. Als false: gebruik de eigenschap OverflowBin.

**Retourneert:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Specificeert de automatische overflow-bin-waarde. Als false: gebruik de eigenschap OverflowBin.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Geeft de aangepaste overflow-bin-waarde weer. Van toepassing wanneer IsAutomaticOverflowBin is ingesteld op false en IsOverflowBin is true.

**Retourneert:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Geeft de aangepaste overflow-bin-waarde weer. Van toepassing wanneer IsAutomaticOverflowBin is ingesteld op false en IsOverflowBin is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Geeft aan of een underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-bin-waarde aan te passen.

**Retourneert:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Geeft aan of een underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-bin-waarde aan te passen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Specificeert de automatische underflow-bin-waarde. Als false: gebruik de eigenschap UnderflowBin.

**Retourneert:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Specificeert de automatische underflow-bin-waarde. Als false: gebruik de eigenschap UnderflowBin.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Geeft de aangepaste underflow-bin-waarde weer. Van toepassing wanneer IsAutomaticUnderflowBin is ingesteld op false en IsUnderflowBin is true.

**Retourneert:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Geeft de aangepaste underflow-bin-waarde weer. Van toepassing wanneer IsAutomaticUnderflowBin is ingesteld op false en IsUnderflowBin is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |