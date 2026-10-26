---
title: SlidesAIAgent class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent คลาส

ให้คุณสมบัติที่ใช้ AI ในการประมวลผลการนำเสนอ

ประเภท SlidesAIAgent เปิดเผยสมาชิกต่อไปนี้:

## คอนสตรัคเตอร์

| Constructor | Description |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/th/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | สร้างอินสแตนซ์ใหม่ของ [`SlidesAIAgent`](/slides/python-net/th/aspose.slides.ai/slidesaiagent) ด้วยคลายเอไอที่กำหนดเอง.<br/>            ใช้ overload นี้เพื่อระบุผู้ให้บริการ AI, จัดหา LLM ของคุณเอง, หรือปรับแต่ง<br/>            การเชื่อมต่อ (เช่น โดยการให้ `HttpClient` ของคุณเอง).<br/>            สามารถใช้การทำงานใด ๆ ของ [`IAIWebClient`](/slides/python-net/th/aspose.slides.ai/iaiwebclient) รวมถึง:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/th/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/th/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            เพื่อใช้ [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient) ที่มาพร้อมกับการกำหนดค่าเริ่มต้น,<br/>            ให้ใช้ overload **SlidesAIAgent.#ctor** แทน. |
| [`__init__(self)`](/slides/python-net/th/aspose.slides.ai/slidesaiagent/__init__/#) | สร้างอินสแตนซ์ใหม่ของ [`SlidesAIAgent`](/slides/python-net/th/aspose.slides.ai/slidesaiagent) โดยใช้ [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient) ที่มาพร้อมกับการกำหนดค่าเริ่มต้น. ลูกค้าจะเชื่อมต่อกับ<br/>            LLM ของ Aspose เองและไม่ต้องการการกำหนดค่าเพิ่มเติม.<br/>            เพื่อใช้ไคลเอนต์ AI อื่น, ให้ใช้ overload **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** แทน. |

## เมธอด

| Method | Description |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/th/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | สร้างอินสแตนซ์การนำเสนอจากคำอธิบายข้อความ. ให้ระบุหัวข้อ, ไอเดีย, คำคม, หรือส่วนข้อความในภาษาที่ต้องการ. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/th/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | สร้างอินสแตนซ์การนำเสนอจากคำอธิบายข้อความ. ให้ระบุหัวข้อ, ไอเดีย, คำคม, หรือส่วนข้อความในภาษาที่ต้องการ. |
| [`translate(self, presentation, language)`](/slides/python-net/th/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | แปลการนำเสนอเป็นภาษาที่ระบุโดยใช้ AI (รุ่น synchronous). |

### ดูเพิ่มเติม
* คลาส [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient)
* คลาส [`IAIWebClient`](/slides/python-net/th/aspose.slides.ai/iaiwebclient)
* คลาส [`OpenAICompatibleWebClient`](/slides/python-net/th/aspose.slides.ai/openaicompatiblewebclient)
* คลาส [`OpenAIWebClient`](/slides/python-net/th/aspose.slides.ai/openaiwebclient)
* คลาส [`SlidesAIAgent`](/slides/python-net/th/aspose.slides.ai/slidesaiagent)
* โมดูล [`aspose.slides.ai`](/slides/python-net/th/aspose.slides.ai)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)