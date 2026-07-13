---
title: IChartSeriesGroup
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un gruppo di serie.
type: docs
url: /it/com.aspose.slides/ichartseriesgroup/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Rappresenta un gruppo di serie.

--------------------

1) Vedere il riepilogo e le note per la classe ChartSeriesGroupCollection e l'enum CombinableSeriesTypesGroup. 2) Un gruppo di serie contiene alcune proprietà delle serie che sono comuni a ciascuna serie nel gruppo ("proprietà del gruppo di serie"). Le "proprietà del gruppo di serie" nella classe ChartSeriesGroup sono lettura/scrittura. Ognuna delle "proprietà del gruppo di serie" può avere una proiezione solo lettura nella classe ChartSeries.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Restituisce un tipo di questo gruppo di serie. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indica se le serie di questo gruppo sono tracciate sull'asse secondario. |
| [getSeries()](#getSeries--) | Restituisce una collezione di sola lettura di serie di grafico. |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [getUpDownBars()](#getUpDownBars--) | Fornisce l'accesso alle barre up/down di un grafico a linee o a barre. |
| [getGapWidth()](#getGapWidth--) | Specifica lo spazio tra i raggruppamenti di barre o colonne, come percentuale della larghezza della barra o della colonna. |
| [setGapWidth(int value)](#setGapWidth-int-) | Specifica lo spazio tra i raggruppamenti di barre o colonne, come percentuale della larghezza della barra o della colonna. |
| [getGapDepth()](#getGapDepth--) | Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Ottiene o imposta l'angolo della prima fetta di un grafico a torta o a ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Ottiene o imposta l'angolo della prima fetta di un grafico a torta o a ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). |
| [isColorVaried()](#isColorVaried--) | Specifica che ogni marcatore dati nella serie ha un colore diverso. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Specifica che ogni marcatore dati nella serie ha un colore diverso. |
| [hasSeriesLines()](#hasSeriesLines--) | Vero se il grafico ha linee di serie. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Vero se il grafico ha linee di serie. |
| [getOverlap()](#getOverlap--) | Specifica quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Specifica quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specifica la dimensione della seconda fetta o barra di un grafico torta-su-torta o barra-su-torta, come percentuale della dimensione della prima torta (può essere tra 5 e 200%). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Specifica la dimensione della seconda fetta o barra di un grafico torta-su-torta o barra-su-torta, come percentuale della dimensione della prima torta (può essere tra 5 e 200%). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specifica un valore da usare per determinare quali punti dati sono nella seconda torta o barra su un grafico torta-su-torta o barra-su-torta. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Specifica un valore da usare per determinare quali punti dati sono nella seconda torta o barra su un grafico torta-su-torta o barra-su-torta. |
| [getPieSplitBy()](#getPieSplitBy--) | Specifica come determinare quali punti dati sono nella seconda torta o barra su un grafico torta-su-torta o barra-su-torta. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Specifica come determinare quali punti dati sono nella seconda torta o barra su un grafico torta-su-torta o barra-su-torta. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Le informazioni di divisione personalizzata per un grafico torta-su-torta o barra-su-torta con una divisione personalizzata. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specifica la dimensione del foro in un grafico a ciambella (può essere tra il 10% e il 90% della dimensione dell'area del grafico). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Specifica la dimensione del foro in un grafico a ciambella (può essere tra il 10% e il 90% della dimensione dell'area del grafico). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300% della dimensione predefinita). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300% della dimensione predefinita). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Specifica il formato HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specifica come i valori della dimensione delle bolle sono rappresentati nel grafico a bolle. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Specifica come i valori della dimensione delle bolle sono rappresentati nel grafico a bolle. |

### getType() {#getType--}
```
public abstract int getType()
```

Restituisce un tipo di questo gruppo di serie. Solo lettura [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Restituisce:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Indica se le serie di questo gruppo sono tracciate sull'asse secondario. Solo lettura boolean.

**Restituisce:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Restituisce una collezione di sola lettura di serie di grafico. Solo lettura [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Restituisce:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
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
public abstract IUpDownBarsManager getUpDownBars()
```

Fornisce l'accesso alle barre up/down di un grafico a linee o a barre. Solo lettura [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Restituisce:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Specifica lo spazio tra i raggruppamenti di barre o colonne, come percentuale della larghezza della barra o della colonna. Lettura/Scrittura int.

**Restituisce:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Specific a lo spazio tra i raggruppamenti di barre o colonne, come percentuale della larghezza della barra o della colonna. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Lettura/Scrittura int.

**Restituisce:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Ottiene o imposta l'angolo della prima fetta di un grafico a torta o a ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). Lettura/Scrittura int.

**Restituisce:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Ottiene o imposta l'angolo della prima fetta di un grafico a torta o a ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Specific a che ogni marcatore dati nella serie ha un colore diverso. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Specific a che ogni marcatore dati nella serie ha un colore diverso. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Vero se il grafico ha linee di serie. Applicato a grafici a barre impilate e OfPie. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Vero se il grafico ha linee di serie. Applicato a grafici a barre impilate e OfPie. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Specific a quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). -100%: Spaziatura massima (le barre sono completamente separate). -0%: Le barre sono posizionate una accanto all'altra senza sovrapposizione o spaziatura. 100%: Sovrapposizione massima (le barre si sovrappongono completamente). Questa proprietà è Lettura/Scrittura byte.

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
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Specific a quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). -100%: Spaziatura massima (le barre sono completamente separate). -0%: Le barre sono posizionate una accanto all'altra senza sovrapposizione o spaziatura. 100%: Sovrapposizione massima (le barre si sovrappongono completamente). Questa proprietà è Lettura/Scrittura byte.

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
public abstract int getSecondPieSize()
```

Specific a la dimensione della seconda torta o barra di un grafico torta-su-torta o barra-su-torta, come percentuale della dimensione della prima torta (può essere tra 5 e 200%). Lettura/Scrittura int.

**Restituisce:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Specific a la dimensione della seconda torta o barra di un grafico torta-su-torta o barra-su-torta, come percentuale della dimensione della prima torta (può essere tra 5 e 200%). Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Specific a un valore da usare per determinare quali punti dati sono nella seconda torta o barra su un grafico torta-su-torta o barra-su-torta. È usato insieme alla proprietà PieSplitBy. Lettura/Scrittura double.

**Restituisce:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Specific a un valore da usare per determinare quali punti dati sono nella seconda torta o barra su un grafico torta-su-torta o barra-su-torta. È usato insieme alla proprietà PieSplitBy. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Specific a come determinare quali punti dati sono nella seconda torta o barra su un grafico torta-su-torta o barra-su-torta. Lettura/Scrittura [PieSplitType](../../com.aspose.slides/piesplittype).

**Restituisce:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Specific a come determinare quali punti dati sono nella seconda torta o barra su un grafico torta-su-torta o barra-su-torta. Lettura/Scrittura [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Le informazioni di divisione personalizzata per un grafico torta-su-torta o barra-su-torta con una divisione personalizzata. Contiene punti dati che devono essere disegnati nella seconda torta o barra in un grafico torta-su-torta o barra-su-torta. Solo lettura [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Restituisce:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Specific a la dimensione del foro in un grafico a ciambella (può essere tra il 10% e il 90% della dimensione dell'area del grafico). Lettura/Scrittura byte.

**Restituisce:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Specific a la dimensione del foro in un grafico a ciambella (può essere tra il 10% e il 90% della dimensione dell'area del grafico). Lettura/Scrittura byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Specific a il fattore di scala per il grafico a bolle (può essere tra 0 e 300% della dimensione predefinita). Lettura/Scrittura int.

**Restituisce:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Specific a il fattore di scala per il grafico a bolle (può essere tra 0 e 300% della dimensione predefinita). Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Specific a il formato HiLowLines. HiLowLines viene applicato con i tipi di grafico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose.

**Restituisce:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Specific a come i valori della dimensione delle bolle sono rappresentati nel grafico a bolle. Lettura/Scrittura [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Restituisce:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Specific a come i valori della dimensione delle bolle sono rappresentati nel grafico a bolle. Lettura/Scrittura [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |