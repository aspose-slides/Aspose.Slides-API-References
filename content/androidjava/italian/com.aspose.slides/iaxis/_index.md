---
title: IAxis
second_title: Riferimento API Java di Aspose.Slides per Android
description: Incapsula l'oggetto che rappresenta l'asse di un grafico.
type: docs
url: /it/com.aspose.slides/iaxis/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Incapsula l'oggetto che rappresenta l'asse di un grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Rappresenta se l'asse dei valori attraversa l'asse delle categorie tra le categorie. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Rappresenta se l'asse dei valori attraversa l'asse delle categorie tra le categorie. |
| [getCrossAt()](#getCrossAt--) | Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. |
| [setCrossAt(float value)](#setCrossAt-float-) | Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. |
| [getDisplayUnit()](#getDisplayUnit--) | Specifica il valore di scala delle unità di visualizzazione per l'asse dei valori. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Specifica il valore di scala delle unità di visualizzazione per l'asse dei valori. |
| [getActualMaxValue()](#getActualMaxValue--) | Specifica il valore massimo reale sull'asse. |
| [getActualMinValue()](#getActualMinValue--) | Specifica il valore minimo reale sull'asse. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Specifica l'unità principale reale dell'asse. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Specifica l'unità secondaria reale dell'asse. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Specifica la scala dell'unità principale reale dell'asse. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Specifica la scala dell'unità secondaria reale dell'asse. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Indica se il valore massimo è assegnato automaticamente. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Indica se il valore massimo è assegnato automaticamente. |
| [getMaxValue()](#getMaxValue--) | Rappresenta il valore massimo sull'asse dei valori. |
| [setMaxValue(double value)](#setMaxValue-double-) | Rappresenta il valore massimo sull'asse dei valori. |
| [getMinorUnit()](#getMinorUnit--) | Rappresenta le unità secondarie per l'asse della data o dei valori. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Rappresenta le unità secondarie per l'asse della data o dei valori. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indica se l'unità secondaria dell'asse è assegnata automaticamente. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indica se l'unità secondaria dell'asse è assegnata automaticamente. |
| [getMajorUnit()](#getMajorUnit--) | Rappresenta le unità principali per l'asse della data o dei valori. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Rappresenta le unità principali per l'asse della data o dei valori. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Indica se l'unità principale dell'asse è assegnata automaticamente. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Indica se l'unità principale dell'asse è assegnata automaticamente. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Indica se il valore minimo è assegnato automaticamente. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Indica se il valore minimo è assegnato automaticamente. |
| [getMinValue()](#getMinValue--) | Rappresenta il valore minimo sull'asse dei valori. |
| [setMinValue(double value)](#setMinValue-double-) | Rappresenta il valore minimo sull'asse dei valori. |
| [isLogarithmic()](#isLogarithmic--) | Rappresenta se il tipo di scala dell'asse dei valori è logaritmico o meno. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Rappresenta se il tipo di scala dell'asse dei valori è logaritmico o meno. |
| [getLogBase()](#getLogBase--) | Rappresenta la base logaritmica. |
| [setLogBase(double value)](#setLogBase-double-) | Rappresenta la base logaritmica. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo. |
| [isVisible()](#isVisible--) | Rappresenta se l'asse è visibile. |
| [setVisible(boolean value)](#setVisible-boolean-) | Rappresenta se l'asse è visibile. |
| [getMajorTickMark()](#getMajorTickMark--) | Rappresenta il tipo di segno di spunta principale per l'asse specificato. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Rappresenta il tipo di segno di spunta principale per l'asse specificato. |
| [getMinorTickMark()](#getMinorTickMark--) | Rappresenta il tipo di segno di spunta secondario per l'asse specificato. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Rappresenta il tipo di segno di spunta secondario per l'asse specificato. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Rappresenta la posizione delle etichette dei segni di spunta sull'asse specificato. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Rappresenta la posizione delle etichette dei segni di spunta sull'asse specificato. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Rappresenta la scala dell'unità principale per l'asse della data. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Rappresenta la scala dell'unità principale per l'asse della data. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Rappresenta la scala dell'unità principale per l'asse della data. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Rappresenta la scala dell'unità principale per l'asse della data. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Specifica l'unità di tempo più piccola rappresentata sull'asse della data. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Specifica l'unità di tempo più piccola rappresentata sull'asse della data. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Rappresenta il formato delle linee della griglia secondarie su un asse del grafico. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Rappresenta il formato delle linee della griglia principali su un asse del grafico. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Rappresenta se le linee della griglia secondarie sono visualizzate. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Rappresenta se le linee della griglia principali sono visualizzate. |
| [getFormat()](#getFormat--) | Rappresenta il formato dell'asse. |
| [getTitle()](#getTitle--) | Ottiene il titolo dell'asse. |
| [getCrossType()](#getCrossType--) | Rappresenta il CrossType sull'asse specificato dove l'altro asse lo attraversa. |
| [setCrossType(int value)](#setCrossType-int-) | Rappresenta il CrossType sull'asse specificato dove l'altro asse lo attraversa. |
| [getPosition()](#getPosition--) | Rappresenta la posizione dell'asse. |
| [setPosition(int value)](#setPosition-int-) | Rappresenta la posizione dell'asse. |
| [hasTitle()](#hasTitle--) | Determina se un asse ha un titolo visibile. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determina se un asse ha un titolo visibile. |
| [getNumberFormat()](#getNumberFormat--) | Rappresenta la stringa di formato per le etichette dell'asse. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Rappresenta la stringa di formato per le etichette dell'asse. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Indica se il formato è collegato ai dati di origine. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Indica se il formato è collegato ai dati di origine. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Rappresenta l'angolo di rotazione delle etichette di spunta Lettura/Scrittura float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Rappresenta l'angolo di rotazione delle etichette di spunta Lettura/Scrittura float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Specifica quante etichette di spunta saltare tra le etichette disegnate. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Specifica quante etichette di spunta saltare tra le etichette disegnate. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Specifica il valore di spaziatura automatico delle etichette di spunta. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Specifica il valore di spaziatura automatico delle etichette di spunta. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Specifica quante spunte devono essere saltate prima che la successiva venga disegnata. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Specifica quante spunte devono essere saltate prima che la successiva venga disegnata. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Specifica il valore di spaziatura automatico delle spunte. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Specifica il valore di spaziatura automatico delle spunte. |
| [getLabelOffset()](#getLabelOffset--) | Specifica la distanza delle etichette dall'asse. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Specifica la distanza delle etichette dall'asse. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Specifica il tipo di asse della categoria. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Specifica il tipo di asse della categoria. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Imposta la proprietà IAxis.CategoryAxisType con un valore determinato automaticamente in base ai dati dell'asse. |
| [getAggregationType()](#getAggregationType--) | Rappresenta il tipo di aggregazione dell'asse della categoria (binning). |
| [setAggregationType(int value)](#setAggregationType-int-) | Rappresenta il tipo di aggregazione dell'asse della categoria (binning). |
| [getBinWidth()](#getBinWidth--) | Specifica la larghezza del bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Specifica la larghezza del bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Specifica il numero di bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Specifica il numero di bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Specifica se è applicato il bin di overflow. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Specifica se è applicato il bin di overflow. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Specifica il valore automatico del bin di overflow. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Specifica il valore automatico del bin di overflow. |
| [getOverflowBin()](#getOverflowBin--) | Specifica il valore personalizzato del bin di overflow. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Specifica il valore personalizzato del bin di overflow. |
| [isUnderflowBin()](#isUnderflowBin--) | Specifica se è applicato il bin di underflow. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Specifica se è applicato il bin di underflow. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Specifica il valore automatico del bin di underflow. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Specifica il valore automatico del bin di underflow. |
| [getUnderflowBin()](#getUnderflowBin--) | Specifica il valore personalizzato del bin di underflow. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Specifica il valore personalizzato del bin di underflow. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Rappresenta se l'asse dei valori attraversa l'asse delle categorie tra le categorie. Questa proprietà si applica solo agli assi delle categorie e non si applica ai grafici 3-D. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Rappresenta se l'asse dei valori attraversa l'asse delle categorie tra le categorie. Questa proprietà si applica solo agli assi delle categorie e non si applica ai grafici 3-D. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. Lettura/Scrittura float.

**Restituisce:**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. Lettura/Scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Specifică il valore di scala delle unità di visualizzazione per l'asse dei valori. Lettura/Scrittura [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Restituisce:**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Specifică il valore di scala delle unità di visualizzazione per l'asse dei valori. Lettura/Scrittura [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Specifică il valore massimo reale sull'asse. Richiamare prima il metodo IChart.ValidateChartLayout() per ottenere il valore reale.

**Restituisce:**
double
### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Specifică il valore minimo reale sull'asse. Richiamare prima il metodo IChart.ValidateChartLayout() per ottenere il valore reale.

**Restituisce:**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Specifică l'unità principale reale dell'asse. Richiamare prima il metodo IChart.ValidateChartLayout() per ottenere il valore reale.

**Restituisce:**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Specifică l'unità secondaria reale dell'asse. Richiamare prima il metodo IChart.ValidateChartLayout() per ottenere il valore reale.

**Restituisce:**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Specifică la scala dell'unità principale reale dell'asse. Richiamare prima il metodo IChart.ValidateChartLayout() per ottenere il valore reale.

**Restituisce:**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Specifică la scala dell'unità secondaria reale dell'asse. Richiamare prima il metodo IChart.ValidateChartLayout() per ottenere il valore reale.

**Restituisce:**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Indica se il valore massimo è assegnato automaticamente. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Indica se il valore massimo è assegnato automaticamente. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Rappresenta il valore massimo sull'asse dei valori. Lettura/Scrittura double.

**Restituisce:**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Rappresenta il valore massimo sull'asse dei valori. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Rappresenta le unità secondarie per l'asse della data o dei valori. Lettura/Scrittura double.

**Restituisce:**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Rappresenta le unità secondarie per l'asse della data o dei valori. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Indica se l'unità secondaria dell'asse è assegnata automaticamente. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Indica se l'unità secondaria dell'asse è assegnata automaticamente. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Rappresenta le unità principali per l'asse della data o dei valori. Lettura/Scrittura double.

**Restituisce:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Rappresenta le unità principali per l'asse della data o dei valori. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Indica se l'unità principale dell'asse è assegnata automaticamente. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Indica se l'unità principale dell'asse è assegnata automaticamente. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Indica se il valore minimo è assegnato automaticamente. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Indica se il valore minimo è assegnato automaticamente. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Rappresenta il valore minimo sull'asse dei valori. Lettura/Scrittura double.

**Restituisce:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Rappresenta il valore minimo sull'asse dei valori. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Rappresenta se il tipo di scala dell'asse dei valori è logaritmico o meno. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Rappresenta se il tipo di scala dell'asse dei valori è logaritmico o meno. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Rappresenta la base logaritmica. Il valore predefinito è 10. Lettura/Scrittura double.

**Restituisce:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Rappresenta la base logaritmica. Il valore predefinito è 10. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Rappresenta se l'asse è visibile. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Rappresenta se l'asse è visibile. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Rappresenta il tipo di segno di spunta principale per l'asse specificato. Lettura/Scrittura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Restituisce:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Rappresenta il tipo di segno di spunta principale per l'asse specificato. Lettura/Scrittura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Rappresenta il tipo di segno di spunta secondario per l'asse specificato. Lettura/Scrittura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Restituisce:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Rappresenta il tipo di segno di spunta secondario per l'asse specificato. Lettura/Scrittura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Rappresenta la posizione delle etichette dei segni di spunta sull'asse specificato. Lettura/Scrittura [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Restituisce:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Rappresenta la posizione delle etichette dei segni di spunta sull'asse specificato. Lettura/Scrittura [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Rappresenta la scala dell'unità principale per l'asse della data. Lettura/Scrittura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Restituisce:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Rappresenta la scala dell'unità principale per l'asse della data. Lettura/Scrittura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Rappresenta la scala dell'unità principale per l'asse della data. Lettura/Scrittura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Restituisce:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Rappresenta la scala dell'unità principale per l'asse della data. Lettura/Scrittura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Specifică l'unità di tempo più piccola rappresentata sull'asse della data. Lettura/Scrittura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Restituisce:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Specifică l'unità di tempo più piccola rappresentata sull'asse della data. Lettura/Scrittura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Rappresenta il formato delle linee della griglia secondarie su un asse del grafico. Solo lettura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Restituisce:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Rappresenta il formato delle linee della griglia principali su un asse del grafico. Solo lettura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Restituisce:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Rappresenta se le linee della griglia secondarie sono visualizzate. Solo lettura boolean.

**Restituisce:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Rappresenta se le linee della griglia principali sono visualizzate. Solo lettura boolean.

**Restituisce:**
boolean
### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Rappresenta il formato dell'asse. Solo lettura [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Restituisce:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Ottiene il titolo dell'asse. Solo lettura [IChartTitle](../../com.aspose.slides/icharttitle).

**Restituisce:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Rappresenta il CrossType sull'asse specificato dove l'altro asse lo attraversa. Lettura/Scrittura [CrossesType](../../com.aspose.slides/crossestype).

**Restituisce:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Rappresenta il CrossType sull'asse specificato dove l'altro asse lo attraversa. Lettura/Scrittura [CrossesType](../../com.aspose.slides/crossestype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Rappresenta la posizione dell'asse. Lettura/Scrittura [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Restituisce:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Rappresenta la posizione dell'asse. Lettura/Scrittura [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Determina se un asse ha un titolo visibile. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Determina se un asse ha un titolo visibile. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Rappresenta la stringa di formato per le etichette dell'asse. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Rappresenta la stringa di formato per le etichette dell'asse. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Indica se il formato è collegato ai dati di origine. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Indica se il formato è collegato ai dati di origine. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Rappresenta l'angolo di rotazione delle etichette di spunta Lettura/Scrittura float.

**Restituisce:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Rappresenta l'angolo di rotazione delle etichette di spunta Lettura/Scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Specifică quante etichette di spunta saltare tra le etichette disegnate. Lettura/Scrittura long.

**Restituisce:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Specifică quante etichette di spunta saltare tra le etichette disegnate. Lettura/Scrittura long.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Specifică il valore di spaziatura automatico delle etichette di spunta. Se false: usare la proprietà TickLabelSpacing. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Specifică il valore di spaziatura automatico delle etichette di spunta. Se false: usare la proprietà TickLabelSpacing. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Specifică quante spunte devono essere saltate prima che la successiva venga disegnata. Applicato all'asse di categoria o di serie. Lettura/Scrittura int.

**Restituisce:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Specifică quante spunte devono essere saltate prima che la successiva venga disegnata. Applicato all'asse di categoria o di serie. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Specifică il valore di spaziatura automatico delle spunte. Se false: usare la proprietà TickMarksSpacing. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Specifică il valore di spaziatura automatico delle spunte. Se false: usare la proprietà TickMarksSpacing. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Specifică la distanza delle etichette dall'asse. Applicato all'asse di categoria o di data. Il valore deve essere compreso tra 0% e 1000%. Lettura/Scrittura int.

**Restituisce:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Specifică la distanza delle etichette dall'asse. Applicato all'asse di categoria o di data. Il valore deve essere compreso tra 0% e 1000%. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Specifică il tipo di asse della categoria. Lettura/Scrittura [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Restituisce:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Specifică il tipo di asse della categoria. Lettura/Scrittura [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Imposta la proprietà IAxis.CategoryAxisType con un valore determinato automaticamente in base ai dati dell'asse.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Rappresenta il tipo di aggregazione dell'asse della categoria (binning). Applicato alla categoria. Utilizzato solo con serie Histogram o HistogramPareto.

**Restituisce:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Rappresenta il tipo di aggregazione dell'asse della categoria (binning). Applicato alla categoria. Utilizzato solo con serie Histogram o HistogramPareto.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Specifică la larghezza del bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByBinWidth. Applicato agli assi della categoria. Utilizzato solo con serie Histogram o HistogramPareto.

**Restituisce:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Specifică la larghezza del bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByBinWidth. Applicato agli assi della categoria. Utilizzato solo con serie Histogram o HistogramPareto.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Specifică il numero di bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByNumberOfBins. Applicato agli assi della categoria. Utilizzato solo con serie Histogram o HistogramPareto.

**Restituisce:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Specifică il numero di bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByNumberOfBins. Applicato agli assi della categoria. Utilizzato solo con serie Histogram o HistogramPareto.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Specifică se è applicato il bin di overflow. Usa IsAutomaticOverflowBin e OverflowBin per regolare il valore del bin di overflow.

**Restituisce:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Specifică se è applicato il bin di overflow. Usa IsAutomaticOverflowBin e OverflowBin per regolare il valore del bin di overflow.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Specifică il valore automatico del bin di overflow. Se false: usare la proprietà OverflowBin.

**Restituisce:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Specifică il valore automatico del bin di overflow. Se false: usare la proprietà OverflowBin.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Specifică il valore personalizzato del bin di overflow. Applicato quando la proprietà IsAutomaticOverflowBin è impostata su false e la proprietà IsOverflowBin è true.

**Restituisce:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Specifică il valore personalizzato del bin di overflow. Applicato quando la proprietà IsAutomaticOverflowBin è impostata su false e la proprietà IsOverflowBin è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Specifică se è applicato il bin di underflow. Usa IsAutomaticUnderflowBin e UnderflowBin per regolare il valore del bin di underflow.

**Restituisce:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Specifică se è applicato il bin di underflow. Usa IsAutomaticUnderflowBin e UnderflowBin per regolare il valore del bin di underflow.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Specifică il valore automatico del bin di underflow. Se false: usare la proprietà UnderflowBin.

**Restituisce:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Specifică il valore automatico del bin di underflow. Se false: usare la proprietà UnderflowBin.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Specifică il valore personalizzato del bin di underflow. Applicato quando la proprietà IsAutomaticUnderflowBin è impostata su false e la proprietà IsUnderflowBin è true.

**Restituisce:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Specifică il valore personalizzato del bin di underflow. Applicato quando la proprietà IsAutomaticUnderflowBin è impostata su false e la proprietà IsUnderflowBin è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |