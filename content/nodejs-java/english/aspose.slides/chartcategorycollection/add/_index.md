---
title: add
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/chartcategorycollection/add/
---

## add([ChartDataCell](../../chartdatacell) chartDataCell)  function

 If category exists in collection, return it. Else creates new chart category from 
  IChartDataCell and adds it to the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| chartDataCell | [ChartDataCell](../../chartdatacell) | Cell used to create chart category. |

### Result
[ChartCategory](../../chartcategory)


---


## add(Object value)  function

  Creates new  ChartCategory from value and adds it to the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | Object | The value. This function adds worksheet with name AUTO_DATA and adds all values there. If you use ChartDataWorkbook to add or edit cell values, be sure that you do not use this worksheet Maximum number of values added using this function must not exceed 16711680 |

### Result
[ChartCategory](../../chartcategory)

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | if limit exceeded |


---


