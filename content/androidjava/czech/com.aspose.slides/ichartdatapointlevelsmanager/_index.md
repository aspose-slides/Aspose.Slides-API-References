---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Kontejner úrovní datových bodů.
type: docs
url: /cs/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Kontejner úrovní datových bodů. Používá se pro řady Treeamp a Sunburst. Indexování úrovní datových bodů je nulové.
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

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| level | int |  |

**Returns:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Vrací počet úrovní datových bodů.

**Returns:**
int