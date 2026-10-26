---
title: IChartSeries
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una serie di grafico.
type: docs
url: /it/com.aspose.slides/ichartseries/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Rappresenta una serie di grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getExplosion()](#getExplosion--) | La distanza di una fetta di torta aperta dal centro del grafico a torta è espressa in percentuale del diametro della torta. |
| [setExplosion(int value)](#setExplosion-int-) | La distanza di una fetta di torta aperta dal centro del grafico a torta è espressa in percentuale del diametro della torta. |
| [getSmooth()](#getSmooth--) | Rappresenta l'ammorbidimento della curva. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Rappresenta l'ammorbidimento della curva. |
| [getMarker()](#getMarker--) | Restituisce il marcatore della serie. |
| [getBar3DShape()](#getBar3DShape--) | Specifica la forma di una serie di un grafico a barre 3-D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Specifica la forma di una serie di un grafico a barre 3-D. |
| [getName()](#getName--) | Restituisce il nome della serie. |
| [getDataPoints()](#getDataPoints--) | Restituisce la collezione di punti dati di questa serie. |
| [getType()](#getType--) | Restituisce un tipo di questa serie. |
| [setType(int value)](#setType-int-) | Restituisce un tipo di questa serie. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Restituisce il gruppo di serie padre. |
| [getFormat()](#getFormat--) | Restituisce il formato di una serie. |
| [getOrder()](#getOrder--) | Restituisce l'ordine di una serie. |
| [setOrder(int value)](#setOrder-int-) | Restituisce l'ordine di una serie. |
| [getLabels()](#getLabels--) | Restituisce le Etichette di una serie. |
| [getTrendLines()](#getTrendLines--) | Collezione di linee di tendenza della serie Solo lettura [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Rappresenta le barre di errore della serie con direzione X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Rappresenta le barre di errore della serie con direzione Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indica se questa serie è tracciata su un secondo asse dei valori. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indica se questa serie è tracciata su un secondo asse dei valori. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Restituisce o imposta il formato numerico per i valori della serie. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Restituisce o imposta il formato numerico per i valori della serie. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Restituisce o imposta il formato numerico per i valori x della serie. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Restituisce o imposta il formato numerico per i valori x della serie. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Restituisce o imposta il formato numerico per i valori y della serie. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Restituisce o imposta il formato numerico per i valori y della serie. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Restituisce o imposta il formato numerico per le dimensioni delle bolle della serie. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Restituisce o imposta il formato numerico per le dimensioni delle bolle della serie. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specifica che la serie a barre, colonne o bolle deve invertire i colori se il valore è negativo. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specifica che la serie a barre, colonne o bolle deve invertire i colori se il valore è negativo. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Specifica il colore solido invertito per la serie. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Rappresenta la voce della legenda correlata a questa serie Solo lettura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Restituisce un colore automatico della serie basato sull'indice della serie e sullo stile del grafico. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Rappresenta i punti interni. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Rappresenta i punti interni. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Rappresenta i punti anomali. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Rappresenta i punti anomali. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Rappresenta i marcatori della media. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Rappresenta i marcatori della media. |
| [getShowMeanLine()](#getShowMeanLine--) | Rappresenta i marcatori della media. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Rappresenta i marcatori della media. |
| [getQuartileMethod()](#getQuartileMethod--) | Rappresenta il metodo del quartile. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Rappresenta il metodo del quartile. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Rappresenta le linee di collegamento. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Rappresenta le linee di collegamento. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Rappresenta il layout delle etichette della categoria padre. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Rappresenta il layout delle etichette della categoria padre. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percento della dimensione predefinita). |
| [hasUpDownBars()](#hasUpDownBars--) | Determina se il grafico a linee o a barre ha bande su/giù. |
| [getGapWidth()](#getGapWidth--) | Specifica lo spazio tra i gruppi di barre o colonne, in percentuale della larghezza della barra o colonna. |
| [getGapDepth()](#getGapDepth--) | Restituisce o imposta la distanza, in percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. |
| [isColorVaried()](#isColorVaried--) | Specifica che ogni marcatore di dati nella serie ha un colore diverso. |
| [hasSeriesLines()](#hasSeriesLines--) | Determina se esistono linee di serie per questa serie e le serie correlate. |
| [getOverlap()](#getOverlap--) | Specifica quanto le barre e le colonne si sovrappongono nei grafici 2-D, in percentuale (da -100% a 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specifica la dimensione della seconda torta o barra di un grafico torta-in-torta o barra-in-torta, in percentuale della dimensione della prima torta (può essere tra 5 e 200 percento). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specifica un valore da utilizzare per determinare quali punti dati sono nella seconda torta o barra in un grafico torta-in-torta o barra-in-torta. |
| [getPieSplitBy()](#getPieSplitBy--) | Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico torta-in-torta o barra-in-torta. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specifica la dimensione del foro in un grafico a ciambella (può essere tra 10 e 90 percento della dimensione dell'area del grafico). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Specifica l'angolo della prima fetta di torta o ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Le informazioni di divisione personalizzate per un grafico torta-in-torta o barra-in-torta con divisione personalizzata. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specifica come i valori di dimensione delle bolle sono rappresentati nel grafico a bolle. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

La distanza di una fetta di torta aperta dal centro del grafico a torta è espressa in percentuale del diametro della torta. Lettura/scrittura int.

**Restituisce:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

La distanza di una fetta di torta aperta dal centro del grafico a torta è espressa in percentuale del diametro della torta. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Rappresenta l'ammorbidimento della curva. True se l'ammorbidimento della curva è attivo per il grafico a linee o scatter. Si applica solo ai grafici a linee e scatter connessi da linee. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Rappresenta l'ammorbidimento della curva. True se l'ammorbidimento della curva è attivo per il grafico a linee o scatter. Si applica solo ai grafici a linee e scatter connessi da linee. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Restituisce il marcatore della serie. Solo lettura [IMarker](../../com.aspose.slides/imarker).

**Restituisce:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Specifica la forma di una serie di un grafico a barre 3-D. La modifica di questo valore può causare la modifica automatica del Tipo della serie. Lettura/scrittura [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Restituisce:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Specifica la forma di una serie di un grafico a barre 3-D. La modifica di questo valore può causare la modifica automatica del Tipo della serie. Lettura/scrittura [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Restituisce il nome della serie. Solo lettura [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Restituisce:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Restituisce la collezione di punti dati di questa serie. Solo lettura [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Restituisce:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

Restituisce un tipo di questa serie. Lettura/scrittura [ChartType](../../com.aspose.slides/charttype).

**Restituisce:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Restituisce un tipo di questa serie. Lettura/scrittura [ChartType](../../com.aspose.slides/charttype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Restituisce il gruppo di serie padre. Solo lettura [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Restituisce:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Restituisce il formato di una serie. Solo lettura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Restituisce l'ordine di una serie. Lettura/scrittura int.

**Restituisce:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Restituisce l'ordine di una serie. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Restituisce le Etichette di una serie. Solo lettura [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Restituisce:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Collezione di linee di tendenza della serie Solo lettura [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Restituisce:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Rappresenta le barre di errore della serie con direzione X. Solo lettura [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Le barre di errore con direzione X sono disponibili per le serie di tipo area, bar, scatter e bubble. Per tutti gli altri tipi di grafico questa proprietà restituisce null (incluse le grafici 3D). In caso di valori personalizzati usare la collezione DataPoints per specificare il valore (con la proprietà ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Restituisce:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Rappresenta le barre di errore della serie con direzione Y. Solo lettura [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Le barre di errore con direzione Y sono disponibili per le serie di tipo area, bar, line, scatter e bubble. Per tutti gli altri tipi di grafico questa proprietà restituisce null (incluse le grafici 3D). In caso di valori personalizzati usare la collezione DataPoints per specificare il valore (con la proprietà ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Restituisce:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Indica se questa serie è tracciata su un secondo asse dei valori. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Indica se questa serie è tracciata su un secondo asse dei valori. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Restituisce o imposta il formato numerico per i valori della serie. Lettura/scrittura String.

**Restituisce:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Restituisce o imposta il formato numerico per i valori della serie. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Restituisce o imposta il formato numerico per i valori x della serie. Lettura/scrittura String.

**Restituisce:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Restituisce o imposta il formato numerico per i valori x della serie. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Restituisce o imposta il formato numerico per i valori y della serie. Lettura/scrittura String.

**Restituisce:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Restituisce o imposta il formato numerico per i valori y della serie. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Restituisce o imposta il formato numerico per le dimensioni delle bolle della serie. Lettura/scrittura String.

**Restituisce:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Restituisce o imposta il formato numerico per le dimensioni delle bolle della serie. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Specifica che la serie a barre, colonne o bolle deve invertire i colori se il valore è negativo. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Specifica che la serie a barre, colonne o bolle deve invertire i colori se il valore è negativo. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Specifica il colore solido invertito per la serie. Per applicare l'impostazione del colore impostare FillType del formato serie su FillType.Solid. Lettura/scrittura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Rappresenta la voce della legenda correlata a questa serie Solo lettura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Restituisce:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Restituisce un colore automatico della serie basato sull’indice della serie e sullo stile del grafico. Questo colore è usato per impostazione predefinita se FillType equals NotDefined.

**Restituisce:**
java.awt.Color - Colore automatico della serie java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Rappresenta i punti interni. True se i punti interni sono mostrati nel grafico BoxAndWhisker. Si applica solo ai grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Rappresenta i punti interni. True se i punti interni sono mostrati nel grafico BoxAndWhisker. Si applica solo ai grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Rappresenta i punti anomali. True se i punti anomali sono mostrati nel grafico BoxAndWhisker. Si applica solo ai grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Rappresenta i punti anomali. True se i punti anomali sono mostrati nel grafico BoxAndWhisker. Si applica solo ai grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Rappresenta i marcatori della media. True se i marcatori della media sono mostrati nel grafico BoxAndWhisker. Si applica solo ai grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Rappresenta i marcatori della media. True se i marcatori della media sono mostrati nel grafico BoxAndWhisker. Si applica solo ai grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Rappresenta i marcatori della media. True se la linea media è mostrata nel grafico BoxAndWhisker. Si applica solo ai grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Rappresenta i marcatori della media. True se la linea media è mostrata nel grafico BoxAndWhisker. Si applica solo ai grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Rappresenta il metodo quartile. Si applica solo ai grafici BoxAndWhisker.

**Restituisce:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Rappresenta il metodo quartile. Si applica solo ai grafici BoxAndWhisker.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Rappresenta le linee di collegamento. Si applica solo ai grafici Waterfall.

**Restituisce:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Rappresenta le linee di collegamento. Si applica solo ai grafici Waterfall.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Rappresenta il layout delle etichette delle categorie padre. Si applica solo ai grafici Treemap.

**Restituisce:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Rappresenta il layout delle etichette delle categorie padre. Si applica solo ai grafici Treemap.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percenti della dimensione predefinita). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è una proiezione della proprietà del gruppo appropriato. Pertanto questa proprietà è sola lettura. Utilizzare la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Utilizzare la proprietà ParentSeriesGroup.BubbleSizeScale Lettura/Scrittura per modificare il valore.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.BubbleSizeScale.

**Restituisce:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Determina se il grafico Line- o Stock-chart ha barre up/down. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è una proiezione della proprietà del gruppo appropriato. Pertanto questa proprietà è sola lettura. Utilizzare la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Utilizzare la proprietà ParentSeriesGroup.UpDownBars.HasUpDownBars Lettura/Scrittura per modificare il valore. Utilizzare la proprietà ParentSeriesGroup.UpDownBars per formattare le barre up/down. Sola lettura boolean.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Restituisce:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Specifica lo spazio tra i raggruppamenti di barre o colonne, come percentuale della larghezza della barra o della colonna. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è una proiezione della proprietà del gruppo appropriato. Pertanto questa proprietà è sola lettura. Utilizzare la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Utilizzare la proprietà ParentSeriesGroup.GapWidth Lettura/Scrittura per modificare il valore. Sola lettura int.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.GapWidth.

**Restituisce:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è una proiezione della proprietà del gruppo appropriato. Pertanto questa proprietà è sola lettura. Utilizzare la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Utilizzare la proprietà ParentSeriesGroup.GapDepth Lettura/Scrittura per modificare il valore. Sola lettura int.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.GapDepth.

**Restituisce:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Specifica che ogni marcatore dati nella serie ha un colore diverso. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è una proiezione della proprietà del gruppo appropriato. Pertanto questa proprietà è sola lettura. Utilizzare la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Utilizzare la proprietà ParentSeriesGroup.IsColorVaried Lettura/Scrittura per modificare il valore. Sola lettura boolean.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.IsColorVaried.

**Restituisce:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Determina se esistono linee di serie per questa serie e le serie correlate. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è una proiezione della proprietà del gruppo appropriato. Pertanto questa proprietà è sola lettura. Utilizzare la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Utilizzare la proprietà ParentSeriesGroup.HasSeriesLines Lettura/Scrittura per modificare il valore. Utilizzare la proprietà ParentSeriesGroup.SeriesLinesFormat per formattare le linee di serie. Sola lettura boolean.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.HasSeriesLines.

**Restituisce:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Specifică quanto le barre e le colonne si sovrappongono nei grafici 2-D, come percentuale (da -100 % a 100 %). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre. È una proiezione della proprietà appropriata nel gruppo di serie padre, e quindi questa proprietà è sola lettura. Per cambiare il valore, usare la proprietà ParentSeriesGroup.Overlap Lettura/Scrittura. Sola lettura byte.

--------------------

Overlap specifica il grado di sovrapposizione o spaziatura tra barre e colonne come percentuale della loro larghezza:
- -100 %: Spaziatura massima (le barre sono completamente separate).
- 0 %: Le barre sono affiancate senza sovrapposizione né spaziatura.
- 100 %: Sovrapposizione massima (le barre si sovrappongono completamente).

Questa è una proiezione della proprietà ParentSeriesGroup.Overlap.

**Restituisce:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Specifică la dimensione della seconda torta o barra di un grafico pie-of-pie o bar-of-pie, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percenti). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è una proiezione della proprietà del gruppo appropriato. Pertanto questa proprietà è sola lettura. Utilizzare la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Utilizzare la proprietà ParentSeriesGroup.SecondPieSize Lettura/Scrittura per modificare il valore. Sola lettura int.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.SecondPieSize.

**Restituisce:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Specifică un valore che deve essere usato per determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. È usato insieme alla proprietà PieSplitBy. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è una proiezione della proprietà del gruppo appropriato. Pertanto questa proprietà è sola lettura. Utilizzare la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Utilizzare la proprietà ParentSeriesGroup.PieSplitPosition Lettura/Scrittura per modificare il valore. Sola lettura double.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.PieSplitPosition.

**Restituisce:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Specifică come determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è una proiezione della proprietà del gruppo appropriato. Pertanto questa proprietà è sola lettura. Utilizzare la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Utilizzare la proprietà ParentSeriesGroup.PieSplitBy Lettura/Scrittura per modificare il valore. Sola lettura [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Questa è la proiezione della proprietà ParentSeriesGroup.PieSplitBy. 2) Se il valore della proprietà è PieSplitType.Custom, è possibile definire informazioni di split personalizzate con la proprietà ParentSeriesGroup.PieSplitCustomPoints.

**Restituisce:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Specifică la dimensione del foro in un grafico doughnut (può essere tra 10 e 90 percenti della dimensione dell’area del grafico). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è una proiezione della proprietà del gruppo appropriato. Pertanto questa proprietà è sola lettura. Utilizzare la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Utilizzare la proprietà ParentSeriesGroup.DoughnutHoleSize Lettura/Scrittura per modificare il valore. Sola lettura byte.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.DoughnutHoleSize.

**Restituisce:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Specifică l’angolo della prima fetta di torta o doughnut, in gradi (orario dall’alto, da 0 a 360 gradi). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è una proiezione della proprietà del gruppo appropriato. Pertanto questa proprietà è sola lettura. Utilizzare la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Utilizzare la proprietà ParentSeriesGroup.FirstSliceAngle Lettura/Scrittura per modificare il valore. Sola lettura int.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.FirstSliceAngle.

**Restituisce:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Le informazioni di split personalizzate per un grafico pie-of-pie o bar-of-pie con split personalizzato. Contiene i punti dati che devono essere disegnati nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre – è una proiezione della proprietà del gruppo appropriato. Sola lettura [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.PieSplitCustomPoints.

**Restituisce:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
Specifica come i valori della dimensione delle bolle sono rappresentati nel grafico a bolle. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre - è la proiezione della proprietà di gruppo appropriata. Pertanto questa proprietà è di sola lettura. Utilizzare la proprietà ParentSeriesGroup per accedere al gruppo di serie padre. Utilizzare la proprietà di lettura/scrittura ParentSeriesGroup.BubbleSizeRepresentation per modificare il valore.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.BubbleSizeRepresentation.

**Restituisce:**
int