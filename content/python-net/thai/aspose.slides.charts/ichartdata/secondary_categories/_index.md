---
title: secondary_categories property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories คุณสมบัติ
Gets the secondary categories if [`IChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/use_secondary_categories) property is true.
            อ่านอย่างเดียว [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection).

### หมายเหตุ

หาก property [`IChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/use_secondary_categories) เป็น false แล้ว property [`IChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/secondary_categories) นี้ 
            property จะคืนค่า None และข้อมูลใน [`IChartData.categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/categories) property จะถูกใช้ทั้งสำหรับ primary 
            และ secondary series.
หาก property [`IChartData.use_secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/use_secondary_categories) เป็น true แล้ว data ใน 
            property [`IChartData.secondary_categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/secondary_categories) นี้จะถูกใช้สำหรับ secondary series และ data 
            ใน [`IChartData.categories`](/slides/python-net/th/aspose.slides.charts/ichartdata/categories) property จะถูกใช้สำหรับ primary series.

### คำนิยาม:
```python
@property
def secondary_categories(self):
    ...
```

### ดูเพิ่มเติม
* คลาส [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection)
* คลาส [`IChartData`](/slides/python-net/th/aspose.slides.charts/ichartdata)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)