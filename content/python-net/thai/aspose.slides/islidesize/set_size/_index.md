---
title: set_size method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API เอกสารอ้างอิง
description: 
type: docs
url: /th/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
กำหนดขนาดสไลด์โดย type และปรับสเกลเนื้อหาที่มีอยู่


```python
def set_size(self, type, scale_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/th/aspose.slides/slidesizetype) | ขนาดสไลด์ที่กำหนดไว้ล่วงหน้าเพื่อใช้งาน |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/th/aspose.slides/slidesizescaletype) | โหมดการปรับสเกลเนื้อหาที่จะใช้ |

### Remarks

การกำหนดค่าที่แตกต่างจาก [`SlideSizeType.CUSTOM`](/slides/python-net/th/aspose.slides/slidesizetype/CUSTOM) จะปรับ [`ISlideSize.size`](/slides/python-net/th/aspose.slides/islidesize/size) ตามประเภทที่เลือกในขณะที่คงไว้ [`ISlideSize.orientation`](/slides/python-net/th/aspose.slides/islidesize/orientation).


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
กำหนดมิติของสไลด์อย่างชัดเจนและปรับสเกลเนื้อหาที่มีอยู่


```python
def set_size(self, width, height, scale_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| width | **float** | ความกว้างสไลด์ใหม่, หน่วยเป็นพอยท์ |
| height | **float** | ความสูงสไลด์ใหม่, หน่วยเป็นพอยท์ |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/th/aspose.slides/slidesizescaletype) | โหมดการปรับสเกลเนื้อหาที่จะใช้ |

### Remarks

สิ่งนี้จะรีเซ็ตคุณสมบัติ [`ISlideSize.type`](/slides/python-net/th/aspose.slides/islidesize/type) เป็น [`SlideSizeType.CUSTOM`](/slides/python-net/th/aspose.slides/slidesizetype/CUSTOM) และตั้งค่า [`ISlideSize.orientation`](/slides/python-net/th/aspose.slides/islidesize/orientation).



### ดูเพิ่มเติม
* คลาส [`ISlideSize`](/slides/python-net/th/aspose.slides/islidesize)
* enumeration [`SlideSizeScaleType`](/slides/python-net/th/aspose.slides/slidesizescaletype)
* enumeration [`SlideSizeType`](/slides/python-net/th/aspose.slides/slidesizetype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)