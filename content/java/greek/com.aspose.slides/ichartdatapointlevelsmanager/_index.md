---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Το κοντέινερ των επιπέδων σημείων δεδομένων.
type: docs
url: /el/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Το κοντέινερ των επιπέδων σημείων δεδομένων. Εφαρμόζεται για σειρές Treeamp και Sunburst. Η αρίθμηση των επιπέδων σημείων δεδομένων είναι μηδενική.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returns IChartDataPointLevel object for defined level. |
| [getCount()](#getCount--) | Returns data point levels count. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```

Returns IChartDataPointLevel object for defined level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int |  |

**Returns:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Returns data point levels count.

**Returns:**
int