---
title: refresh_data method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
รีเฟรชข้อมูลแผนภูมิโดยโหลดใหม่จากสมุดงานต้นฉบับ


```python
def refresh_data(self):
    ...
```


### หมายเหตุ

หากแผนภูมิใช้สมุดงานภายนอก สมุดงานต้องสามารถเข้าถึงได้ในขณะที่เรียกใช้

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | จะถูกโยนเมื่อรูปแบบสมุดงานไม่รองรับ หรือเมื่อ [`IChartData.data_source_type`](/slides/python-net/th/aspose.slides.charts/ichartdata/data_source_type) เป็น<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/th/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) และไม่สามารถเข้าถึงหรือโหลดสมุดงานภายนอกได้. |



### ดูเพิ่มเติม
* คลาส [`IChartData`](/slides/python-net/th/aspose.slides.charts/ichartdata)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)