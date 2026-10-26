---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Container of data point levels.
type: docs
url: /cs/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Kontejner úrovní datových bodů. Používá se pro řady Treeamp a Sunburst. Indexování úrovní datových bodů je založeno na nule.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Vrací objekt IChartDataPointLevel pro definovanou úroveň. |
| [getCount()](#getCount--) | Vrací počet úrovní datových bodů. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```


Vrací objekt IChartDataPointLevel pro definovanou úroveň.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| level | int |  |

**Vrací:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Vrací počet úrovní datových bodů.

**Vrací:**
int