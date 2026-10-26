---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
สร้างอินสแตนซ์ของเว็บไคลเอนต์ที่เข้ากันได้กับ OpenAI-compatible.

```python
def __init__(self, model, api_key, base_url):
    ...
```

| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| model | **str** | ชื่อโมเดลที่รองรับโดยผู้ให้บริการ LLM. |
| api_key | **str** | API key (โทเค็น). |
| base_url | **str** | Base URL ของ LLM ที่เข้ากันได้กับ OpenAI-compatible. |

### ข้อยกเว้น

| ข้อยกเว้น | รายละเอียด |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | ค่า API key ไม่สามารถเป็น None หรือว่างเปล่าได้. |
| **RuntimeError(Proxy error(ArgumentException))** | ค่า Text model ไม่สามารถเป็น None หรือว่างเปล่าได้. |
| **RuntimeError(Proxy error(ArgumentException))** | ค่า Base URL ไม่สามารถเป็น None หรือว่างเปล่าได้. |

### ดูเพิ่มเติม
* คลาส [`OpenAICompatibleWebClient`](/slides/python-net/th/aspose.slides.ai/openaicompatiblewebclient)
* โมดูล [`aspose.slides.ai`](/slides/python-net/th/aspose.slides.ai)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)