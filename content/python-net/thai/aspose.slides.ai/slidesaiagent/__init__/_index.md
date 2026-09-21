---
title: SlidesAIAgent constructor
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
เริ่มต้นอินสแตนซ์ใหม่ของ [`SlidesAIAgent`](/slides/python-net/th/aspose.slides.ai/slidesaiagent) โดยใช้ [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient) ที่มาพร้อมการกำหนดค่าเริ่มต้น. ลูกค้าจะเชื่อมต่อกับ LLM ของ Aspose และไม่ต้องกำหนดค่าพิเศษเพิ่มเติม. หากต้องการใช้คลไอเอนต์ AI ตัวอื่น ให้ใช้ overload **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** แทน

```python
def __init__(self):
    ...
```

## __init__(self, ai_client) {#iaiwebclient}
เริ่มต้นอินสแตนซ์ใหม่ของ [`SlidesAIAgent`](/slides/python-net/th/aspose.slides.ai/slidesaiagent) ด้วยคลไอเอนต์ AI ที่กำหนดเอง. ใช้ overload นี้เพื่อระบุผู้ให้บริการ AI, จัดหา LLM ของคุณเอง, หรือปรับแต่งการเชื่อมต่อ (เช่น โดยการให้ `HttpClient` ของคุณเอง). สามารถใช้การดำเนินการใด ๆ ของ [`IAIWebClient`](/slides/python-net/th/aspose.slides.ai/iaiwebclient) ได้, รวมถึง:

* [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/th/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/th/aspose.slides.ai/openaicompatiblewebclient)

หากต้องการใช้ [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient) ที่มาพร้อมการกำหนดค่าเริ่มต้น, ให้ใช้ overload **SlidesAIAgent.#ctor** แทน

```python
def __init__(self, ai_client):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/th/aspose.slides.ai/iaiwebclient) | อินสแตนซ์ของคลไอเอนต์ AI. สามารถใช้การดำเนินการใด ๆ ของ [`IAIWebClient`](/slides/python-net/th/aspose.slides.ai/iaiwebclient) ได้. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | ไม่ได้ระบุอินสแตนซ์ของคลไอเอนต์ AI. |

### See Also
* class [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient)
* class [`IAIWebClient`](/slides/python-net/th/aspose.slides.ai/iaiwebclient)
* class [`OpenAICompatibleWebClient`](/slides/python-net/th/aspose.slides.ai/openaicompatiblewebclient)
* class [`OpenAIWebClient`](/slides/python-net/th/aspose.slides.ai/openaiwebclient)
* class [`SlidesAIAgent`](/slides/python-net/th/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/th/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)