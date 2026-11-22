---
title: categories property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/ichartdata/categories/
weight: 80
---
## categories คุณสมบัติ
ดึงค่าหมวดหมู่หลัก (หรือทั้งหมวดหมู่หลักและรองหาก [`IChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/use_secondary_categories) คุณสมบัติเป็น false). อ่านอย่างเดียว [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection).

### หมายเหตุ
หาก [`IChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/use_secondary_categories) คุณสมบัติเป็น false แล้ว [`IChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/secondary_categories) คุณสมบัติจะคืนค่า None และข้อมูลใน [`IChartData.categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/categories) คุณสมบัติจะถูกใช้ทั้งสำหรับชุดหลักและชุดรอง. หาก [`IChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/use_secondary_categories) คุณสมบัติเป็น true แล้วข้อมูลใน [`IChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/secondary_categories) คุณสมบัติจะถูกใช้สำหรับชุดรองและข้อมูลใน [`IChartData.categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/categories) คุณสมบัติจะถูกใช้สำหรับชุดหลัก.

### คำนิยาม:
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