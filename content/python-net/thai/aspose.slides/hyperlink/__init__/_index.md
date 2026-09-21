---
title: Hyperlink constructor
second_title: อ้างอิง API Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
สร้างอินสแตนซ์ของไฮเปอร์ลิงก์

```python
def __init__(self, url):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| url | **str** | URL ของไฮเปอร์ลิงก์. |

## __init__(self, slide) {#islide}
สร้างอินสแตนซ์ของไฮเปอร์ลิงก์ที่ชี้ไปยังสไลด์เฉพาะ
หมายเหตุ: ไฮเปอร์ลิงก์ที่สร้างควรถูกกำหนดให้กับอ็อบเจกต์จากพรีเซนเทชันเดียวกัน มิฉะนั้นลิงค์จะถูกบันทึกเป็น NoAction

```python
def __init__(self, slide):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | สไลด์เป้าหมาย. |

## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
สร้างอินสแตนซ์ของไฮเปอร์ลิงก์โดยใช้ไฮเปอร์ลิงก์อื่นเป็นแหล่งที่มาและแทนที่คุณสมบัติที่สอง

```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/th/aspose.slides/hyperlink) | ไฮเปอร์ลิงก์แหล่งที่มา |
| target_frame | **str** | เฟรมเป้าหมาย |
| tooltip | **str** | ข้อความ tooltip |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |

### ดูเพิ่มเติม
* คลาส [`Hyperlink`](/slides/python-net/th/aspose.slides/hyperlink)
* คลาส [`ISlide`](/slides/python-net/th/aspose.slides/islide)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)