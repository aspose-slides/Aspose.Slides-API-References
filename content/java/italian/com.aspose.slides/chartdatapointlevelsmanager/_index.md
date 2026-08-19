---
title: ChartDataPointLevelsManager
second_title: Riferimento API di Aspose.Slides per Java
description: Contenitore dei livelli dei punti dati.
type: docs
url: /it/com.aspose.slides/chartdatapointlevelsmanager/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
```
public class ChartDataPointLevelsManager extends DomObject<ChartDataPoint> implements IChartDataPointLevelsManager
```

Contenitore dei livelli dei punti dati. Applicato alle serie Treeamp e Sunburst. L'indicizzazione dei livelli dei punti dati parte da zero.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Restituisce l'oggetto IChartDataPointLevel per il livello definito. |
| [getCount()](#getCount--) | Restituisce il conteggio dei livelli del punto dati. |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataPointLevel get_Item(int level)
```

Restituisce l'oggetto IChartDataPointLevel per il livello definito.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| level | int |  |

**Restituisce:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public final int getCount()
```

Restituisce il conteggio dei livelli del punto dati.

**Restituisce:**
int