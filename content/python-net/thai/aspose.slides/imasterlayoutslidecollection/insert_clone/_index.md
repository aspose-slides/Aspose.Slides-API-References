---
title: insert_clone method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API อ้างอิง
description: 
type: docs
url: /th/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
แทรกสำเนาของสไลด์เลย์เอาต์ที่ระบุไปยังตำแหน่งที่กำหนดในคอลเลกชัน

### คืนค่า
สไลด์ที่แทรก

```python
def insert_clone(self, index, source_layout):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีของสไลด์ใหม่ |
| source_layout | [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide) | สไลด์ที่จะทำสำเนา |

### หมายเหตุ
เลย์เอาต์ใหม่จะเชื่อมโยงกับสไลด์มาสเตอร์หลักสำหรับคอลเลกชันสไลด์เลย์เอาต์นี้ ดังนั้นจึงเป็นการทำงานที่คล้ายกับคัดลอก/วางโดยใช้ตัวเลือก "Use Destination Theme" ใน PowerPoint

### ดูเพิ่มเติม
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`IMasterLayoutSlideCollection`](/slides/python-net/th/aspose.slides/imasterlayoutslidecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)