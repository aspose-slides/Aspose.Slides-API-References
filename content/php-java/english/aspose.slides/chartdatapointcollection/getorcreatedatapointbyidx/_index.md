---
title: getOrCreateDataPointByIdx
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/chartdatapointcollection/getorcreatedatapointbyidx/
---

## getOrCreateDataPointByIdx(long index)  method

 If collection already contains data point with index index then returns this data point.
 If collection doesn't contains data point with index index==N
 (when number of data points in this collection is less or equal then N)
 then adds deficient data points and returns last (which has requested index).
 For example, collection indexes are {0, 1, 2}, and requested index is 5.
 Then method adds deficient data points: {0, 1, 2, 3, 4, 5}. And returns data point with index 5.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | long | Index. |

### Returns
[ChartDataPoint](../../chartdatapoint)


---


