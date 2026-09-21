---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
หากคอลเลกชันมีข้อมูลจุดที่มีดัชนี `index` อยู่แล้ว จะคืนข้อมูลจุดนั้น
            หากคอลเลกชันไม่มีข้อมูลจุดที่มีดัชนี `index`==N
            (เมื่อจำนวนข้อมูลจุดในคอลเลกชันนี้น้อยกว่าหรือเท่ากับ N)
            จะทำการเพิ่มข้อมูลจุดที่ขาดหายและคืนค่าข้อมูลจุดสุดท้าย (ซึ่งมีดัชนีที่ร้องขอ)
            ตัวอย่างเช่น ดัชนีของคอลเลกชันคือ {0, 1, 2} และดัชนีที่ร้องขอคือ 5
            เมธอดจะเพิ่มข้อมูลจุดที่ขาดหาย: {0, 1, 2, 3, 4, 5} และคืนข้อมูลจุดที่มีดัชนี 5

### คืนค่า

คืนข้อมูลจุดที่มีดัชนีตามที่ร้องขอ.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนี. |



### ดูเพิ่มเติม
* คลาส [`ChartDataPointCollection`](/slides/python-net/th/aspose.slides.charts/chartdatapointcollection)
* คลาส [`IChartDataPoint`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)