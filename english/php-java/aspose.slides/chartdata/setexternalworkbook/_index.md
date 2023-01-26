---
title: setExternalWorkbook
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 110
url: /php-java/aspose.slides/chartdata/setexternalworkbook/
---

## setExternalWorkbook(String workbookPath)  method

 Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook.  
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| workbookPath | String | Path to the target workbook |

### Returns
void

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | External workbook is not available or can't be loaded. |


---


## setExternalWorkbook(String workbookPath, boolean updateChartData)  method

 Sets external workbook as a data source for the chart. 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| workbookPath | String | Path to the target workbook |
| updateChartData | boolean | If value is false only workbook path will be updated. Chart data won't be loaded and updated from the target workbook. Can be used when target workbook doesn't exist or it's not available. If value is true chart data will be updated from the target workbook. |

### Returns
void

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | External workbook is not available or can't be loaded. |


---


