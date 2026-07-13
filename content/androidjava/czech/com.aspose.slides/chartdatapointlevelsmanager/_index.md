---
title: ChartDataPointLevelsManager
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Kontejner úrovní datových bodů.
type: docs
url: /cs/com.aspose.slides/chartdatapointlevelsmanager/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
```
public class ChartDataPointLevelsManager extends DomObject<ChartDataPoint> implements IChartDataPointLevelsManager
```

Kontejner úrovní datových bodů. Používá se pro řady Treeamp a Sunburst. Indexování úrovní datových bodů je založeno na nulové bázi.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Vrací objekt IChartDataPointLevel pro definovanou úroveň. |
| [getCount()](#getCount--) | Vrací počet úrovní datových bodů. |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataPointLevel get_Item(int level)
```

Vrací objekt IChartDataPointLevel pro definovanou úroveň.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| level | int |  |

**Návratová hodnota:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public final int getCount()
```

Vrací počet úrovní datových bodů.

**Návratová hodnota:**
int