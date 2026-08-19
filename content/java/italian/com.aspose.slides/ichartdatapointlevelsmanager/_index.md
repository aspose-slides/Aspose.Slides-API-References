---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Contenitore di livelli di punto dati.
type: docs
url: /it/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Contenitore di livelli di punto dati. Applicato per le serie Treeamp e Sunburst. L'indicizzazione dei livelli di punto dati è basata su zero.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Restituisce l'oggetto IChartDataPointLevel per il livello definito. |
| [getCount()](#getCount--) | Restituisce il conteggio dei livelli di punto dati. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
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
public abstract int getCount()
```

Restituisce il conteggio dei livelli di punto dati.

**Restituisce:**
int