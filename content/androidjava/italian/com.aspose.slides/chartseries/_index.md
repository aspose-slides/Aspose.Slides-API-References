---
title: ChartSeries
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una serie di grafico.
type: docs
url: /it/com.aspose.slides/chartseries/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Rappresenta una serie di grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Restituisce il grafico genitore. |
| [getExplosion()](#getExplosion--) | La distanza di una fetta di torta aperta dal centro del grafico a torta è espressa come percentuale del diametro della torta. |
| [setExplosion(int value)](#setExplosion-int-) | La distanza di una fetta di torta aperta dal centro del grafico a torta è espressa come percentuale del diametro della torta. |
| [getSmooth()](#getSmooth--) | Rappresenta l'ammorbidimento della curva. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Rappresenta l'ammorbidimento della curva. |
| [getName()](#getName--) | Restituisce il nome della serie. |
| [getDataPoints()](#getDataPoints--) | Restituisce la raccolta di punti dati di questa serie. |
| [getType()](#getType--) | Restituisce un tipo di questa serie. |
| [setType(int value)](#setType-int-) | Restituisce un tipo di questa serie. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indica se questa serie è tracciata su un asse secondario. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indica se questa serie è tracciata su un asse secondario. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Restituisce il formato di una serie. |
| [getOrder()](#getOrder--) | Restituisce l'ordine di una serie. |
| [setOrder(int value)](#setOrder-int-) | Restituisce l'ordine di una serie. |
| [getLabels()](#getLabels--) | Restituisce le Labels di una serie. |
| [getTrendLines()](#getTrendLines--) | Raccolta di linee di tendenza della serie. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Rappresenta le ErrorBars della serie con direzione X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Rappresenta le ErrorBars della serie con direzione Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Rappresenta la voce della legenda collegata a questa serie. Solo lettura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Specifica la forma di una serie di un grafico a barre 3-D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Specifica la forma di una serie di un grafico a barre 3-D. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specifica che la serie a barre, colonne o bolle deve invertire i colori se il valore è negativo. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specifica che la serie a barre, colonne o bolle deve invertire i colori se il valore è negativo. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Specifica l'inversione del colore pieno per la serie. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Restituisce un colore automatico della serie basato sull'indice della serie e sullo stile del grafico. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Rappresenta i punti interni. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Rappresenta i punti interni. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Rappresenta i punti anomali. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Rappresenta i punti anomali. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Rappresenta i marcatori della media. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Rappresenta i marcatori della media. |
| [getShowMeanLine()](#getShowMeanLine--) | Rappresenta la linea della media. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Rappresenta la linea della media. |
| [getQuartileMethod()](#getQuartileMethod--) | Rappresenta il metodo quartile. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Rappresenta il metodo quartile. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Rappresenta le linee di collegamento. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Rappresenta le linee di collegamento. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Rappresenta il layout delle etichette di categoria genitore. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Rappresenta il layout delle etichette di categoria genitore. |
| [hasUpDownBars()](#hasUpDownBars--) | Determina se un grafico a linee o a barre ha barre su/giù. |
| [getGapWidth()](#getGapWidth--) | Specifica lo spazio tra i gruppi di barre o colonne, come percentuale della larghezza della barra o della colonna. |
| [getGapDepth()](#getGapDepth--) | Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Specifica l'angolo della prima fetta di un grafico a torta o ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specifica la dimensione del foro in un grafico a ciambella (può essere tra il 10 % e il 90 % della dimensione dell'area del grafico). |
| [getOverlap()](#getOverlap--) | Specifica quanto le barre e le colonne si sovrappongono nei grafici 2-D, come percentuale (da -100 % a 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Specifica la dimensione della seconda fetta di torta o della seconda barra in un grafico torta-di-torta o barra-di-torta, come percentuale della prima torta (può essere tra il 5 % e il 200 %). |
| [hasSeriesLines()](#hasSeriesLines--) | Determina se esistono linee di serie per questa serie e le serie correlate. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specifica come i valori di dimensione delle bolle sono rappresentati nel grafico a bolle. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specifica un valore da utilizzare per determinare quali punti dati sono nella seconda torta o barra in un grafico torta-di-torta o barra-di-torta. |
| [getPieSplitBy()](#getPieSplitBy--) | Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico torta-di-torta o barra-di-torta. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Le informazioni di divisione personalizzate per un grafico torta-di-torta o barra-di-torta con divisione personalizzata. |
| [isColorVaried()](#isColorVaried--) | Specifica che ogni marcatore di dati nella serie ha un colore diverso. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 % della dimensione predefinita). |
| [getSlide()](#getSlide--) | Restituisce la diapositiva genitore di un FillFormat. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione genitore di un FillFormat. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Restituisce il grafico genitore. Solo lettura [IChart](../../com.aspose.slides/ichart).

**Restituisce:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

La distanza di una fetta di torta aperta dal centro del grafico a torta è espressa come percentuale del diametro della torta. Lettura/Scrittura int.

**Restituisce:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

La distanza di una fetta di torta aperta dal centro del grafico a torta è espressa come percentuale del diametro della torta. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Rappresenta l'ammorbidimento della curva. Vero se l'ammorbidimento è attivo per il grafico a linee o a dispersione. Valido solo per i grafici a linee e dispersione collegati da linee. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Rappresenta l'ammorbidimento della curva. Vero se l'ammorbidimento è attivo per il grafico a linee o a dispersione. Valido solo per i grafici a linee e dispersione collegati da linee. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

Restituisce il nome della serie. Solo lettura [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Restituisce:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Restituisce la raccolta di punti dati di questa serie. Solo lettura [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Restituisce:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

Restituisce un tipo di questa serie. Lettura/Scrittura [ChartType](../../com.aspose.slides/charttype).

**Restituisce:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Restituisce un tipo di questa serie. Lettura/Scrittura [ChartType](../../com.aspose.slides/charttype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Indica se questa serie è tracciata su un asse secondario. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Indica se questa serie è tracciata su un asse secondario. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Solo lettura [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Restituisce:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Restituisce il formato di una serie. Solo lettura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

Restituisce l'ordine di una serie. Lettura/Scrittura int.

**Restituisce:**
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Restituisce l'ordine di una serie. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Restituisce le Labels di una serie. Solo lettura [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Restituisce:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Raccolta di linee di tendenza della serie. Solo lettura [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

Le TrendLines sono disponibili (non null) per le serie di dati nei grafici area, barre, colonne, linee, azioni, xy (dispersione) e bolle non impilati a 2-D. Non sono disponibili per serie in grafici impilati o 3-D. Non sono disponibili per grafici radar, torta, superficie o ciambella.

**Restituisce:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Rappresenta le ErrorBars della serie con direzione X. Solo lettura [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Le ErrorBars con direzione X sono disponibili per le serie di tipo area, barra, dispersione e bolle. Per tutti gli altri tipi di grafico questa proprietà restituisce null (inclusi i grafici 3D). In caso di valori personalizzati usare la raccolta DataPoints per specificare il valore (con la proprietà ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Restituisce:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Rappresenta le ErrorBars della serie con direzione Y. Solo lettura [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Le ErrorBars con direzione Y sono disponibili per le serie di tipo area, barra, linea, dispersione e bolle. Per tutti gli altri tipi di grafico questa proprietà restituisce null (inclusi i grafici 3D). In caso di valori personalizzati usare la raccolta DataPoints per specificare il valore (con la proprietà ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Restituisce:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Rappresenta la voce della legenda collegata a questa serie. Solo lettura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Restituisce:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Solo lettura [IMarker](../../com.aspose.slides/imarker).

**Restituisce:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Specifica la forma di una serie di un grafico a barre 3-D. La modifica di questo valore può causare la modifica automatica del tipo della serie. Lettura/Scrittura [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Restituisce:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Specifica la forma di una serie di un grafico a barre 3-D. La modifica di questo valore può causare la modifica automatica del tipo della serie. Lettura/Scrittura [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Specifica che la serie a barre, colonne o bolle deve invertire i colori se il valore è negativo. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Specifica che la serie a barre, colonne o bolle deve invertire i colori se il valore è negativo. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

Specifica l'inversione del colore pieno per la serie. Per applicare l'impostazione del colore impostare FillType della serie su FillType.Solid. Lettura/Scrittura [ColorFormat](../../com.aspose.slides/colorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

Restituisce un colore automatico della serie basato sull'indice della serie e sullo stile del grafico. Questo colore è usato di default se FillType è NotDefined.

**Restituisce:**
java.lang.Integer - L'oggetto java.lang.Integer.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Rappresenta i punti interni. Vero se i punti interni sono mostrati nel grafico BoxAndWhisker. Valido solo per i grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Rappresenta i punti interni. Vero se i punti interni sono mostrati nel grafico BoxAndWhisker. Valido solo per i grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Rappresenta i punti anomali. Vero se i punti anomali sono mostrati nel grafico BoxAndWhisker. Valido solo per i grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Rappresenta i punti anomali. Vero se i punti anomali sono mostrati nel grafico BoxAndWhisker. Valido solo per i grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Rappresenta i marcatori della media. Vero se i marcatori della media sono mostrati nel grafico BoxAndWhisker. Valido solo per i grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Rappresenta i marcatori della media. Vero se i marcatori della media sono mostrati nel grafico BoxAndWhisker. Valido solo per i grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Rappresenta la linea della media. Vero se la linea della media è mostrata nel grafico BoxAndWhisker. Valido solo per i grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Rappresenta la linea della media. Vero se la linea della media è mostrata nel grafico BoxAndWhisker. Valido solo per i grafici BoxAndWhisker. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Rappresenta il metodo quartile. Valido solo per i grafici BoxAndWhisker.

**Restituisce:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Rappresenta il metodo quartile. Valido solo per i grafici BoxAndWhisker.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Rappresenta le linee di collegamento. Valido solo per i grafici Waterfall.

**Restituisce:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Rappresenta le linee di collegamento. Valido solo per i grafici Waterfall.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Rappresenta il layout delle etichette di categoria genitore. Valido solo per i grafici Treemap.

**Restituisce:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Rappresenta il layout delle etichette di categoria genitore. Valido solo per i grafici Treemap.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Determina se un grafico a linee o a barre ha barre su/giù. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo genitore – è una proiezione della proprietà del gruppo appropriato. Pertanto è sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo genitore. Usa la proprietà ParentSeriesGroup.UpDownBars.HasUpDownBars Lettura/Scrittura per modificare il valore. Usa la proprietà ParentSeriesGroup.UpDownBars per formattare le barre su/giù. Solo lettura boolean.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Restituisce:**
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Specifica lo spazio tra i gruppi di barre o colonne, come percentuale della larghezza della barra o della colonna. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo genitore – è una proiezione della proprietà del gruppo appropriato. Pertanto è sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo genitore. Usa la proprietà ParentSeriesGroup.GapWidth Lettura/Scrittura per modificare il valore. Solo lettura int.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.GapWidth.

**Restituisce:**
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo genitore – è una proiezione della proprietà del gruppo appropriato. Pertanto è sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo genitore. Usa la proprietà ParentSeriesGroup.GapDepth Lettura/Scrittura per modificare il valore. Solo lettura int.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.GapDepth.

**Restituisce:**
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Specifica l'angolo della prima fetta di un grafico a torta o ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo genitore – è una proiezione della proprietà del gruppo appropriato. Pertanto è sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo genitore. Usa la proprietà ParentSeriesGroup.FirstSliceAngle Lettura/Scrittura per modificare il valore. Solo lettura int.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.FirstSliceAngle.

**Restituisce:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Specifica la dimensione del foro in un grafico a ciambella (può essere tra il 10 % e il 90 % della dimensione dell'area del grafico). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo genitore – è una proiezione della proprietà del gruppo appropriato. Pertanto è sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo genitore. Usa la proprietà ParentSeriesGroup.DoughnutHoleSize Lettura/Scrittura per modificare il valore. Solo lettura byte.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.DoughnutHoleSize.

**Restituisce:**
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Specifica quanto le barre e le colonne si sovrappongono nei grafici 2-D, come percentuale (da -100 % a 100 %). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo genitore. È una proiezione della proprietà corrispondente nel gruppo genitore, quindi è sola lettura. Per modificare il valore, usa la proprietà ParentSeriesGroup.Overlap Lettura/Scrittura. Solo lettura byte.

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
int         *     *  -  *
```

Specifica la dimensione della seconda fetta di torta o della seconda barra in un grafico torta-di-torta o barra-di-torta, come percentuale della prima torta (può essere tra il 5 % e il 200 %). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo genitore – è una proiezione della proprietà del gruppo appropriato. Pertanto è sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo genitore. Usa la proprietà ParentSeriesGroup.SecondPieSize Lettura/Scrittura per modificare il valore. Solo lettura int.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.SecondPieSize.

**Restituisce:**
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Determina se esistono linee di serie per questa serie e le serie correlate. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo genitore – è una proiezione della proprietà del gruppo appropriato. Pertanto è sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo genitore. Usa la proprietà ParentSeriesGroup.HasSeriesLines Lettura/Scrittura per modificare il valore. Usa la proprietà ParentSeriesGroup.SeriesLinesFormat per formattare le linee di serie. Solo lettura boolean.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.HasSeriesLines.

**Restituisce:**
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Specifica come i valori di dimensione delle bolle sono rappresentati nel grafico a bolle. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo genitore – è una proiezione della proprietà del gruppo appropriato. Pertanto è sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo genitore. Usa la proprietà ParentSeriesGroup.BubbleSizeRepresentation Lettura/Scrittura per modificare il valore.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.BubbleSizeRepresentation.

**Restituisce:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Specifica un valore da usare per determinare quali punti dati sono nella seconda torta o barra in un grafico torta-di-torta o barra-di-torta. È usato insieme alla proprietà PieSplitBy. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo genitore – è una proiezione della proprietà del gruppo appropriato. Pertanto è sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo genitore. Usa la proprietà ParentSeriesGroup.PieSplitPosition Lettura/Scrittura per modificare il valore. Solo lettura double.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.PieSplitPosition.

**Restituisce:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico torta-di-torta o barra-di-torta. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo genitore – è una proiezione della proprietà del gruppo appropriato. Pertanto è sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo genitore. Usa la proprietà ParentSeriesGroup.PieSplitBy Lettura/Scrittura per modificare il valore. Solo lettura [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Questa è la proiezione della proprietà ParentSeriesGroup.PieSplitBy. 2) Se il valore della proprietà è PieSplitType.Custom, è possibile definire informazioni di divisione personalizzate con la proprietà ParentSeriesGroup.PieSplitCustomPoints.

**Restituisce:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Le informazioni di divisione personalizzate per un grafico torta-di-torta o barra-di-torta con divisione personalizzata. Contiene i punti dati che devono essere disegnati nella seconda torta o barra. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo genitore – è una proiezione della proprietà del gruppo appropriato. Solo lettura [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.PieSplitCustomPoints.

**Restituisce:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Specifica che ogni marcatore di dati nella serie ha un colore diverso. Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo genitore – è una proiezione della proprietà del gruppo appropriato. Pertanto è sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo genitore. Usa la proprietà ParentSeriesGroup.IsColorVaried Lettura/Scrittura per modificare il valore. Solo lettura boolean.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.IsColorVaried.

**Restituisce:**
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 % della dimensione predefinita). Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo genitore – è una proiezione della proprietà del gruppo appropriato. Pertanto è sola lettura. Usa la proprietà ParentSeriesGroup per accedere al gruppo genitore. Usa la proprietà ParentSeriesGroup.BubbleSizeScale Lettura/Scrittura per modificare il valore.

--------------------

Questa è la proiezione della proprietà ParentSeriesGroup.BubbleSizeScale.

**Restituisce:**
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Restituisce la diapositiva genitore di un FillFormat. Solo lettura [BaseSlide](../../com.aspose.slides/baseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione genitore di un FillFormat. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)