---
title: translate method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
แปลงานนำเสนอเป็นภาษาที่กำหนดโดยใช้ AI (เวอร์ชันแบบซิงโครนัส).

```python
def translate(self, presentation, language):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation) | งานนำเสนอเป้าหมาย |
| language | **str** | ภาษาที่ต้องการ |

### หมายเหตุ

ตัวอย่างด้านล่างใช้ค่าเริ่มต้น [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient) ซึ่งสร้างโดยคอนสตรัคเตอร์ **SlidesAIAgent.#ctor** ที่ไม่มีพารามิเตอร์และเชื่อมต่อกับ LLM ของ Aspose เอง. เพื่อใช้ผู้ให้บริการ AI ตัวอื่น ให้จัดหา LLM ของคุณเอง หรือปรับแต่งการเชื่อมต่อ (เช่น โดยให้ `HttpClient` ของคุณเอง) ส่งการทำงาน [`IAIWebClient`](/slides/python-net/th/aspose.slides.ai/iaiwebclient) ไปยังคอนสตรัคเตอร์ **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. การทำงานที่มีให้รวมถึง:

* [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/th/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/th/aspose.slides.ai/openaicompatiblewebclient)

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | ไม่ได้ระบุอินสแตนซ์ของงานนำเสนอ |
| **RuntimeError(Proxy error(ArgumentException))** | ค่าภาษาไม่สามารถเป็น None หรือเป็นค่าว่าง |

### ดูเพิ่มเติม
* คลาส [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient)
* คลาส [`IAIWebClient`](/slides/python-net/th/aspose.slides.ai/iaiwebclient)
* คลาส [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation)
* คลาส [`OpenAICompatibleWebClient`](/slides/python-net/th/aspose.slides.ai/openaicompatiblewebclient)
* คลาส [`OpenAIWebClient`](/slides/python-net/th/aspose.slides.ai/openaiwebclient)
* คลาส [`SlidesAIAgent`](/slides/python-net/th/aspose.slides.ai/slidesaiagent)
* โมดูล [`aspose.slides.ai`](/slides/python-net/th/aspose.slides.ai)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)