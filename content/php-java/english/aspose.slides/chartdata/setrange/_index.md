---
title: setRange
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/chartdata/setrange/
---

## setRange(String formula)  method

 Set chart data range. Series and categories will be updated based on new data range.
 If amount of series in data range greater than count of series in the chart data then additional series with the same type
 as a last series in the current collection will be added to the end of the collection. 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| formula | String | The cells data range formula. E.g: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Returns
void

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentException | formula has incorrect format. |


---


