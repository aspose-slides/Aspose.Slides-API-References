---
title: IAxis
second_title: Aspose.Slides voor Java API-referentie
description: Omvat het object dat een grafiekas vertegenwoordigt.
type: docs
url: /nl/com.aspose.slides/iaxis/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Verkapselt het object dat een as van een diagram vertegenwoordigt.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Geeft aan of de waardenas de categorieas tussen categorieën kruist. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Geeft aan of de waardenas de categorieas tussen categorieën kruist. |
| [getCrossAt()](#getCrossAt--) | Geeft het punt op de as aan waar de loodrechte as deze kruist. |
| [setCrossAt(float value)](#setCrossAt-float-) | Geeft het punt op de as aan waar de loodrechte as deze kruist. |
| [getDisplayUnit()](#getDisplayUnit--) | Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. |
| [getActualMaxValue()](#getActualMaxValue--) | Specificeert de daadwerkelijke maximale waarde op de as. |
| [getActualMinValue()](#getActualMinValue--) | Specificeert de daadwerkelijke minimale waarde op de as. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Specificeert de daadwerkelijke hoofdwaarde-eenheid van de as. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Specificeert de daadwerkelijke subeenheid van de as. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Specificeert de daadwerkelijke hoofdwaarde-schaal van de as. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Specificeert de daadwerkelijke subeenheid-schaal van de as. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Geeft aan of de maximale waarde automatisch wordt toegewezen. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Geeft aan of de maximale waarde automatisch wordt toegewezen. |
| [getMaxValue()](#getMaxValue--) | Vertegenwoordigt de maximale waarde op de waardenas. |
| [setMaxValue(double value)](#setMaxValue-double-) | Vertegenwoordigt de maximale waarde op de waardenas. |
| [getMinorUnit()](#getMinorUnit--) | Vertegenwoordigt de subeenheden voor de datum- of waardenas. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Vertegenwoordigt de subeenheden voor de datum- of waardenas. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Geeft aan of de subeenheid van de as automatisch wordt toegewezen. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Geeft aan of de subeenheid van de as automatisch wordt toegewezen. |
| [getMajorUnit()](#getMajorUnit--) | Vertegenwoordigt de hoofd-eenheden voor de datum- of waardenas. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Vertegenwoordigt de hoofd-eenheden voor de datum- of waardenas. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Geeft aan of de hoofdwaarde van de as automatisch wordt toegewezen. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Geeft aan of de hoofdwaarde van de as automatisch wordt toegewezen. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Geeft aan of de minimale waarde automatisch wordt toegewezen. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Geeft aan of de minimale waarde automatisch wordt toegewezen. |
| [getMinValue()](#getMinValue--) | Vertegenwoordigt de minimale waarde op de waardenas. |
| [setMinValue(double value)](#setMinValue-double-) | Vertegenwoordigt de minimale waarde op de waardenas. |
| [isLogarithmic()](#isLogarithmic--) | Geeft aan of het schaalsoort van de waardenas logaritmisch is of niet. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Geeft aan of het schaalsoort van de waardenas logaritmisch is of niet. |
| [getLogBase()](#getLogBase--) | Vertegenwoordigt de logaritmische basis. |
| [setLogBase(double value)](#setLogBase-double-) | Vertegenwoordigt de logaritmische basis. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Geeft aan of MS PowerPoint gegevenspunten van laatst naar eerst plot. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Geeft aan of MS PowerPoint gegevenspunten van laatst naar eerst plot. |
| [isVisible()](#isVisible--) | Geeft aan of de as zichtbaar is. |
| [setVisible(boolean value)](#setVisible-boolean-) | Geeft aan of de as zichtbaar is. |
| [getMajorTickMark()](#getMajorTickMark--) | Vertegenwoordigt het type hoofd-ticmarkering voor de opgegeven as. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Vertegenwoordigt het type hoofd-ticmarkering voor de opgegeven as. |
| [getMinorTickMark()](#getMinorTickMark--) | Vertegenwoordigt het type sub-ticmarkering voor de opgegeven as. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Vertegenwoordigt het type sub-ticmarkering voor de opgegeven as. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Vertegenwoordigt de positie van tic-label-teksten op de opgegeven as. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Vertegenwoordigt de positie van tic-label-teksten op de opgegeven as. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Vertegenwoordigt de hoofd-eenheid-schaal voor de datumas. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Vertegenwoordigt de hoofd-eenheid-schaal voor de datumas. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Vertegenwoordigt de hoofd-eenheid-schaal voor de datumas. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Vertegenwoordigt de hoofd-eenheid-schaal voor de datumas. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Specificeert de kleinste tijdseenheid die op de datumas wordt weergegeven. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Specificeert de kleinste tijdseenheid die op de datumas wordt weergegeven. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Vertegenwoordigt het formaat van de sub-roosterlijnen op een diagramas. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Vertegenwoordigt het formaat van de hoofd-roosterlijnen op een diagramas. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Geeft aan of de sub-roosterlijnen werden weergegeven. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Geeft aan of de hoofd-roosterlijnen werden weergegeven. |
| [getFormat()](#getFormat--) | Vertegenwoordigt het formaat van de as. |
| [getTitle()](#getTitle--) | Haalt de titel van de as op. |
| [getCrossType()](#getCrossType--) | Vertegenwoordigt het CrossType op de opgegeven as waar de andere as kruist. |
| [setCrossType(int value)](#setCrossType-int-) | Vertegenwoordigt het CrossType op de opgegeven as waar de andere as kruist. |
| [getPosition()](#getPosition--) | Vertegenwoordigt de positie van de as. |
| [setPosition(int value)](#setPosition-int-) | Vertegenwoordigt de positie van de as. |
| [hasTitle()](#hasTitle--) | Bepaalt of een as een zichtbare titel heeft. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bepaalt of een as een zichtbare titel heeft. |
| [getNumberFormat()](#getNumberFormat--) | Vertegenwoordigt de opmaakreeks voor de as-labels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Vertegenwoordigt de opmaakreeks voor de as-labels. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Geeft aan of de opmaak gekoppeld is aan brongegevens. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Geeft aan of de opmaak gekoppeld is aan brongegevens. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Vertegenwoordigt de rotatiehoek van tic-labels. Lezen/schrijven float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Vertegenwoordigt de rotatiehoek van tic-labels. Lezen/schrijven float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Specificeert hoeveel tic-labels overgeslagen worden tussen getekende labels. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Specificeert hoeveel tic-labels overgeslagen worden tussen getekende labels. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Specificeert de automatische spreiding van tic-labels. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Specificeert de automatische spreiding van tic-labels. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Specificeert hoeveel tic-markeringen moeten worden overgeslagen vóór de volgende getekend wordt. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Specificeert hoeveel tic-markeringen moeten worden overgeslagen vóór de volgende getekend wordt. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Specificeert de automatische spreiding van tic-markeringen. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Specificeert de automatische spreiding van tic-markeringen. |
| [getLabelOffset()](#getLabelOffset--) | Specificeert de afstand van labels tot de as. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Specificeert de afstand van labels tot de as. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Specificeert het type van de categorieas. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Specificeert het type van de categorieas. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Stelt de eigenschap IAxis.CategoryAxisType in met een waarde die automatisch wordt bepaald op basis van as-gegevens. |
| [getAggregationType()](#getAggregationType--) | Vertegenwoordigt het aggregatietype van de categorieas (binnengroepen). |
| [setAggregationType(int value)](#setAggregationType-int-) | Vertegenwoordigt het aggregatietype van de categorieas (binnengroepen). |
| [getBinWidth()](#getBinWidth--) | Specificeert de breedte van de bin wanneer AggregationType-waarde is ingesteld op AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Specificeert de breedte van de bin wanneer AggregationType-waarde is ingesteld op AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Specificeert het aantal bins wanneer AggregationType-waarde is ingesteld op AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Specificeert het aantal bins wanneer AggregationType-waarde is ingesteld op AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Specificeert of een overflow-bin wordt toegepast. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Specificeert of een overflow-bin wordt toegepast. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Specificeert de automatische overflow-bin-waarde. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Specificeert de automatische overflow-bin-waarde. |
| [getOverflowBin()](#getOverflowBin--) | Specificeert een aangepaste overflow-bin-waarde. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Specificeert een aangepaste overflow-bin-waarde. |
| [isUnderflowBin()](#isUnderflowBin--) | Specificeert of een underflow-bin wordt toegepast. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Specificeert of een underflow-bin wordt toegepast. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Specificeert de automatische underflow-bin-waarde. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Specificeert de automatische underflow-bin-waarde. |
| [getUnderflowBin()](#getUnderflowBin--) | Specificeert een aangepaste underflow-bin-waarde. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Specificeert een aangepaste underflow-bin-waarde. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Geeft aan of de waardenas de categorieas tussen categorieën kruist. Deze eigenschap is alleen van toepassing op categorieassen en is niet van toepassing op 3D-diagrammen. Lezen/schrijven boolean.

**Retour:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Geeft aan of de waardenas de categorieas tussen categorieën kruist. Deze eigenschap is alleen van toepassing op categorieassen en is niet van toepassing op 3D-diagrammen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Geeft het punt op de as aan waar de loodrechte as deze kruist. Lezen/schrijven float.

**Retour:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Geeft het punt op de as aan waar de loodrechte as deze kruist. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. Lezen/schrijven [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Retour:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas. Lezen/schrijven [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Specificeert de daadwerkelijke maximale waarde op de as. Roep eerst IChart.ValidateChartLayout() aan om de feitelijke waarde te verkrijgen.

**Retour:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Specificeert de daadwerkelijke minimale waarde op de as. Roep eerst IChart.ValidateChartLayout() aan om de feitelijke waarde te verkrijgen.

**Retour:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Specificeert de daadwerkelijke hoofd-eenheid van de as. Roep eerst IChart.ValidateChartLayout() aan om de feitelijke waarde te verkrijgen.

**Retour:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Specificeert de daadwerkelijke sub-eenheid van de as. Roep eerst IChart.ValidateChartLayout() aan om de feitelijke waarde te verkrijgen.

**Retour:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Specificeert de daadwerkelijke hoofd-eenheid-schaal van de as. Roep eerst IChart.ValidateChartLayout() aan om de feitelijke waarde te verkrijgen.

**Retour:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Specificeert de daadwerkelijke sub-eenheid-schaal van de as. Roep eerst IChart.ValidateChartLayout() aan om de feitelijke waarde te verkrijgen.

**Retour:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Geeft aan of de maximale waarde automatisch wordt toegewezen. Lezen/schrijven boolean.

**Retour:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Geeft aan of de maximale waarde automatisch wordt toegewezen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Vertegenwoordigt de maximale waarde op de waardenas. Lezen/schrijven double.

**Retour:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Vertegenwoordigt de maximale waarde op de waardenas. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Vertegenwoordigt de sub-eenheden voor de datum- of waardenas. Lezen/schrijven double.

**Retour:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Vertegenwoordigt de sub-eenheden voor de datum- of waardenas. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Geeft aan of de sub-eenheid van de as automatisch wordt toegewezen. Lezen/schrijven boolean.

**Retour:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Geeft aan of de sub-eenheid van de as automatisch wordt toegewezen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Vertegenwoordigt de hoofd-eenheden voor de datum- of waardenas. Lezen/schrijven double.

**Retour:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Vertegenwoordigt de hoofd-eenheden voor de datum- of waardenas. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Geeft aan of de hoofd-eenheid van de as automatisch wordt toegewezen. Lezen/schrijven boolean.

**Retour:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Geeft aan of de belangrijkste eenheid van de as automatisch wordt toegewezen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Geeft aan of de minimumwaarde automatisch wordt toegewezen. Lezen/schrijven boolean.

**Retour:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Geeft aan of de minimumwaarde automatisch wordt toegewezen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Geeft de minimumwaarde op de waardenas weer. Lezen/schrijven double.

**Retour:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Geeft de minimumwaarde op de waardenas weer. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Geeft aan of het schaaltype van de waardenas logaritmisch is of niet. Lezen/schrijven boolean.

**Retour:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Geeft aan of het schaaltype van de waardenas logaritmisch is of niet. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Geeft de logaritmische basis weer. Standaardwaarde is 10. Lezen/schrijven double.

**Retour:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Geeft de logaritmische basis weer. Standaardwaarde is 10. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Geeft aan of MS PowerPoint gegevenspunten van laatst naar eerst plot. Lezen/schrijven boolean.

**Retour:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Geeft aan of MS PowerPoint gegevenspunten van laatst naar eerst plot. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Geeft aan of de as zichtbaar is. Lezen/schrijven boolean.

**Retour:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Geeft aan of de as zichtbaar is. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Geeft het type hoofd-tickmarkering voor de opgegeven as weer. Lezen/schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retour:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Geeft het type hoofd-tickmarkering voor de opgegeven as weer. Lezen/schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Geeft het type sub-tickmarkering voor de opgegeven as weer. Lezen/schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retour:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Geeft het type sub-tickmarkering voor de opgegeven as weer. Lezen/schrijven [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Geeft de positie van tick-label-tekens op de opgegeven as weer. Lezen/schrijven [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Retour:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Geeft de positie van tick-label-tekens op de opgegeven as weer. Lezen/schrijven [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Geeft de schaal van de hoofd-eenheid voor de datum-as weer. Lezen/schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retour:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Geeft de schaal van de hoofd-eenheid voor de datum-as weer. Lezen/schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Geeft de schaal van de hoofd-eenheid voor de datum-as weer. Lezen/schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retour:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Geeft de schaal van de hoofd-eenheid voor de datum-as weer. Lezen/schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Specificeert de kleinste tijdseenheid die op de datum-as wordt weergegeven. Lezen/schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retour:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Specificeert de kleinste tijdseenheid die op de datum-as wordt weergegeven. Lezen/schrijven [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Geeft het formaat van de onderliggende rasterlijnen op een grafiekas weer. Alleen-lezen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retour:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Geeft het formaat van de hoofd-rasterlijnen op een grafiekas weer. Alleen-lezen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retour:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Geeft aan of de onderliggende rasterlijnen worden weergegeven. Alleen-lezen boolean.

**Retour:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Geeft aan of de hoofd-rasterlijnen worden weergegeven. Alleen-lezen boolean.

**Retour:**
boolean
### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Geeft het formaat van de as weer. Alleen-lezen [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Retour:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Haalt de titel van de as op. Alleen-lezen [IChartTitle](../../com.aspose.slides/icharttitle).

**Retour:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Geeft het CrossType op de opgegeven as weer waar de andere as kruist. Lezen/schrijven [CrossesType](../../com.aspose.slides/crossestype).

**Retour:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Geeft het CrossType op de opgegeven as weer waar de andere as kruist. Lezen/schrijven [CrossesType](../../com.aspose.slides/crossestype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Geeft de positie van de as weer. Lezen/schrijven [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Retour:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Geeft de positie van de as weer. Lezen/schrijven [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Bepaalt of een as een zichtbare titel heeft. Lezen/schrijven boolean.

**Retour:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Bepaalt of een as een zichtbare titel heeft. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Geeft de opmaak-string voor de as-labels weer. Lezen/schrijven String.

**Retour:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Geeft de opmaak-string voor de as-labels weer. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Geeft aan of de opmaak is gekoppeld aan brongegevens. Lezen/schrijven boolean.

**Retour:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Geeft aan of de opmaak is gekoppeld aan brongegevens. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Geeft de rotatiehoek van tick-labels weer. Lezen/schrijven float.

**Retour:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Geeft de rotatiehoek van tick-labels weer. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Specificeert hoeveel tick-labels overgeslagen moeten worden tussen labels die worden getekend. Lezen/schrijven long.

**Retour:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Specificeert hoeveel tick-labels overgeslagen moeten worden tussen labels die worden getekend. Lezen/schrijven long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Specificeert de automatische waarde voor tick-label-spacing. Indien false: gebruik de TickLabelSpacing-eigenschap. Lezen/schrijven boolean.

**Retour:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Specificeert de automatische waarde voor tick-label-spacing. Indien false: gebruik de TickLabelSpacing-eigenschap. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Specificeert hoeveel tick-markeringen overgeslagen moeten worden voordat de volgende wordt getekend. Toegepast op categorie- of serie-as. Lezen/schrijven int.

**Retour:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Specificeert hoeveel tick-markeringen overgeslagen moeten worden voordat de volgende wordt getekend. Toegepast op categorie- of serie-as. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Specificeert de automatische waarde voor tick-mark-spacing. Indien false: gebruik de TickMarksSpacing-eigenschap. Lezen/schrijven boolean.

**Retour:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Specificeert de automatische waarde voor tick-mark-spacing. Indien false: gebruik de TickMarksSpacing-eigenschap. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Specificeert de afstand van labels tot de as. Toegepast op categorie- of datum-as. Waarde moet tussen 0% en 1000% liggen. Lezen/schrijven int.

**Retour:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Specificeert de afstand van labels tot de as. Toegepast op categorie- of datum-as. Waarde moet tussen 0% en 1000% liggen. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Specificeert het type van de categorie-as. Lezen/schrijven [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Retour:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Specificeert het type van de categorie-as. Lezen/schrijven [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Stelt de IAxis.CategoryAxisType-eigenschap in met een waarde die automatisch wordt bepaald op basis van as-gegevens.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Geeft het aggregatietype van de categorie-as weer (groepering). Toegepast op categorie. Alleen gebruikt met Histogram- of HistogramPareto-reeksen.

**Retour:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Geeft het aggregatietype van de categorie-as weer (groepering). Toegepast op categorie. Alleen gebruikt met Histogram- of HistogramPareto-reeksen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Specificeert de breedte van de bin wanneer de AggregationType-eigenschapwaarde is ingesteld op AxisAggregationType.ByBinWidth. Toegepast op categorische assen. Alleen te gebruiken met Histogram- of HistogramPareto-series.

**Retour:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Specificeert de breedte van de bin wanneer de AggregationType-eigenschapwaarde is ingesteld op AxisAggregationType.ByBinWidth. Toegepast op categorische assen. Alleen te gebruiken met Histogram- of HistogramPareto-series.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Specificeert het aantal bins wanneer de AggregationType-eigenschapwaarde is ingesteld op AxisAggregationType.ByNumberOfBins. Toegepast op categorische assen. Alleen te gebruiken met Histogram- of HistogramPareto-series.

**Retour:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Specificeert het aantal bins wanneer de AggregationType-eigenschapwaarde is ingesteld op AxisAggregationType.ByNumberOfBins. Toegepast op categorische assen. Alleen te gebruiken met Histogram- of HistogramPareto-series.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Specificeert of de overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-bin-waarde aan te passen.

**Retour:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Specificeert of de overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-bin-waarde aan te passen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Specificeert de automatische overflow-bin-waarde. Als false: gebruik de OverflowBin-eigenschap.

**Retour:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Specificeert de automatische overflow-bin-waarde. Als false: gebruik de OverflowBin-eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Specificeert de aangepaste waarde voor de overflow-bin. Toegepast wanneer de IsAutomaticOverflowBin-eigenschap is ingesteld op false en de IsOverflowBin-eigenschap true is.

**Retour:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Specificeert de aangepaste waarde voor de overflow-bin. Toegepast wanneer de IsAutomaticOverflowBin-eigenschap is ingesteld op false en de IsOverflowBin-eigenschap true is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Specificeert of de underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-bin-waarde aan te passen.

**Retour:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Specificeert of de underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-bin-waarde aan te passen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Specificeert de automatische underflow-bin-waarde. Als false: gebruik de UnderflowBin-eigenschap.

**Retour:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Specificeert de automatische underflow-bin-waarde. Als false: gebruik de UnderflowBin-eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Specificeert de aangepaste waarde voor de underflow-bin. Toegepast wanneer de IsAutomaticUnderflowBin-eigenschap is ingesteld op false en de IsUnderflowBin-eigenschap true is.

**Retour:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Specificeert de aangepaste waarde voor de underflow-bin. Toegepast wanneer de IsAutomaticUnderflowBin-eigenschap is ingesteld op false en de IsUnderflowBin-eigenschap true is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |