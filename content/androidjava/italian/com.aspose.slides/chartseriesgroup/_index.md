---
title: ChartSeriesGroup
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un gruppo di serie.
type: docs
url: /it/com.aspose.slides/chartseriesgroup/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Rappresenta un gruppo di serie.

--------------------

1) Vedere il riepilogo e le osservazioni per la classe ChartSeriesGroupCollection e l'enumerazione CombinableSeriesTypesGroup. 2) Il gruppo di serie contiene alcune series properies whitch è comune per ogni serie nel gruppo ("Series group properties"). "Series group properties" nella classe ChartSeriesGroup è read/write. Ognuna delle "Series group properties" può avere una proiezione read-only nella classe ChartSeries.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Restituisce un tipo di questo gruppo di serie. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indica se le serie di questo gruppo sono tracciate su un asse secondario. |
| [getSeries()](#getSeries--) | Restituisce una collezione di serie. |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [getUpDownBars()](#getUpDownBars--) | Fornisce l'accesso alle barre up/down di un grafico Line- o Stock-chart. |
| [getGapWidth()](#getGapWidth--) | Specifica lo spazio tra i gruppi di barre o colonne, come percentuale della larghezza della barra o colonna. |
| [setGapWidth(int value)](#setGapWidth-int-) | Specifica lo spazio tra i gruppi di barre o colonne, come percentuale della larghezza della barra o colonna. |
| [getGapDepth()](#getGapDepth--) | Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Ottiene o imposta l'angolo della prima fetta di un grafico a torta o ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Ottiene o imposta l'angolo della prima fetta di un grafico a torta o ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specifica la dimensione del foro in un grafico a ciambella (può essere tra 0 e 90 percenti della dimensione dell'area del grafico). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Specifica la dimensione del foro in un grafico a ciambella (può essere tra 0 e 90 percenti della dimensione dell'area del grafico). |
| [getOverlap()](#getOverlap--) | Specifica quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Specifica quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specifica la dimensione della seconda torta o barra di un grafico pie-of-pie o bar-of-pie, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percenti). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Specifica la dimensione della seconda torta o barra di un grafico pie-of-pie o bar-of-pie, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percenti). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specifica come i valori di dimensione delle bolle sono rappresentati nel grafico a bolle. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Specifica come i valori di dimensione delle bolle sono rappresentati nel grafico a bolle. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specifica un valore da usare per determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Specifica un valore da usare per determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. |
| [isColorVaried()](#isColorVaried--) | Specifica che ogni marcatore dati nella serie ha un colore diverso. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Specifica che ogni marcatore dati nella serie ha un colore diverso. |
| [hasSeriesLines()](#hasSeriesLines--) | Vero se il grafico ha linee di serie. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Vero se il grafico ha linee di serie. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Specifica il formato HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percenti della dimensione predefinita). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percenti della dimensione predefinita). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Le informazioni di divisione personalizzata per un grafico pie-of-pie o bar-of-pie con divisione personalizzata. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Restituisce il grafico genitore. |
| [getSlide()](#getSlide--) | Restituisce la diapositiva genitore di un FillFormat. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione genitore di un FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Restituisce un tipo di questo gruppo di serie. Solo lettura [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Restituisce:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Indica se le serie di questo gruppo sono tracciate su un asse secondario. Solo lettura boolean.

**Restituisce:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Restituisce una collezione di serie. Solo lettura [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Restituisce:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Ottiene l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Fornisce l'accesso alle barre up/down di un grafico Line- o Stock-chart. Solo lettura [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Restituisce:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Specifica lo spazio tra i gruppi di barre o colonne, come percentuale della larghezza della barra o colonna. Lettura/Scrittura int.

**Restituisce:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Specifica lo spazio tra i gruppi di barre o colonne, come percentuale della larghezza della barra o colonna. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Lettura/Scrittura int.

**Restituisce:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Ottiene o imposta l'angolo della prima fetta di un grafico a torta o ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). Lettura/Scrittura int.

**Restituisce:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Ottiene o imposta l'angolo della prima fetta di un grafico a torta o ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Specifica la dimensione del foro in un grafico a ciambella (può essere tra 0 e 90 percenti della dimensione dell'area del grafico). Lettura/Scrittura byte.

**Restituisce:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Specifica la dimensione del foro in un grafico a ciambella (può essere tra 0 e 90 percenti della dimensione dell'area del grafico). Lettura/Scrittura byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Specifica quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). - -100%: Spaziatura massima (le barre sono completamente separate). - 0%: Le barre sono affiancate senza sovrapposizione o spaziatura. - 100%: Sovrapposizione massima (le barre si sovrappongono completamente). Questa proprietà è Lettura/Scrittura byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Imposta la sovrapposizione al 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Specifica quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). - -100%: Spaziatura massima (le barre sono completamente separate). - 0%: Le barre sono affiancate senza sovrapposizione o spaziatura. - 100%: Sovrapposizione massima (le barre si sovrappongono completamente). Questa proprietà è Lettura/Scrittura byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Imposta la sovrapposizione al 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Specifica la dimensione della seconda torta o barra di un grafico pie-of-pie o bar-of-pie, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percenti). Lettura/Scrittura int.

**Restituisce:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Specifica la dimensione della seconda torta o barra di un grafico pie-of-pie o bar-of-pie, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percenti). Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Specifica come i valori di dimensione delle bolle sono rappresentati nel grafico a bolle. Lettura/Scrittura [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Restituisce:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Specifica come i valori di dimensione delle bolle sono rappresentati nel grafico a bolle. Lettura/Scrittura [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Specifica un valore da usare per determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. È usato insieme alla proprietà PieSplitBy. Lettura/Scrittura double.

**Restituisce:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Specifica un valore da usare per determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. È usato insieme alla proprietà PieSplitBy. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Lettura/Scrittura [PieSplitType](../../com.aspose.slides/piesplittype).

**Restituisce:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Lettura/Scrittura [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Specifica che ogni marcatore dati nella serie ha un colore diverso. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Specifica che ogni marcatore dati nella serie ha un colore diverso. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Vero se il grafico ha linee di serie. Applicato ai grafici a barre impilate e OfPie. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Vero se il grafico ha linee di serie. Applicato ai grafici a barre impilate e OfPie. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Specifica il formato HiLowLines. HiLowLines è applicato con i tipi di grafico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose.

**Restituisce:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percenti della dimensione predefinita). Lettura/Scrittura int.

**Restituisce:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percenti della dimensione predefinita). Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Le informazioni di divisione personalizzata per un grafico pie-of-pie o bar-of-pie con divisione personalizzata. Contiene i punti dati che devono essere disegnati nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Solo lettura [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Restituisce:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

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

### getSlide() {#getSlide--}
```
public 
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