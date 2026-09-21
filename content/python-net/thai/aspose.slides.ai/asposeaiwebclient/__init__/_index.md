---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับปลายทาง Aspose LLM เริ่มต้น
นี้คือไคลเอนต์ที่ใช้โดยคอนสตรัคเตอร์ **SlidesAIAgent.#ctor** ที่ไม่มีพารามิเตอร์ ดังนั้นการสร้างอย่างชัดเจนจึงจำเป็นเฉพาะเมื่อส่งไคลเอนต์ให้กับคอนสตรัคเตอร์ **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** โดยตรง.

```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับ URL ปลายทางแบบกำหนดเอง ใช้ overload นี้เมื่อคุณมี URL ที่ได้รับจากทีม Aspose.Slides; หากไม่เป็นเช่นนั้น ให้ใช้ overload **AsposeAIWebClient.#ctor** พร้อม URL เริ่มต้น.

```python
def __init__(self, url):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| url | **str** | Endpoint URL ของ Aspose LLM ที่จัดให้โดยทีม Aspose.Slides. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL ไม่สามารถเป็น None หรือว่างเปล่าได้. |



### ดูเพิ่มเติม
* คลาส [`AsposeAIWebClient`](/slides/python-net/th/aspose.slides.ai/asposeaiwebclient)
* โมดูล [`aspose.slides.ai`](/slides/python-net/th/aspose.slides.ai)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)