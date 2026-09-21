---
title: categories property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## categories คุณสมบัติ
รับค่าประเภทหลัก (หรือประเภทหลักและรองถ้า [`IChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/use_secondary_categories) คุณสมบัติเป็น false). อ่านอย่างเดียว [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection).

### หมายเหตุ

ถ้า [`IChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/use_secondary_categories) คุณสมบัติเป็น false แล้ว [`IChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/secondary_categories) คุณสมบัติจะคืนค่า None และข้อมูลใน [`IChartData.categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/categories) คุณสมบัตินี้จะใช้ทั้งสำหรับซีรีส์หลักและซีรีส์รอง.
ถ้า [`IChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/use_secondary_categories) คุณสมบัติเป็น true แล้วข้อมูลใน [`IChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/secondary_categories) คุณสมบัติจะใช้สำหรับซีรีส์รองและข้อมูลใน [`IChartData.categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/categories) คุณสมบัตินี้จะใช้สำหรับซีรีส์หลัก.

### นิยาม:
```python
@property
def categories(self):
    ...
```

### ดูเพิ่มเติม
* คลาส [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection)
* คลาส [`IChartData`](/slides/python-net/th/aspose.slides.charts/ichartdata)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)