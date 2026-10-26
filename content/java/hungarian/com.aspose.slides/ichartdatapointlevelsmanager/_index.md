---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Az adatpont-szintek tárolója.
type: docs
url: /hu/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Az adatpont-szintek tárolója. Treeamp és Sunburst sorozatokhoz alkalmazható. Az adatpont-szintek indexelése nulláral kezdődik.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Visszaad egy IChartDataPointLevel objektumot a meghatározott szinthez. |
| [getCount()](#getCount--) | Visszaadja az adatpont-szintek számát. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```

Visszaad egy IChartDataPointLevel objektumot a meghatározott szinthez.

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

Visszaadja az adatpont-szintek számát.

**Visszatérési érték:**
int