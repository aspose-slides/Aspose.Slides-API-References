---
title: set_range method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docS
url: /aspose.slides.charts/ichartdata/set_range/
weight: 30
---


## set_range {#string}
Set chart data range. Series and categories will be updated based on new data range.
            If amount of series in data range greater than count of series in the chart data then additional series with the same type
            as a last series in the current collection will be added to the end of the collection.


```python
def set_range(self, formula):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| formula | string | The cells data range formula. E.g: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

## Exceptions

| Exception | Description |
| :- | :- |
| .NET type System.ArgumentNullException | formula is null. |
| .NET type System.ArgumentException | formula has incorrect format. |



