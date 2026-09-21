---
title: process method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
รวมหลายงานนำเสนอ PowerPoint ที่มีรูปแบบเดียวกันเป็นไฟล์งานนำเสนอเดียว.

```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| input_file_names | **List[str]** | An array of the input presentation file names. |
| output_file_name | **str**** | The output file name of the resulting merged presentation file. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดเมื่อชื่อไฟล์อินพุตไม่ถูกต้องหรือรูปแบบไม่ตรงกัน. |

## process(input_file_names, output_stream) {#liststr-iorawiobase}
รวมหลายงานนำเสนอ PowerPoint ที่มีรูปแบบเดียวกันเป็นไฟล์งานนำเสนอเดียว.

```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| input_file_names | **List[str]** | An array of the input presentation file names. |
| output_stream | **io.RawIOBase** | The output stream. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดเมื่อชื่อไฟล์อินพุตไม่ถูกต้องหรือรูปแบบไม่ตรงกัน. |

## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
รวมหลายงานนำเสนอ PowerPoint ที่มีรูปแบบเดียวกันเป็นไฟล์งานนำเสนอเดียว.

```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| input_file_names | **List[str]** | An array of the input presentation file names. |
| output_file_name | **str** | The output file name of the resulting merged presentation file. |
| options | [`ISaveOptions`](/slides/python-net/th/aspose.slides.export/isaveoptions) | The additional options that define how the merged presentation is saved. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดเมื่อชื่อไฟล์อินพุตไม่ถูกต้องหรือรูปแบบไม่ตรงกัน. |

## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
รวมหลายงานนำเสนอ PowerPoint ที่มีรูปแบบเดียวกันเป็นไฟล์งานนำเสนอเดียว.

```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| input_file_names | **List[str]** | An array of the input presentation file names. |
| output_stream | **io.RawIOBase** | The output stream. |
| options | [`ISaveOptions`](/slides/python-net/th/aspose.slides.export/isaveoptions) | The additional options that define how the merged presentation is saved. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดเมื่อชื่อไฟล์อินพุตไม่ถูกต้องหรือรูปแบบไม่ตรงกัน. |

### ดูเพิ่มเติม
* คลาส [`ISaveOptions`](/slides/python-net/th/aspose.slides.export/isaveoptions)
* คลาส [`Merger`](/slides/python-net/th/aspose.slides.lowcode/merger)
* โมดูล [`aspose.slides.lowcode`](/slides/python-net/th/aspose.slides.lowcode)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)