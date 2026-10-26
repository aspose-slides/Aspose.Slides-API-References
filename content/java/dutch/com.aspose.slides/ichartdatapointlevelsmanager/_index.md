---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides voor Java API-referentie
description: Container van datapunteniveaus.
type: docs
url: /nl/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Container van datapunteniveaus. Toegepast voor Treeamp- en Sunburst-series. Indexering van datapunteniveaus is nul-gebaseerd.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Retourneert een IChartDataPointLevel-object voor het opgegeven niveau. |
| [getCount()](#getCount--) | Retourneert het aantal datapunteniveaus. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```

Retourneert een IChartDataPointLevel-object voor het opgegeven niveau.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| level | int |  |

**Retour:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Retourneert het aantal datapunteniveaus.

**Retour:**
int