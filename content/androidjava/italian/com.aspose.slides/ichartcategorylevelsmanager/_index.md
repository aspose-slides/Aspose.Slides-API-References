---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides per Android tramite Java API Reference
description: Contenitore gestito dei valori dei livelli di categoria del grafico.
type: docs
url: /it/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Contenitore gestito dei valori dei livelli di categoria del grafico.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Restituisce l'oggetto IChartDataCell per il livello definito. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Imposta l'elemento di raggruppamento per il livello definito. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Elimina l'elemento di raggruppamento per il livello definito. |

### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Restituisce l'oggetto IChartDataCell per il livello definito.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| level | int |  |

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Imposta l'elemento di raggruppamento per il livello definito.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| level | int | Livello di categoria int |
| value | java.lang.Object | Oggetto elemento di raggruppamento |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Elimina l'elemento di raggruppamento per il livello definito.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| level | int | Livello di categoria int |