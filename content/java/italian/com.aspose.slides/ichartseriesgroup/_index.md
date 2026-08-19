---
title: IChartSeriesGroup
second_title: Aspose.Slides per Java – Riferimento API
description: Rappresenta un gruppo di serie.
type: docs
url: /it/com.aspose.slides/ichartseriesgroup/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Rappresenta un gruppo di serie.

--------------------

1) Vedere il riepilogo e le note per ChartSeriesGroupCollection classe e CombinableSeriesTypesGroup enum. 2) Il gruppo di serie contiene alcune proprietà delle serie che sono comuni a ogni serie del gruppo ("series group properties"). "Series group properties" in ChartSeriesGroup classe è lettura/scrittura. Ciascuna delle "series group properties" può avere una proiezione solo lettura in ChartSeries classe.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Restituisce un tipo di questo gruppo di serie. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indica se le serie di questo gruppo sono tracciate su un asse secondario. |
| [getSeries()](#getSeries--) | Restituisce una collezione sola lettura di serie del grafico. |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [getUpDownBars()](#getUpDownBars--) | Fornisce l'accesso alle barre su/giù dei grafici Line o Stock. |
| [getGapWidth()](#getGapWidth--) | Specifica lo spazio tra gruppi di barre o colonne, come percentuale della larghezza della barra o colonna. |
| [setGapWidth(int value)](#setGapWidth-int-) | Specifica lo spazio tra gruppi di barre o colonne, come percentuale della larghezza della barra o colonna. |
| [getGapDepth()](#getGapDepth--) | Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Ottiene o imposta l'angolo della prima fetta del grafico torta o ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Ottiene o imposta l'angolo della prima fetta del grafico torta o ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). |
| [isColorVaried()](#isColorVaried--) | Specifica che ogni marcatore dei dati nella serie ha un colore diverso. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Specifica che ogni marcatore dei dati nella serie ha un colore diverso. |
| [hasSeriesLines()](#hasSeriesLines--) | Vero se il grafico ha linee di serie. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Vero se il grafico ha linee di serie. |
| [getOverlap()](#getOverlap--) | Specifica di quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Specifica di quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specifica la dimensione del secondo segmento di torta o barra di un grafico torta-in-torta o barra-in-torta, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percenti). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Specifica la dimensione del secondo segmento di torta o barra di un grafico torta-in-torta o barra-in-torta, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percenti). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specifica un valore da usare per determinare quali punti dati sono nella seconda torta o barra in un grafico torta-in-torta o barra-in-torta. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Specifica un valore da usare per determinare quali punti dati sono nella seconda torta o barra in un grafico torta-in-torta o barra-in-torta. |
| [getPieSplitBy()](#getPieSplitBy--) | Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico torta-in-torta o barra-in-torta. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico torta-in-torta o barra-in-torta. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Le informazioni di divisione personalizzate per un grafico torta-in-torta o barra-in-torta con divisione personalizzata. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specifica la dimensione del foro in un grafico ciambella (può essere tra 10 e 90 percento della dimensione dell'area del grafico). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Specifica la dimensione del foro in un grafico ciambella (può essere tra 10 e 90 percento della dimensione dell'area del grafico). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percenti della dimensione predefinita). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percenti della dimensione predefinita). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Specifica il formato HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specifica come i valori di dimensione delle bolle sono rappresentati nel grafico a bolle. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Specifica come i valori di dimensione delle bolle sono rappresentati nel grafico a bolle. |

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

Indica se le serie di questo gruppo sono tracciate su un asse secondario. Solo lettura boolean.

**Restituisce:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Restituisce una collezione sola lettura di serie del grafico. Solo lettura [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

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

Fornisce l'accesso alle barre su/giù dei grafici Line o Stock. Solo lettura [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Restituisce:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Specificaza lo spazio tra gruppi di barre o colonne, come percentuale della larghezza della barra o colonna. Lettura/scrittura int.

**Restituisce:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Specificaza lo spazio tra gruppi di barre o colonne, come percentuale della larghezza della barra o colonna. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Lettura/scrittura int.

**Restituisce:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Restituisce o imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Ottiene o imposta l'angolo della prima fetta di torta o ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). Lettura/scrittura int.

**Restituisce:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Ottiene o imposta l'angolo della prima fetta di torta o ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Specificaza che ogni marcatore dei dati nella serie ha un colore diverso. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Specificaza che ogni marcatore dei dati nella serie ha un colore diverso. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Vero se il grafico ha linee di serie. Applicato ai grafici a barre impilate e OfPie. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Vero se il grafico ha linee di serie. Applicato ai grafici a barre impilate e OfPie. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Specificaza di quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). - -100%: Spaziatura massima (le barre sono completamente separate). - 0%: Le barre sono affiancate senza sovrapposizione né spaziatura. - 100%: Sovrapposizione massima (le barre si sovrappongono completamente). Questa proprietà è lettura/scrittura byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Set overlap to 55%
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

Specificaza di quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). - -100%: Spaziatura massima (le barre sono completamente separate). - 0%: Le barre sono affiancate senza sovrapposizione né spaziatura. - 100%: Sovrapposizione massima (le barre si sovrappongono completamente). Questa proprietà è lettura/scrittura byte.

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

Specificaza la dimensione del secondo segmento di torta o barra di un grafico torta-in-torta o barra-in-torta, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percenti). Lettura/scrittura int.

**Restituisce:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Specificaza la dimensione del secondo segmento di torta o barra di un grafico torta-in-torta o barra-in-torta, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percenti). Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Specificaza un valore da usare per determinare quali punti dati sono nella seconda torta o barra in un grafico torta-in-torta o barra-in-torta. È usato insieme alla proprietà PieSplitBy. Lettura/scrittura double.

**Restituisce:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Specificaza un valore da usare per determinare quali punti dati sono nella seconda torta o barra in un grafico torta-in-torta o barra-in-torta. È usato insieme alla proprietà PieSplitBy. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Specificaza come determinare quali punti dati sono nella seconda torta o barra in un grafico torta-in-torta o barra-in-torta. Lettura/scrittura [PieSplitType](../../com.aspose.slides/piesplittype).

**Restituisce:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Specificaza come determinare quali punti dati sono nella seconda torta o barra in un grafico torta-in-torta o barra-in-torta. Lettura/scrittura [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Le informazioni di divisione personalizzate per un grafico torta-in-torta o barra-in-torta con divisione personalizzata. Contiene i punti dati che devono essere disegnati nella seconda torta o barra in un grafico torta-in-torta o barra-in-torta. Solo lettura [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Restituisce:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Specificaza la dimensione del foro in un grafico ciambella (può essere tra 10 e 90 percenti della dimensione dell'area del grafico). Lettura/scrittura byte.

**Restituisce:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Specificaza la dimensione del foro in un grafico ciambella (può essere tra 10 e 90 percenti della dimensione dell'area del grafico). Lettura/scrittura byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Specificaza il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percenti della dimensione predefinita). Lettura/scrittura int.

**Restituisce:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Specificaza il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percenti della dimensione predefinita). Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Specificaza il formato HiLowLines. HiLowLines è applicato ai tipi di grafico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose.

**Restituisce:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Specificaza come i valori di dimensione delle bolle sono rappresentati nel grafico a bolle. Lettura/scrittura [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Restituisce:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Specificaza come i valori di dimensione delle bolle sono rappresentati nel grafico a bolle. Lettura/scrittura [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |