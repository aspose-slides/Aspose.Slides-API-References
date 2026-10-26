---
title: save method
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นชุดไฟล์ที่เป็นตัวแทนของมาร์คอัป XAML


```python
def save(self, options):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/th/aspose.slides.export.xaml/ixamloptions) | ตัวเลือกรูปแบบ XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
บันทึกสไลด์ทั้งหมดของการนำเสนอลงในไฟล์โดยใช้รูปแบบที่ระบุ


```python
def save(self, fname, format):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| fname | **str** | เส้นทางไปยังไฟล์ที่สร้างขึ้น |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) | รูปแบบของข้อมูลที่ส่งออก |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
บันทึกสไลด์ทั้งหมดของการนำเสนอลงในสตรีมโดยใช้รูปแบบที่ระบุ


```python
def save(self, stream, format):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมผลลัพธ์ |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) | รูปแบบของข้อมูลที่ส่งออก |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
บันทึกสไลด์ทั้งหมดของการนำเสนอลงในไฟล์โดยใช้รูปแบบที่ระบุและตัวเลือกเพิ่มเติม


```python
def save(self, fname, format, options):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| fname | **str** | เส้นทางไปยังไฟล์ที่สร้างขึ้น |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) | รูปแบบของข้อมูลที่ส่งออก |
| options | [`ISaveOptions`](/slides/python-net/th/aspose.slides.export/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
บันทึกสไลด์ทั้งหมดของการนำเสนอลงในสตรีมโดยใช้รูปแบบที่ระบุและตัวเลือกเพิ่มเติม


```python
def save(self, stream, format, options):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมผลลัพธ์ |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) | รูปแบบของข้อมูลที่ส่งออก |
| options | [`ISaveOptions`](/slides/python-net/th/aspose.slides.export/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม |

### ข้อยกเว้น

| Exception | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | หากคุณพยายามบันทึกไฟล์ที่เข้ารหัสใน <br/>รูปแบบที่ไม่ใช่ Office 2007-2010 |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
บันทึกสไลด์ที่ระบุของการนำเสนอลงในไฟล์โดยใช้รูปแบบที่ระบุ


```python
def save(self, fname, slides, format):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| fname | **str** | เส้นทางไปยังไฟล์ที่สร้างขึ้น |
| slides | **List[int]** | อาเรย์ของตำแหน่งสไลด์ เริ่มจาก 1 |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) | รูปแบบของข้อมูลที่ส่งออก |

### ข้อยกเว้น

| Exception | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | เมื่อพารามิเตอร์ stream หรือ slides มีค่าเป็น None |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าไม่ถูกต้อง |
| **RuntimeError(Proxy error(InvalidOperationException))** | เมื่อใช้ SaveFormat ที่ไม่รองรับ เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
บันทึกสไลด์ที่ระบุของการนำเสนอลงในสตรีมโดยใช้รูปแบบที่ระบุ


```python
def save(self, stream, slides, format):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมผลลัพธ์ |
| slides | **List[int]** | อาเรย์ของตำแหน่งสไลด์ เริ่มจาก 1 |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) | รูปแบบของข้อมูลที่ส่งออก |

### ข้อยกเว้น

| Exception | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | เมื่อพารามิเตอร์ stream หรือ slides มีค่าเป็น None |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าไม่ถูกต้อง |
| **RuntimeError(Proxy error(InvalidOperationException))** | เมื่อใช้ SaveFormat ที่ไม่รองรับ เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
บันทึกสไลด์ที่ระบุของการนำเสนอลงในไฟล์โดยใช้รูปแบบที่ระบุ


```python
def save(self, fname, slides, format, options):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| fname | **str** | เส้นทางไปยังไฟล์ที่สร้างขึ้น |
| slides | **List[int]** | อาเรย์ของตำแหน่งสไลด์ เริ่มจาก 1 |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) | รูปแบบของข้อมูลที่ส่งออก |
| options | [`ISaveOptions`](/slides/python-net/th/aspose.slides.export/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม |

### ข้อยกเว้น

| Exception | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | เมื่อพารามิเตอร์ stream หรือ slides มีค่าเป็น None |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าไม่ถูกต้อง |
| **RuntimeError(Proxy error(InvalidOperationException))** | เมื่อใช้ SaveFormat ที่ไม่รองรับ เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
บันทึกสไลด์ที่ระบุของการนำเสนอลงในสตรีมโดยใช้รูปแบบที่ระบุ


```python
def save(self, stream, slides, format, options):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมผลลัพธ์ |
| slides | **List[int]** | อาเรย์ของตำแหน่งสไลด์ เริ่มจาก 1 |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) | รูปแบบของข้อมูลที่ส่งออก |
| options | [`ISaveOptions`](/slides/python-net/th/aspose.slides.export/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม |

### ข้อยกเว้น

| Exception | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | เมื่อพารามิเตอร์ stream หรือ slides มีค่าเป็น None |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าไม่ถูกต้อง |
| **RuntimeError(Proxy error(InvalidOperationException))** | เมื่อใช้ SaveFormat ที่ไม่รองรับ เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |



### ดูเพิ่มเติม
* คลาส [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation)
* คลาส [`ISaveOptions`](/slides/python-net/th/aspose.slides.export/isaveoptions)
* คลาส [`IXamlOptions`](/slides/python-net/th/aspose.slides.export.xaml/ixamloptions)
* การนับ [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)