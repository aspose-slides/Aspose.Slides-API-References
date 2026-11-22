---
title: categories property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/chartdata/categories/
weight: 80
---
## categories คุณสมบัติ
รับค่าประเภทหลัก (หรือทั้งประเภทหลักและประเภทรอง 
            ถ้า [`ChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/use_secondary_categories) คุณสมบัติเป็น false).
            อ่านอย่างเดียว [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection).

### หมายเหตุ
ถ้า [`ChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/use_secondary_categories) คุณสมบัติเป็น false แล้ว [`ChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/secondary_categories) 
            คุณสมบัติคืนค่า None และข้อมูลใน [`ChartData.categories`](/slides/python-net/th/aspose.slides.charts/chartdata/categories) คุณสมบัตินี้ถูกใช้ทั้งสำหรับประเภทหลัก 
            และประเภทรอง.
            ถ้า [`ChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/use_secondary_categories) คุณสมบัติเป็น true แล้วข้อมูลใน [`ChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/secondary_categories) 
            คุณสมบัติจะใช้สำหรับประเภทรองและข้อมูลใน [`ChartData.categories`](/slides/python-net/th/aspose.slides.charts/chartdata/categories) คุณสมบัตินี้จะใช้ 
            สำหรับประเภทหลัก.

### คำจำกัดความ:
```python
@property
def categories(self):
    ...
```

### ดูเพิ่มเติม
* คลาส [`ChartData`](/slides/python-net/th/aspose.slides.charts/chartdata)
* คลาส [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)