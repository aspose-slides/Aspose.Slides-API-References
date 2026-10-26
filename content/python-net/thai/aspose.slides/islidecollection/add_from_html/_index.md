---
title: add_from_html method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/islidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน

### Returns
สไลด์ที่เพิ่ม



```python
def add_from_html(self, html_text):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| html_text | **str** | HTML ที่จะเพิ่ม. |


## add_from_html(self, html_stream) {#iorawiobase}
สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน

### Returns
สไลด์ที่เพิ่ม



```python
def add_from_html(self, html_stream):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | อ็อบเจ็กต์ Stream ที่จะใช้เป็นแหล่งของไฟล์ HTML. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน

### Returns
สไลด์ที่เพิ่ม.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| html_text | **str** | HTML ที่จะเพิ่ม. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/th/aspose.slides.importing/iexternalresourceresolver) | อ็อบเจ็กต์ callback ที่ใช้เพื่อดึงอ็อบเจ็กต์ภายนอก หากพารามิเตอร์นี้เป็น None จะละเว้นอ็อบเจ็กต์ภายนอกทั้งหมด. |
| uri | **str** | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์เชิงสัมพันธ์. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน

### Returns
สไลด์ที่เพิ่ม.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | อ็อบเจ็กต์ Stream ที่จะใช้เป็นแหล่งของไฟล์ HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/th/aspose.slides.importing/iexternalresourceresolver) | อ็อบเจ็กต์ callback ที่ใช้เพื่อดึงอ็อบเจ็กต์ภายนอก หากพารามิเตอร์นี้เป็น None จะละเว้นอ็อบเจ็กต์ภายนอกทั้งหมด. |
| uri | **str** | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์เชิงสัมพันธ์. |



### ดูเพิ่มเติม
* คลาส [`IExternalResourceResolver`](/slides/python-net/th/aspose.slides.importing/iexternalresourceresolver)
* คลาส [`ISlideCollection`](/slides/python-net/th/aspose.slides/islidecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)