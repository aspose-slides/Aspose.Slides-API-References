---
title: Axis
second_title: Riferimento API Java per Aspose.Slides per Android
description: Incapsula l'oggetto che rappresenta l'asse di un grafico.
type: docs
url: /it/com.aspose.slides/axis/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Incapsula l'oggetto che rappresenta l'asse di un grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getChart()](#getChart--) | Restituisce il grafico principale. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Rappresenta se l'asse dei valori attraversa l'asse delle categorie tra le categorie. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Rappresenta se l'asse dei valori attraversa l'asse delle categorie tra le categorie. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Specifica il tipo dell'asse delle categorie. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Specifica il tipo dell'asse delle categorie. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Imposta la proprietà IAxis.CategoryAxisType con un valore determinato automaticamente in base ai dati dell'asse. |
| [getCrossAt()](#getCrossAt--) | Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. |
| [setCrossAt(float value)](#setCrossAt-float-) | Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. |
| [getDisplayUnit()](#getDisplayUnit--) | Specifica il valore di scala delle unità di visualizzazione per l'asse dei valori. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Specifica il valore di scala delle unità di visualizzazione per l'asse dei valori. |
| [getActualMaxValue()](#getActualMaxValue--) | Specifica il valore massimo effettivo sull'asse. |
| [getActualMinValue()](#getActualMinValue--) | Specifica il valore minimo effettivo sull'asse. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Specifica l'unità principale effettiva dell'asse. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Specifica l'unità minore effettiva dell'asse. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Specifica la scala dell'unità principale effettiva dell'asse. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Specifica la scala dell'unità minore effettiva dell'asse. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Indica se il valore massimo è assegnato automaticamente. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Indica se il valore massimo è assegnato automaticamente. |
| [getMaxValue()](#getMaxValue--) | Rappresenta il valore massimo sull'asse dei valori. |
| [setMaxValue(double value)](#setMaxValue-double-) | Rappresenta il valore massimo sull'asse dei valori. |
| [getMinorUnit()](#getMinorUnit--) | Rappresenta le unità minori per l'asse delle date o dei valori. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Rappresenta le unità minori per l'asse delle date o dei valori. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indica se l'unità minore dell'asse è assegnata automaticamente. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indica se l'unità minore dell'asse è assegnata automaticamente. |
| [getMajorUnit()](#getMajorUnit--) | Rappresenta le unità principali per l'asse delle date o dei valori. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Rappresenta le unità principali per l'asse delle date o dei valori. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Indica se l'unità principale dell'asse è assegnata automaticamente. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Indica se l'unità principale dell'asse è assegnata automaticamente. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Indica se il valore minimo è assegnato automaticamente. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Indica se il valore minimo è assegnato automaticamente. |
| [getMinValue()](#getMinValue--) | Rappresenta il valore minimo sull'asse dei valori. |
| [setMinValue(double value)](#setMinValue-double-) | Rappresenta il valore minimo sull'asse dei valori. |
| [isLogarithmic()](#isLogarithmic--) | Rappresenta se il tipo di scala dell'asse dei valori è logaritmico o no. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Rappresenta se il tipo di scala dell'asse dei valori è logaritmico o no. |
| [getLogBase()](#getLogBase--) | Rappresenta la base logaritmica. |
| [setLogBase(double value)](#setLogBase-double-) | Rappresenta la base logaritmica. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo. |
| [isVisible()](#isVisible--) | Rappresenta se l'asse è visibile. |
| [setVisible(boolean value)](#setVisible-boolean-) | Rappresenta se l'asse è visibile. |
| [getMajorTickMark()](#getMajorTickMark--) | Rappresenta il tipo di segno di graduazione principale per l'asse specificato. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Rappresenta il tipo di segno di graduazione principale per l'asse specificato. |
| [getMinorTickMark()](#getMinorTickMark--) | Rappresenta il tipo di segno di graduazione minore per l'asse specificato. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Rappresenta il tipo di segno di graduazione minore per l'asse specificato. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Rappresenta la posizione delle etichette delle tacche sull'asse specificato. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Rappresenta la posizione delle etichette delle tacche sull'asse specificato. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Rappresenta la scala dell'unità principale per l'asse delle date. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Rappresenta la scala dell'unità principale per l'asse delle date. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Rappresenta la scala dell'unità principale per l'asse delle date. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Rappresenta la scala dell'unità principale per l'asse delle date. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Specifica l'unità di tempo più piccola rappresentata sull'asse delle date. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Specifica l'unità di tempo più piccola rappresentata sull'asse delle date. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Rappresenta il formato delle linee della griglia minore su un asse del grafico. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Rappresenta il formato delle linee della griglia maggiore su un asse del grafico. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Per nascondere la linea della griglia minore impostare MinorGridLinesFormat.Line.FillFormat.FillType su FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Per nascondere la linea della griglia maggiore impostare MajorGridLinesFormat.Line.FillFormat.FillType su FillType.NoFill. |
| [getFormat()](#getFormat--) | Rappresenta il formato dell'asse. |
| [getTextFormat()](#getTextFormat--) | Rappresenta il formato del testo. |
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
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Rappresenta l'angolo di rotazione delle etichette delle tacche. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Rappresenta l'angolo di rotazione delle etichette delle tacche. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Specifica quante etichette di tacche saltare tra le etichette disegnate. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Specifica quante etichette di tacche saltare tra le etichette disegnate. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Specifica il valore di spaziatura automatico delle etichette di tacche. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Specifica il valore di spaziatura automatico delle etichette di tacche. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Specifica quante tacche devono essere saltate prima di disegnarne la successiva. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Specifica quante tacche devono essere saltate prima di disegnarne la successiva. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Specifica il valore di spaziatura automatico delle tacche. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Specifica il valore di spaziatura automatico delle tacche. |
| [getLabelOffset()](#getLabelOffset--) | Specifica la distanza delle etichette dall'asse. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Specifica la distanza delle etichette dall'asse. |
| [getAggregationType()](#getAggregationType--) | Rappresenta il tipo di aggregazione dell'asse delle categorie (binning). |
| [setAggregationType(int value)](#setAggregationType-int-) | Rappresenta il tipo di aggregazione dell'asse delle categorie (binning). |
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
| [getSlide()](#getSlide--) | Restituisce la diapositiva principale di un FillFormat. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione principale di un FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```


Restituisce il grafico principale. Solo lettura [IChart](../../com.aspose.slides/ichart).

**Restituisce:**
[IChart](../../com.aspose.slides/ichart)
### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```


Rappresenta se l'asse dei valori attraversa l'asse delle categorie tra le categorie. Questa proprietà si applica solo agli assi delle categorie e non si applica ai grafici 3-D. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```


Rappresenta se l'asse dei valori attraversa l'asse delle categorie tra le categorie. Questa proprietà si applica solo agli assi delle categorie e non si applica ai grafici 3-D. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```


Specifică il tipo dell'asse delle categorie. Lettura/Scrittura [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Restituisce:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```


Specifică il tipo dell'asse delle categorie. Lettura/Scrittura [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```


Imposta la proprietà IAxis.CategoryAxisType con un valore determinato automaticamente in base ai dati dell'asse.
### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```


Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. Lettura/Scrittura float.

**Restituisce:**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```


Rappresenta il punto sull'asse dove l'asse perpendicolare lo attraversa. Lettura/Scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```


Specifică il valore di scala delle unità di visualizzazione per l'asse dei valori. Lettura/Scrittura [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Restituisce:**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```


Specifică il valore di scala delle unità di visualizzazione per l'asse dei valori. Lettura/Scrittura [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```


Specifică il valore massimo effettivo sull'asse. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere il valore effettivo.

**Restituisce:**
double
### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```


Specifică il valore minimo effettivo sull'asse. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere il valore effettivo.

**Restituisce:**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```


Specifică l'unità principale effettiva dell'asse. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere il valore effettivo.

**Restituisce:**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```


Specifică l'unità minore effettiva dell'asse. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere il valore effettivo.

**Restituisce:**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```


Specifică la scala dell'unità principale effettiva dell'asse. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere il valore effettivo.

**Restituisce:**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```


Specifică la scala dell'unità minore effettiva dell'asse. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere il valore effettivo.

**Restituisce:**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```


Indica se il valore massimo è assegnato automaticamente. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```


Indica se il valore massimo è assegnato automaticamente. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```


Rappresenta il valore massimo sull'asse dei valori. Lettura/Scrittura double.

**Restituisce:**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```


Rappresenta il valore massimo sull'asse dei valori. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```


Rappresenta le unità minori per l'asse delle date o dei valori. Lettura/Scrittura double.

**Restituisce:**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```


Rappresenta le unità minori per l'asse delle date o dei valori. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```


Indica se l'unità minore dell'asse è assegnata automaticamente. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```


Indica se l'unità minore dell'asse è assegnata automaticamente. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```


Rappresenta le unità principali per l'asse delle date o dei valori. Lettura/Scrittura double.

**Restituisce:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```


Rappresenta le unità principali per l'asse delle date o dei valori. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```


Indica se l'unità principale dell'asse è assegnata automaticamente. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```


Indica se l'unità principale dell'asse è assegnata automaticamente. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```


Indica se il valore minimo è assegnato automaticamente. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```


Indica se il valore minimo è assegnato automaticamente. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```


Rappresenta il valore minimo sull'asse dei valori. Lettura/Scrittura double.

**Restituisce:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```


Rappresenta il valore minimo sull'asse dei valori. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```


Rappresenta se il tipo di scala dell'asse dei valori è logaritmico o no. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```


Rappresenta se il tipo di scala dell'asse dei valori è logaritmico o no. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```


Rappresenta la base logaritmica. Il valore predefinito è 10. Lettura/Scrittura double.

**Restituisce:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```


Rappresenta la base logaritmica. Il valore predefinito è 10. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```


Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```


Rappresenta se MS PowerPoint traccia i punti dati dall'ultimo al primo. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Rappresenta se l'asse è visibile. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Rappresenta se l'asse è visibile. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```


Rappresenta il tipo di segno di graduazione principale per l'asse specificato. Lettura/Scrittura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Restituisce:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```


Rappresenta il tipo di segno di graduazione principale per l'asse specificato. Lettura/Scrittura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```


Rappresenta il tipo di segno di graduazione minore per l'asse specificato. Lettura/Scrittura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Restituisce:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```


Rappresenta il tipo di segno di graduazione minore per l'asse specificato. Lettura/Scrittura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```


Rappresenta la posizione delle etichette delle tacche sull'asse specificato. Lettura/Scrittura [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Restituisce:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```


Rappresenta la posizione delle etichette delle tacche sull'asse specificato. Lettura/Scrittura [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```


Rappresenta la scala dell'unità principale per l'asse delle date. Lettura/Scrittura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Restituisce:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```


Rappresenta la scala dell'unità principale per l'asse delle date. Lettura/Scrittura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```


Rappresenta la scala dell'unità principale per l'asse delle date. Lettura/Scrittura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Restituisce:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```


Rappresenta la scala dell'unità principale per l'asse delle date. Lettura/Scrittura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```


Specifică l'unità di tempo più piccola rappresentata sull'asse delle date. Lettura/Scrittura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Restituisce:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```


Specifică l'unità di tempo più piccola rappresentata sull'asse delle date. Lettura/Scrittura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


Rappresenta il formato delle linee della griglia minore su un asse del grafico. Solo lettura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Restituisce:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```


Rappresenta il formato delle linee della griglia maggiore su un asse del grafico. Solo lettura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Restituisce:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```


Per nascondere la linea della griglia minore impostare MinorGridLinesFormat.Line.FillFormat.FillType su FillType.NoFill. Solo lettura boolean.

**Restituisce:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```


Per nascondere la linea della griglia maggiore impostare MajorGridLinesFormat.Line.FillFormat.FillType su FillType.NoFill. Solo lettura boolean.

**Restituisce:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```


Rappresenta il formato dell'asse. Solo lettura [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Restituisce:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Rappresenta il formato del testo. Solo lettura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Restituisce:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```


Ottiene il titolo dell'asse. Solo lettura [IChartTitle](../../com.aspose.slides/icharttitle).

**Restituisce:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```


Rappresenta il CrossType sull'asse specificato dove l'altro asse lo attraversa. Lettura/Scrittura [CrossesType](../../com.aspose.slides/crossestype).

**Restituisce:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```


Rappresenta il CrossType sull'asse specificato dove l'altro asse lo attraversa. Lettura/Scrittura [CrossesType](../../com.aspose.slides/crossestype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Rappresenta la posizione dell'asse. Lettura/Scrittura [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Restituisce:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Rappresenta la posizione dell'asse. Lettura/Scrittura [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


Determina se un asse ha un titolo visibile. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


Determina se un asse ha un titolo visibile. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


Rappresenta la stringa di formato per le etichette dell'asse. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


Rappresenta la stringa di formato per le etichette dell'asse. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


Indica se il formato è collegato ai dati di origine. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


Indica se il formato è collegato ai dati di origine. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```


Rappresenta l'angolo di rotazione delle etichette delle tacche. Lettura/Scrittura float.

**Restituisce:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```


Rappresenta l'angolo di rotazione delle etichette delle tacche. Lettura/Scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```


Specifică quante etichette di tacche saltare tra le etichette disegnate. Applicato all'asse di categoria o di serie. Lettura/Scrittura long.

**Restituisce:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```


Specifică quante etichette di tacche saltare tra le etichette disegnate. Applicato all'asse di categoria o di serie. Lettura/Scrittura long.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |
### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```


Specifică il valore di spaziatura automatico delle etichette di tacche. Se false: usare la proprietà TickLabelSpacing. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```


Specifică il valore di spaziatura automatico delle etichette di tacche. Se false: usare la proprietà TickLabelSpacing. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```


Specifică quante tacche devono essere saltate prima di disegnarne la successiva. Applicato all'asse di categoria o di serie. Lettura/Scrittura int.

**Restituisce:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```


Specifică quante tacche devono essere saltate prima di disegnarne la successiva. Applicato all'asse di categoria o di serie. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |
### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```


Specifică il valore di spaziatura automatico delle tacche. Se false: usare la proprietà TickMarksSpacing. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```


Specifică il valore di spaziatura automatico delle tacche. Se false: usare la proprietà TickMarksSpacing. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```


Specifică la distanza delle etichette dall'asse. Applicato all'asse di categoria o di data. Il valore deve essere compreso tra 0% e 1000%. Lettura/Scrittura int.

**Restituisce:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```


Specifică la distanza delle etichette dall'asse. Applicato all'asse di categoria o di data. Il valore deve essere compreso tra 0% e 1000%. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```


Rappresenta il tipo di aggregazione dell'asse delle categorie (binning). Applicato alla categoria. Utilizzato solo con serie Histogram o HistogramPareto.

**Restituisce:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```


Rappresenta il tipo di aggregazione dell'asse delle categorie (binning). Applicato alla categoria. Utilizzato solo con serie Histogram o HistogramPareto.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```


Specifică la larghezza del bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByBinWidth. Applicato agli assi di categoria. Utilizzato solo con serie Histogram o HistogramPareto.

**Restituisce:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```


Specifică la larghezza del bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByBinWidth. Applicato agli assi di categoria. Utilizzato solo con serie Histogram o HistogramPareto.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```


Specifică il numero di bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByNumberOfBins. Applicato agli assi di categoria. Utilizzato solo con serie Histogram o HistogramPareto.

**Restituisce:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```


Specifică il numero di bin quando il valore della proprietà AggregationType è impostato su AxisAggregationType.ByNumberOfBins. Applicato agli assi di categoria. Utilizzato solo con serie Histogram o HistogramPareto.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |
### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```


Specifică se è applicato il bin di overflow. Usare IsAutomaticOverflowBin e OverflowBin per regolare il valore del bin di overflow.

**Restituisce:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```


Specifică se è applicato il bin di overflow. Usare IsAutomaticOverflowBin e OverflowBin per regolare il valore del bin di overflow.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```


Specifică il valore automatico del bin di overflow. Se false: usare la proprietà OverflowBin.

**Restituisce:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```


Specifică il valore automatico del bin di overflow. Se false: usare la proprietà OverflowBin.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```


Specifică il valore personalizzato del bin di overflow. Applicato quando IsAutomaticOverflowBin è impostato su false e IsOverflowBin è vero.

**Restituisce:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```


Specifică il valore personalizzato del bin di overflow. Applicato quando IsAutomaticOverflowBin è impostato su false e IsOverflowBin è vero.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```


Specifică se è applicato il bin di underflow. Usare IsAutomaticUnderflowBin e UnderflowBin per regolare il valore del bin di underflow.

**Restituisce:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```


Specifică se è applicato il bin di underflow. Usare IsAutomaticUnderflowBin e UnderflowBin per regolare il valore del bin di underflow.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```


Specifică il valore automatico del bin di underflow. Se false: usare la proprietà UnderflowBin.

**Restituisce:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```


Specifică il valore automatico del bin di underflow. Se false: usare la proprietà UnderflowBin.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```


Specifică il valore personalizzato del bin di underflow. Applicato quando IsAutomaticUnderflowBin è impostato su false e IsUnderflowBin è vero.

**Restituisce:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```


Specifică il valore personalizzato del bin di underflow. Applicato quando IsAutomaticUnderflowBin è impostato su false e IsUnderflowBin è vero.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Restituisce la diapositiva principale di un FillFormat. Solo lettura [BaseSlide](../../com.aspose.slides/baseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
The    
```


Restituisce la presentazione principale di un FillFormat. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)