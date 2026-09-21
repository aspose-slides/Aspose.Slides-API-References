---
title: get_images method
second_title: อ้างอิง API Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
คืนออบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอ

### คืนค่า
ออบเจ็กต์ Bitmap.

```python
def get_images(self, options):
    ...
```

| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions) | ตัวเลือกการเรนเดอร์. |

## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
คืนออบเจ็กต์ Thumbnail Bitmap สำหรับสไลด์ที่ระบุของงานนำเสนอ

### คืนค่า
ออบเจ็กต์ Bitmap.

```python
def get_images(self, options, slides):
    ...
```

| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions) | ตัวเลือกการเรนเดอร์. |
| slides | **List[int]** | Array ที่มีตำแหน่งของสไลด์ เริ่มจาก 1. |

## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
คืนออบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอที่มีขนาดที่ระบุ

### คืนค่า
ออบเจ็กต์ Bitmap.

```python
def get_images(self, options, image_size):
    ...
```

| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions) | ตัวเลือกการเรนเดอร์. |
| image_size | **aspose.slides.Size** | ขนาดของภาพที่ต้องการสร้าง. |

## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
คืนออบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอที่ปรับสัดส่วนตามกำหนด

### คืนค่า
ออบเจ็กต์ Bitmap.

```python
def get_images(self, options, scale_x, scale_y):
    ...
```

| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions) | ตัวเลือกการเรนเดอร์. |
| scale_x | **float** | ค่าที่ใช้ในการขยาย Thumbnail ในแนวแกน x. |
| scale_y | **float** | ค่าที่ใช้ในการขยาย Thumbnail ในแนวแกน y. |

## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
คืนออบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอที่มีขนาดที่ระบุ

### คืนค่า
ออบเจ็กต์ Bitmap.

```python
def get_images(self, options, slides, image_size):
    ...
```

| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions) | ตัวเลือกการเรนเดอร์. |
| slides | **List[int]** | Array ที่มีตำแหน่งของสไลด์ เริ่มจาก 1. |
| image_size | **aspose.slides.Size** | ขนาดของภาพที่ต้องการสร้าง. |

## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
คืนออบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอที่ปรับสัดส่วนตามกำหนด

### คืนค่า
ออบเจ็กต์ Bitmap.

```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```

| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions) | ตัวเลือกการเรนเดอร์. |
| slides | **List[int]** | Array ที่มีตำแหน่งของสไลด์ เริ่มจาก 1. |
| scale_x | **float** | ค่าที่ใช้ในการขยาย Thumbnail ในแนวแกน x. |
| scale_y | **float** | ค่าที่ใช้ในการขยาย Thumbnail ในแนวแกน y. |

### ดูเพิ่มเติม
* คลาส [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation)
* คลาส [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)