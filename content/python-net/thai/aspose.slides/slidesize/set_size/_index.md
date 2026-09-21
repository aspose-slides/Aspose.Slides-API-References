---
title: set_size method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
กำหนดขนาดสไลด์ตามประเภทและปรับสเกลเนื้อหาเดิม

```python
def set_size(self, type, scale_type):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/th/aspose.slides/slidesizetype) | ขนาดสไลด์ที่กำหนดไว้ล่วงหน้าเพื่อใช้ |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/th/aspose.slides/slidesizescaletype) | โหมดการปรับสเกลเนื้อหาเพื่อใช้ |

### หมายเหตุ

การกำหนดค่าใด ๆ ที่ไม่ใช่ [`SlideSizeType.CUSTOM`](/slides/python-net/th/aspose.slides/slidesizetype/CUSTOM) จะปรับ [`SlideSize.size`](/slides/python-net/th/aspose.slides/slidesize/size) ตามประเภทที่เลือก ในขณะที่รักษา [`SlideSize.orientation`](/slides/python-net/th/aspose.slides/slidesize/orientation) ไว้

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
กำหนดมิติสไลด์โดยตรงและปรับสเกลเนื้อหาเดิม

```python
def set_size(self, width, height, scale_type):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| width | **float** | ความกว้างสไลด์ใหม่เป็นจุด |
| height | **float** | ความสูงสไลด์ใหม่เป็นจุด |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/th/aspose.slides/slidesizescaletype) | โหมดการปรับสเกลเนื้อหาเพื่อใช้ |

### หมายเหตุ

การรีเซ็ตนี้จะทำให้คุณสมบัติ [`SlideSize.type`](/slides/python-net/th/aspose.slides/slidesize/type) กลับเป็น [`SlideSizeType.CUSTOM`](/slides/python-net/th/aspose.slides/slidesizetype/CUSTOM) และตั้งค่า [`SlideSize.orientation`](/slides/python-net/th/aspose.slides/slidesize/orientation)

### ดูเพิ่มเติม
* คลาส [`SlideSize`](/slides/python-net/th/aspose.slides/slidesize)
* การนับ [`SlideSizeScaleType`](/slides/python-net/th/aspose.slides/slidesizescaletype)
* การนับ [`SlideSizeType`](/slides/python-net/th/aspose.slides/slidesizetype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)