---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
If collection already contains data point with index `index` then returns this data point.
            If collection doesn't contains data point with index `index`==N
            (when number of data points in this collection is less or equal then N)
            then adds deficient data points and returns last (which has requested index).
            For example, collection indexes are {0, 1, 2}, and requested index is 5.
            Then method adds deficient data points: {0, 1, 2, 3, 4, 5}. And returns data point with index 5.

### คืนค่า

Returns data point with requested index.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนี. |



### ดูเพิ่มเติม
* คลาส [`IChartDataPoint`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint)
* คลาส [`IChartDataPointCollection`](/slides/python-net/th/aspose.slides.charts/ichartdatapointcollection)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)