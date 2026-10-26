---
title: add_summary_zoom_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
สร้าง Summary Zoom frame ใหม่และเพิ่มลงในตอนท้ายของคอลเลกชันรูปทรง

### คืนค่า

[`ISummaryZoomFrame`](/slides/python-net/th/aspose.slides/isummaryzoomframe) ที่สร้างใหม่



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด x ของ Summary Zoom frame ใหม่, หน่วยเป็นพอยท์ |
| y | **float** | พิกัด y ของ Summary Zoom frame ใหม่, หน่วยเป็นพอยท์ |
| width | **float** | ความกว้างของ Summary Zoom frame ใหม่, หน่วยเป็นพอยท์ |
| height | **float** | ความสูงของ Summary Zoom frame ใหม่, หน่วยเป็นพอยท์ |

### หมายเหตุ

เมธอดนี้สร้าง Summary Zoom frame ที่รวมลิงก์สรุปสำหรับทุกส่วนในงานนำเสนอ

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | จะถูกโยนเมื่อไม่มีส่วนในงานนำเสนอ หรือเมื่อสไลด์เป้าหมายไม่ได้อยู่ในส่วนใดส่วนหนึ่ง |

### ดูเพิ่มเติม
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* คลาส [`ISummaryZoomFrame`](/slides/python-net/th/aspose.slides/isummaryzoomframe)
* คลาส [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)