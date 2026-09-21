---
title: save method
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นชุดไฟล์ที่แสดงรูปแบบ XAML markup.


```python
def save(self, options):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/th/aspose.slides.export.xaml/ixamloptions) | ตัวเลือกรูปแบบ XAML |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นไฟล์ในรูปแบบที่ระบุ


```python
def save(self, fname, format):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| fname | **str** | เส้นทางไปยังไฟล์ที่สร้าง |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) | รูปแบบของข้อมูลที่ส่งออก |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นสตรีมในรูปแบบที่ระบุ


```python
def save(self, stream, format):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมเอาต์พุต |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) | รูปแบบของข้อมูลที่ส่งออก |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}


```python
def save(self, fname, format, options):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/th/aspose.slides.export/isaveoptions) |  |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นสตรีมในรูปแบบที่ระบุพร้อมตัวเลือกเพิ่มเติม


```python
def save(self, stream, format, options):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมเอาต์พุต |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) | รูปแบบของข้อมูลที่ส่งออก |
| options | [`ISaveOptions`](/slides/python-net/th/aspose.slides.export/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | หากคุณพยายามบันทึกไฟล์ที่เข้ารหัสใน <br/>            none Office 2007-2010 format |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
บันทึกสไลด์ที่ระบุของการนำเสนอเป็นไฟล์ในรูปแบบที่ระบุพร้อมการคงเลขหน้า


```python
def save(self, fname, slides, format):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| fname | **str** | เส้นทางไปยังไฟล์ที่สร้าง |
| slides | **List[int]** | อาเรย์ที่บอกตำแหน่งสไลด์ เริ่มต้นจาก 1 |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) | รูปแบบของข้อมูลที่ส่งออก |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | เมื่อพารามิเตอร์ stream หรือ slides มีค่าเป็น None |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าไม่ถูกต้อง |
| **RuntimeError(Proxy error(InvalidOperationException))** | เมื่อใช้ SaveFormat ที่ไม่รองรับ เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
บันทึกสไลด์ที่ระบุของการนำเสนอเป็นสตรีมในรูปแบบที่ระบุพร้อมการคงเลขหน้า


```python
def save(self, stream, slides, format):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมเอาต์พุต |
| slides | **List[int]** | อาเรย์ที่บอกตำแหน่งสไลด์ เริ่มต้นจาก 1 |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) | รูปแบบของข้อมูลที่ส่งออก |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
บันทึกสไลด์ที่ระบุของการนำเสนอเป็นไฟล์ในรูปแบบที่ระบุพร้อมการคงเลขหน้าและตัวเลือกเพิ่มเติม


```python
def save(self, fname, slides, format, options):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| fname | **str** | เส้นทางไปยังไฟล์ที่สร้าง |
| slides | **List[int]** | อาเรย์ที่บอกตำแหน่งสไลด์ เริ่มต้นจาก 1 |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) | รูปแบบของข้อมูลที่ส่งออก |
| options | [`ISaveOptions`](/slides/python-net/th/aspose.slides.export/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
บันทึกสไลด์ที่ระบุของการนำเสนอเป็นสตรีมในรูปแบบที่ระบุพร้อมการคงเลขหน้าและตัวเลือกเพิ่มเติม


```python
def save(self, stream, slides, format, options):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมเอาต์พุต |
| slides | **List[int]** | อาเรย์ที่บอกตำแหน่งสไลด์ เริ่มต้นจาก 1 |
| format | [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat) | รูปแบบของข้อมูลที่ส่งออก |
| options | [`ISaveOptions`](/slides/python-net/th/aspose.slides.export/isaveoptions) | ตัวเลือกรูปแบบเพิ่มเติม |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | เมื่อพารามิเตอร์ stream หรือ slides มีค่าเป็น None |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | เมื่อพารามิเตอร์ slides มีหมายเลขหน้าไม่ถูกต้อง |
| **RuntimeError(Proxy error(InvalidOperationException))** | เมื่อใช้ SaveFormat ที่ไม่รองรับ เช่น PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP |



### ดูเพิ่มเติม
* คลาส [`ISaveOptions`](/slides/python-net/th/aspose.slides.export/isaveoptions)
* คลาส [`IXamlOptions`](/slides/python-net/th/aspose.slides.export.xaml/ixamloptions)
* คลาส [`Presentation`](/slides/python-net/th/aspose.slides/presentation)
* enumeration [`SaveFormat`](/slides/python-net/th/aspose.slides.export/saveformat)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)