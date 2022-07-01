---
title: add
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/chartcategorycollection/add/
---

## add(ChartDataCell chartDataCell)  method

 If category exists in collection, return it. Else creates new chart category from 
  IChartDataCell and adds it to the collection.
 

### Parameters

| Name | Description |
| --- | --- |
| chartDataCell | Cell used to create chart category. |

### Returns
IChartDataCell


---


## add(Object value)  method

  Creates new  ChartCategory from value and adds it to the collection.
 

### Parameters

| Name | Description |
| --- | --- |
| value | The value. This method adds worksheet with name AUTO_DATA and adds all values there. If you use ChartDataWorkbook to add or edit cell values, be sure that you do not use this worksheet Maximum number of values added using this method must not exceed 16711680 |

### Returns
ChartCategory

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | if limit exceeded |


---


