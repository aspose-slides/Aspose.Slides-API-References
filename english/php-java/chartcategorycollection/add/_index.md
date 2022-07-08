---
title: add
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/chartcategorycollection/add/
---

## add([ChartDataCell](../../chartdatacell) chartDataCell)  method

 If category exists in collection, return it. Else creates new chart category from 
  IChartDataCell and adds it to the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| chartDataCell | [ChartDataCell](../../chartdatacell) | Cell used to create chart category. |

### Returns
[ChartCategory](../../chartcategory)


---


## add(Object value)  method

  Creates new  ChartCategory from value and adds it to the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | Object | The value. This method adds worksheet with name AUTO_DATA and adds all values there. If you use ChartDataWorkbook to add or edit cell values, be sure that you do not use this worksheet Maximum number of values added using this method must not exceed 16711680 |

### Returns
[ChartCategory](../../chartcategory)

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | if limit exceeded |


---


