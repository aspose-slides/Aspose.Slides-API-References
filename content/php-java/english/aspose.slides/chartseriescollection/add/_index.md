---
title: add
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/chartseriescollection/add/
---

## add(int type)  method

 Creates new chart series and adds it to the collection. 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| type | int | Type of series |

### Returns
[ChartSeries](../../chartseries)


---


## add([ChartDataCell](../../chartdatacell) cellWithSeriesName, int type)  method

 Creates new chart series from  ChartDataCell and adds it to the collection. 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [ChartDataCell](../chartdatacell) | Cell which contain series name. |
| type | int | Type set type of series If chart series careted from same cell already in collection then method adds nothing and returns it's index. |

### Returns
[ChartSeries](../../chartseries)


---


## add([ChartCellCollection](../../chartcellcollection) cellsWithSeriesName, int type)  method

 Creates new chart series from  ChartCellCollection and adds it to the collection. 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [ChartCellCollection](../chartcellcollection) | Cells which contain series name. |
| type | int | Type set type of series If chart series careted from same cell already in collection then method adds nothing and returns it's index. |

### Returns
[ChartSeries](../../chartseries)


---


## add(String name, int type)  method

 Creates new chart series from value and adds it to the collection. 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Series name. |
| type | int | Type set type of series |

### Returns
[ChartSeries](../../chartseries)


---


