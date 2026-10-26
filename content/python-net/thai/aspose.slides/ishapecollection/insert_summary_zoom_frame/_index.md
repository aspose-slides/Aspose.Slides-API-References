---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/ishapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
สร้าง Summary Zoom frame ใหม่และแทรกลงในคอลเลกชันของ shape ที่ตำแหน่งดัชนีที่ระบุ

### ค่าที่ส่งกลับ

[`ISummaryZoomFrame`](/slides/python-net/th/aspose.slides/isummaryzoomframe) ที่สร้างใหม่

```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ที่ใช้ในการแทรก Summary Zoom frame |
| x | **float** | พิกัด x ของ Summary Zoom frame ใหม่ หน่วยเป็นจุด |
| y | **float** | พิกัด y ของ Summary Zoom frame ใหม่ หน่วยเป็นจุด |
| width | **float** | ความกว้างของ Summary Zoom frame ใหม่ หน่วยเป็นจุด |
| height | **float** | ความสูงของ Summary Zoom frame ใหม่ หน่วยเป็นจุด |

### หมายเหตุ

เมธอดนี้สร้าง Summary Zoom frame ที่รวบรวมลิงก์สรุปสำหรับทุกส่วนใน presentation

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | เกิดขึ้นหาก presentation ไม่มีส่วนใด หรือสไลด์เป้าหมายไม่ได้อยู่ในส่วนใดส่วนหนึ่ง |

### ดูเพิ่มเติม
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* คลาส [`ISummaryZoomFrame`](/slides/python-net/th/aspose.slides/isummaryzoomframe)
* คลาส [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)