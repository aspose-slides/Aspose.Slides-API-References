---
title: add method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API อ้างอิง
description: 
type: docs
url: /th/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
สร้างชุดข้อมูลแผนภูมิใหม่และเพิ่มลงในคอลเลกชัน

### คืนค่า
ชุดข้อมูลแผนภูมิใหม่

```python
def add(self, type):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype) | ประเภทของชุดข้อมูล |

## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
สร้างชุดข้อมูลแผนภูมิใหม่จาก [`ChartDataCell`](/slides/python-net/th/aspose.slides.charts/chartdatacell) และเพิ่มลงในคอลเลกชัน

### คืนค่า
ชุดข้อมูลแผนภูมิที่เพิ่มแล้ว หรือชุดข้อมูลที่มีอยู่แล้วในคอลเลกชัน

```python
def add(self, cell_with_series_name, type):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell) | เซลล์ที่มีชื่อชุดข้อมูล |
| type | [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype) | ชนิดของชุดข้อมูลที่ตั้งค่า |

### หมายเหตุ
หากชุดข้อมูลแผนภูมิที่สร้างจากเซลล์เดียวกันมีอยู่แล้วในคอลเลกชัน เมธอดจะไม่เพิ่มอะไรและส่งคืนดัชนีของมัน

## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
สร้างชุดข้อมูลแผนภูมิใหม่จาก [`ChartCellCollection`](/slides/python-net/th/aspose.slides.charts/chartcellcollection) และเพิ่มลงในคอลเลกชัน

### คืนค่า
ชุดข้อมูลแผนภูมิที่เพิ่มแล้ว หรือชุดข้อมูลที่มีอยู่แล้วในคอลเลกชัน

```python
def add(self, cells_with_series_name, type):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/th/aspose.slides.charts/ichartcellcollection) | เซลล์ที่มีชื่อชุดข้อมูล |
| type | [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype) | ชนิดของชุดข้อมูลที่ตั้งค่า |

### หมายเหตุ
หากชุดข้อมูลแผนภูมิที่สร้างจากเซลล์เดียวกันมีอยู่แล้วในคอลเลกชัน เมธอดจะไม่เพิ่มอะไรและส่งคืนดัชนีของมัน

## add(self, name, type) {#str-charttype}
สร้างชุดข้อมูลแผนภูมิใหม่จากค่าและเพิ่มลงในคอลเลกชัน

### คืนค่า
ชุดข้อมูลแผนภูมิที่เพิ่มแล้ว

```python
def add(self, name, type):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| name | **str** | ชื่อชุดข้อมูล |
| type | [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype) | ชนิดของชุดข้อมูลที่ตั้งค่า |

### ดูเพิ่มเติม
* คลาส [`ChartCellCollection`](/slides/python-net/th/aspose.slides.charts/chartcellcollection)
* คลาส [`ChartDataCell`](/slides/python-net/th/aspose.slides.charts/chartdatacell)
* คลาส [`ChartSeriesCollection`](/slides/python-net/th/aspose.slides.charts/chartseriescollection)
* enumeration [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype)
* คลาส [`IChartCellCollection`](/slides/python-net/th/aspose.slides.charts/ichartcellcollection)
* คลาส [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell)
* คลาส [`IChartSeries`](/slides/python-net/th/aspose.slides.charts/ichartseries)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)