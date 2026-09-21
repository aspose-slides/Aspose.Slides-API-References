---
title: Presentation constructor
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
คอนสตรัคเตอร์นี้สร้างงานนำเสนอใหม่จากศูนย์  
งานนำเสนอที่สร้างขึ้นมีสไลด์เปล่า 1 แผ่น

```python
def __init__(self):
    ...
```

## __init__(self, load_options) {#loadoptions}
คอนสตรัคเตอร์นี้สร้างงานนำเสนอใหม่จากศูนย์  
งานนำเสนอที่สร้างขึ้นมีสไลด์เปล่า 1 แผ่น

```python
def __init__(self, load_options):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/th/aspose.slides/loadoptions) | ตัวเลือกการโหลดเพิ่มเติม |

## __init__(self, stream) {#iorawiobase}
คอนสตรัคเตอร์นี้เป็นกลไกหลักในการอ่านงานนำเสนอที่มีอยู่

```python
def __init__(self, stream):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมอินพุต |

## __init__(self, file) {#str}
คอนสตรัคเตอร์นี้รับเส้นทางไฟล์ต้นทางที่ใช้เพื่ออ่านเนื้อหาของงานนำเสนอ

```python
def __init__(self, file):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| file | **str** | ไฟล์อินพุต |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดขึ้นเมื่อไฟล์อินพุตมีความยาวเป็นศูนย์ |

## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
คอนสตรัคเตอร์นี้เป็นกลไกหลักในการอ่านงานนำเสนอที่มีอยู่

```python
def __init__(self, stream, load_options):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมอินพุต |
| load_options | [`LoadOptions`](/slides/python-net/th/aspose.slides/loadoptions) | ตัวเลือกการโหลดเพิ่มเติม |

## __init__(self, file, load_options) {#str-loadoptions}
คอนสตรัคเตอร์นี้รับเส้นทางไฟล์ต้นทางที่ใช้เพื่ออ่านเนื้อหาของงานนำเสนอ

```python
def __init__(self, file, load_options):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| file | **str** | ไฟล์อินพุต |
| load_options | [`LoadOptions`](/slides/python-net/th/aspose.slides/loadoptions) | ตัวเลือกการโหลดเพิ่มเติม |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดขึ้นเมื่อไฟล์อินพุตมีความยาวเป็นศูนย์ |

### ดูเพิ่มเติม
* คลาส [`LoadOptions`](/slides/python-net/th/aspose.slides/loadoptions)
* คลาส [`Presentation`](/slides/python-net/th/aspose.slides/presentation)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)