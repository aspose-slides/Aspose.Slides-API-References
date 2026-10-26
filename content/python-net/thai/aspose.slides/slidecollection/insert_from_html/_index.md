---
title: insert_from_html method
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

### คืนค่า

สไลด์ที่เพิ่ม



```python
def insert_from_html(self, index, html_text):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ตำแหน่งที่จะใส่ |
| html_text | **str** | HTML ที่จะเพิ่ม |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

### คืนค่า

สไลด์ที่เพิ่ม



```python
def insert_from_html(self, index, html_stream):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ตำแหน่งที่จะใส่ |
| html_stream | **io.RawIOBase** | อ็อบเจกต์ Stream ที่จะใช้เป็นแหล่งไฟล์ HTML |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

### คืนค่า

สไลด์ที่เพิ่ม



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ตำแหน่งที่จะใส่ |
| html_text | **str** | HTML ที่จะเพิ่ม |
| use_slide_with_index_as_start | **bool** | ธงนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ.<br/><br/>            หาก **true** , การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ.<br/><br/>            หาก **false** , ข้อมูลจะถูกเพิ่มในสไลด์ที่สร้างขึ้น |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

### คืนค่า

สไลด์ที่เพิ่ม



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ตำแหน่งที่จะใส่ |
| html_stream | **io.RawIOBase** | อ็อบเจกต์ Stream ที่จะใช้เป็นแหล่งไฟล์ HTML |
| use_slide_with_index_as_start | **bool** | ธงนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ.<br/><br/>            หาก **true** , การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ.<br/><br/>            หาก **false** , ข้อมูลจะถูกเพิ่มในสไลด์ที่สร้างขึ้น |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

### คืนค่า

สไลด์ที่เพิ่ม.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ตำแหน่งที่จะใส่ |
| html_text | **str** | HTML ที่จะเพิ่ม |
| resolver | [`IExternalResourceResolver`](/slides/python-net/th/aspose.slides.importing/iexternalresourceresolver) | วัตถุ callback ที่ใช้ดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น None จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด |
| uri | **str** | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบสัมพันธ์ |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

### คืนค่า

สไลด์ที่เพิ่ม.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ตำแหน่งที่จะใส่ |
| html_stream | **io.RawIOBase** | อ็อบเจกต์ Stream ที่จะใช้เป็นแหล่งไฟล์ HTML |
| resolver | [`IExternalResourceResolver`](/slides/python-net/th/aspose.slides.importing/iexternalresourceresolver) | วัตถุ callback ที่ใช้ดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น None จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด |
| uri | **str** | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบสัมพันธ์ |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

### คืนค่า

สไลด์ที่เพิ่ม.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ตำแหน่งที่จะใส่ |
| html_text | **str** | HTML ที่จะเพิ่ม |
| resolver | [`IExternalResourceResolver`](/slides/python-net/th/aspose.slides.importing/iexternalresourceresolver) | วัตถุ callback ที่ใช้ดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น None จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด |
| uri | **str** | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบสัมพันธ์ |
| use_slide_with_index_as_start | **bool** | ธงนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ.<br/><br/>            หาก **true** , การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ.<br/><br/>            หาก **false** , ข้อมูลจะถูกเพิ่มในสไลด์ที่สร้างขึ้น |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

### คืนค่า

สไลด์ที่เพิ่ม.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ตำแหน่งที่จะใส่ |
| html_stream | **io.RawIOBase** | อ็อบเจกต์ Stream ที่จะใช้เป็นแหล่งไฟล์ HTML |
| resolver | [`IExternalResourceResolver`](/slides/python-net/th/aspose.slides.importing/iexternalresourceresolver) | วัตถุ callback ที่ใช้ดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น None จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด |
| uri | **str** | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบสัมพันธ์ |
| use_slide_with_index_as_start | **bool** | ธงนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ.<br/><br/>            หาก **true** , การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ.<br/><br/>            หาก **false** , ข้อมูลจะถูกเพิ่มในสไลด์ที่สร้างขึ้น |



### ดูเพิ่มเติม
* คลาส [`IExternalResourceResolver`](/slides/python-net/th/aspose.slides.importing/iexternalresourceresolver)
* คลาส [`SlideCollection`](/slides/python-net/th/aspose.slides/slidecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)