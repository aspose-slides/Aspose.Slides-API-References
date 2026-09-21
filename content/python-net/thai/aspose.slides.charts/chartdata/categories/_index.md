---
title: categories property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/chartdata/categories/
weight: 70
---
## categories คุณสมบัติ
รับค่า categories หลัก (หรือทั้ง categories หลักและรองถ้า [`ChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/use_secondary_categories) คุณสมบัติเป็น false). อ่านอย่างเดียว [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection).

### หมายเหตุ

ถ้า [`ChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/use_secondary_categories) คุณสมบัติเป็น false แล้ว [`ChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/secondary_categories) คุณสมบัติกลับคืนค่า None และข้อมูลใน [`ChartData.categories`](/slides/python-net/th/aspose.slides.charts/chartdata/categories) คุณสมบัตินี้ถูกใช้ทั้งสำหรับชุดข้อมูลหลักและชุดข้อมูลรอง. ถ้า [`ChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/use_secondary_categories) คุณสมบัติเป็น true แล้วข้อมูลใน [`ChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/chartdata/secondary_categories) คุณสมบัติถูกใช้สำหรับชุดข้อมูลรองและข้อมูลใน [`ChartData.categories`](/slides/python-net/th/aspose.slides.charts/chartdata/categories) คุณสมบัติถูกใช้สำหรับชุดข้อมูลหลัก.

### คำนิยาม:
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