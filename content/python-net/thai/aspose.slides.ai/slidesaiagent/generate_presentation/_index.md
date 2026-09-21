---
title: generate_presentation method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
สร้างอินสแตนซ์การพรีเซนเทชันจากคำอธิบายข้อความ ให้หัวข้อ ไอเดีย คำคม หรือข้อความสั้นในภาษาที่ต้องการ


```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| description | **str** | The topic, ideas, quotes, or text snippets. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/th/aspose.slides.ai/presentationcontentamounttype) | The amount of content in the resulting presentation. |

### หมายเหตุ

ตัวอย่างด้านล่างใช้ค่าเริ่มต้น [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient) ซึ่งสร้างโดยคอนสตรักเตอร์ **SlidesAIAgent.#ctor** ที่ไม่มีพารามิเตอร์และเชื่อมต่อกับ LLM ของ Aspose  
เพื่อใช้ผู้ให้บริการ AI ตัวอื่น ให้ระบุ LLM ของคุณเอง หรือปรับแต่งการเชื่อมต่อ (เช่น โดยให้ `HttpClient` ของคุณ) ส่งการนำไปใช้ [`IAIWebClient`](/slides/python-net/th/aspose.slides.ai/iaiwebclient) ไปยังคอนสตรักเตอร์ **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** การนำไปใช้ที่มีอยู่รวมถึง:

* [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/th/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/th/aspose.slides.ai/openaicompatiblewebclient)

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | คำสั่งแชท AI ไม่สามารถเป็นค่า None หรือว่างได้. |

## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
สร้างอินสแตนซ์การพรีเซนเทชันจากคำอธิบายข้อความ ให้หัวข้อ ไอเดีย คำคม หรือข้อความสั้นในภาษาที่ต้องการ


```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| description | **str** | The topic, ideas, quotes, or text snippets. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/th/aspose.slides.ai/presentationcontentamounttype) | The amount of content in the resulting presentation. |
| presentation_template | [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation) | พรีเซนเทชันที่ใช้เป็นแม่แบบสำหรับการจัดวางและออกแบบ แทนที่แม่แบบเริ่มต้น. |

### หมายเหตุ

ตัวอย่างด้านล่างใช้ค่าเริ่มต้น [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient) ซึ่งสร้างโดยคอนสตรักเตอร์ **SlidesAIAgent.#ctor** ที่ไม่มีพารามิเตอร์และเชื่อมต่อกับ LLM ของ Aspose  
เพื่อใช้ผู้ให้บริการ AI ตัวอื่น ให้ระบุ LLM ของคุณเอง หรือปรับแต่งการเชื่อมต่อ (เช่น โดยให้ `HttpClient` ของคุณ) ส่งการนำไปใช้ [`IAIWebClient`](/slides/python-net/th/aspose.slides.ai/iaiwebclient) ไปยังคอนสตรักเตอร์ **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** การนำไปใช้ที่มีอยู่รวมถึง:

* [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/th/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/th/aspose.slides.ai/openaicompatiblewebclient)

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | ไม่ได้ระบุแม่แบบพรีเซนเทชัน. |
| **RuntimeError(Proxy error(ArgumentException))** | คำสั่งแชท AI ไม่สามารถเป็นค่า None หรือว่างได้. |

### ดูเพิ่มเติม
* class [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient)
* class [`IAIWebClient`](/slides/python-net/th/aspose.slides.ai/iaiwebclient)
* class [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation)
* class [`OpenAICompatibleWebClient`](/slides/python-net/th/aspose.slides.ai/openaicompatiblewebclient)
* class [`OpenAIWebClient`](/slides/python-net/th/aspose.slides.ai/openaiwebclient)
* enumeration [`PresentationContentAmountType`](/slides/python-net/th/aspose.slides.ai/presentationcontentamounttype)
* class [`SlidesAIAgent`](/slides/python-net/th/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/th/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)