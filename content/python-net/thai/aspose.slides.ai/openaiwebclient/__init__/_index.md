---
title: OpenAIWebClient constructor
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
สร้างอินสแตนซ์ของไคลเอ็นต์เว็บ OpenAI

```python
def __init__(self, model, api_key, organization_id):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| model | **str** | โมเดลภาษา OpenAI. ค่าที่เป็นไปได้:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | คีย์ API ของ OpenAI. |
| organization_id | **str** | รหัสองค์กร (ไม่จำเป็น). |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | ค่า API key ไม่สามารถเป็นค่า Null หรือว่างเปล่าได้. |
| **RuntimeError(Proxy error(ArgumentException))** | ค่าโมเดลข้อความไม่สามารถเป็นค่า Null หรือว่างเปล่าได้. |

### ดูเพิ่มเติม
* คลาส [`OpenAIWebClient`](/slides/python-net/th/aspose.slides.ai/openaiwebclient)
* โมดูล [`aspose.slides.ai`](/slides/python-net/th/aspose.slides.ai)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)