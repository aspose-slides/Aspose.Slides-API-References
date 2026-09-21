---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
สร้าง Summary Zoom frame ใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ

### คืนค่า
[`ISummaryZoomFrame`](/slides/python-net/th/aspose.slides/isummaryzoomframe) ที่สร้างใหม่

```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ซึ่งใช้ในการแทรก Summary Zoom frame |
| x | **float** | พิกัด x ของ Summary Zoom frame ใหม่ หน่วยเป็นจุด |
| y | **float** | พิกัด y ของ Summary Zoom frame ใหม่ หน่วยเป็นจุด |
| width | **float** | ความกว้างของ Summary Zoom frame ใหม่ หน่วยเป็นจุด |
| height | **float** | ความสูงของ Summary Zoom frame ใหม่ หน่วยเป็นจุด |

### หมายเหตุ
เมธอดนี้สร้าง Summary Zoom frame ที่รวบรวมลิงก์สรุปสำหรับทุกส่วนในงานนำเสนอ

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | จะเกิดขึ้นหากงานนำเสนอไม่มีส่วนใด หรือถ้าสไลด์เป้าหมายไม่ได้เป็นส่วนของใด |

### ดูเพิ่มเติม
* คลาส [`ISummaryZoomFrame`](/slides/python-net/th/aspose.slides/isummaryzoomframe)
* คลาส [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* คลาส [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)