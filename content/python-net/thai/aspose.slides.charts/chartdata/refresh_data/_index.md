---
title: refresh_data method
second_title: อ้างอิง API Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
รีเฟรชข้อมูลแผนภูมิโดยโหลดซ้ำจากสมุดงานต้นทาง.

```python
def refresh_data(self):
    ...
```

### หมายเหตุ

หากแผนภูมิใช้สมุดงานภายนอก สมุดงานจะต้องสามารถเข้าถึงได้ในขณะที่เรียกใช้.

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | เกิดข้อผิดพลาดเมื่อรูปแบบของสมุดงานไม่รองรับ, หรือเมื่อ [`ChartData.data_source_type`](/slides/python-net/th/aspose.slides.charts/chartdata/data_source_type) เป็น<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/th/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) และสมุดงานภายนอกไม่สามารถเข้าถึงหรือโหลดได้. |

### ดูเพิ่มเติม
* คลาส [`ChartData`](/slides/python-net/th/aspose.slides.charts/chartdata)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)