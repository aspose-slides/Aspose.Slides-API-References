---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Az adatpont szintek tárolója.
type: docs
url: /hu/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Az adatpont szintek tárolója. A Treeamp és a Sunburst sorozatokhoz alkalmazható. Az adatpont szintek indexelése nullától indul.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Visszaadja a meghatározott szinthez tartozó IChartDataPointLevel objektumot. |
| [getCount()](#getCount--) | Visszaadja az adatpont szintek számát. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```

Visszaadja a meghatározott szinthez tartozó IChartDataPointLevel objektumot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| level | int |  |

**Visszatérési érték:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Visszaadja az adatpont szintek számát.

**Visszatérési érték:**
int