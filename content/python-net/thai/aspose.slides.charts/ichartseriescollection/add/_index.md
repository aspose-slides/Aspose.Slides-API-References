---
title: add method
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
สร้างซีรีส์แผนภูมิใหม่และเพิ่มลงในคอลเลกชัน

### ค่าที่ส่งกลับ

ซีรีส์แผนภูมิใหม่



```python
def add(self, type):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype) | ประเภทของซีรีส์ |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
สร้างซีรีส์แผนภูมิใหม่จาก [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell) และเพิ่มลงในคอลเลกชัน

### ค่าที่ส่งกลับ

ซีรีส์แผนภูมิที่เพิ่มหรือซีรีส์ที่มีอยู่แล้วในคอลเลกชัน



```python
def add(self, cell_with_series_name, type):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell) | เซลล์ที่มีชื่อซีรีส์ |
| type | [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype) | ประเภทที่ตั้งค่าให้กับซีรีส์ |

### หมายเหตุ

หากซีรีส์แผนภูมิที่สร้างจากเซลเดียวกันมีอยู่แล้วในคอลเลกชัน
            วิธีจะไม่เพิ่มอะไรและจะคืนค่าตำแหน่งดัชนีของมัน


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
สร้างซีรีส์แผนภูมิใหม่จาก [`IChartCellCollection`](/slides/python-net/th/aspose.slides.charts/ichartcellcollection) และเพิ่มลงในคอลเลกชัน

### ค่าที่ส่งกลับ

ซีรีส์แผนภูมิที่เพิ่มหรือซีรีส์ที่มีอยู่แล้วในคอลเลกชัน



```python
def add(self, cells_with_series_name, type):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/th/aspose.slides.charts/ichartcellcollection) | เซลล์ที่มีชื่อซีรีส์ |
| type | [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype) | ประเภทที่ตั้งค่าให้กับซีรีส์ |

### หมายเหตุ

หากซีรีส์แผนภูมิที่สร้างจากเซลเดียวกันมีอยู่แล้วในคอลเลกชัน
            วิธีจะไม่เพิ่มอะไรและจะคืนค่าตำแหน่งดัชนีของมัน


## add(self, name, type) {#str-charttype}
สร้างซีรีส์แผนภูมิใหม่จากค่าและเพิ่มลงในคอลเลกชัน

### ค่าที่ส่งกลับ

ซีรีส์แผนภูมิที่เพิ่ม



```python
def add(self, name, type):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| name | **str** | ชื่อซีรีส์ |
| type | [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype) | ประเภทที่ตั้งค่าให้กับซีรีส์ |



### ดูเพิ่มเติม
* enumeration [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype)
* คลาส [`IChartCellCollection`](/slides/python-net/th/aspose.slides.charts/ichartcellcollection)
* คลาส [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell)
* คลาส [`IChartSeries`](/slides/python-net/th/aspose.slides.charts/ichartseries)
* คลาส [`IChartSeriesCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriescollection)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)