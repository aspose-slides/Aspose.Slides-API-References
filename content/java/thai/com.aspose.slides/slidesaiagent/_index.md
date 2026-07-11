---
title: SlidesAIAgent
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ให้คุณลักษณะที่ขับเคลื่อนด้วย AI สำหรับการประมวลผลงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/slidesaiagent/
---
**Inheritance:**
java.lang.Object
```
public class SlidesAIAgent
```

ให้คุณลักษณะที่ขับเคลื่อนด้วย AI สำหรับการประมวลผลงานนำเสนอ
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | เริ่มต้นอินสแตนซ์ใหม่ของ [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) ด้วยคลไอเอนท์ AI ที่กำหนดเอง |
| [SlidesAIAgent()](#SlidesAIAgent--) | เริ่มต้นอินสแตนซ์ใหม่ของ [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) โดยใช้ [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) ที่มีมาในตัวพร้อมการกำหนดค่าพื้นฐานของมัน |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | แปลงานนำเสนอเป็นภาษาที่ระบุโดยใช้ AI (เวอร์ชันแบบ synchronous) |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | สร้างอินสแตนซ์งานนำเสนอจากคำอธิบายข้อความ |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | สร้างอินสแตนซ์งานนำเสนอจากคำอธิบายข้อความ |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

เริ่มต้นอินสแตนซ์ใหม่ของ [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) ด้วยคลไอเอนท์ AI ที่กำหนดเอง ใช้อัปโหลดนี้เพื่อระบุผู้ให้บริการ AI, จัดหา LLM ของคุณเอง, หรือปรับแต่งการเชื่อมต่อ (เช่น โดยให้ java.net.HttpURLConnection ของคุณเอง) การทำงานใด ๆ ของ [IAIWebClient](../../com.aspose.slides/iaiwebclient) สามารถใช้ได้ หากต้องการใช้ [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) ที่มีมาในตัวพร้อมการกำหนดค่าพื้นฐาน ให้ใช้เมธอด SlidesAIAgent() แทน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | อินสแตนซ์คลไอเอนท์ AI การทำงานใด ๆ ของ [IAIWebClient](../../com.aspose.slides/iaiwebclient) สามารถใช้ได้ |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

เริ่มต้นอินสแตนซ์ใหม่ของ [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) โดยใช้ [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) ที่มีมาในตัวพร้อมการกำหนดค่าพื้นฐานของมัน คลไอเอนท์จะเชื่อมต่อกับ LLM ของ Aspose เองและไม่ต้องการการกำหนดค่าเพิ่มเติม หากต้องการใช้คลไอเอนท์ AI ตัวอื่น ให้ใช้เมธอด SlidesAIAgent(IAIWebClient) แทน

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

แปลงานนำเสนอเป็นภาษาที่ระบุโดยใช้ AI (เวอร์ชันแบบ synchronous)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอเป้าหมาย |
| language | java.lang.String | ภาษาที่ต้องการ |

--------------------

ตัวอย่างด้านล่างใช้ [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) เริ่มต้น ซึ่งสร้างโดยคอนสตรักเตอร์ SlidesAIAgent() ที่ไม่มีพารามิเตอร์และเชื่อมต่อกับ LLM ของ Aspose หากต้องการใช้ผู้ให้บริการ AI ตัวอื่น จัดหา LLM ของคุณเอง หรือปรับแต่งการเชื่อมต่อ (เช่น โดยให้ java.net.HttpURLConnection ของคุณ) ให้ส่งการนำไปใช้ [IAIWebClient](../../com.aspose.slides/iaiwebclient) ไปยังคอนสตรักเตอร์ SlidesAIAgent(IAIWebClient)

```
Presentation presentation = new Presentation("Presentation.pptx");
 try {
     IAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", "apiKey", null);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     aiAgent.translate(presentation, "spanish");
     presentation.save("translated.pptx", SaveFormat.Pptx);
 } finally {
     if (presentation != null) presentation.dispose();
 }
``` |

### generatePresentation(String description, int presentationContentAmount) {#generatePresentation-java.lang.String-int-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount)
```

สร้างอินสแตนซ์งานนำเสนอจากคำอธิบายข้อความ ให้หัวข้อ, ไอเดีย, คำคม หรือส่วนของข้อความในภาษาที่ต้องการ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| description | java.lang.String | หัวข้อ, ไอเดีย, คำคม หรือส่วนของข้อความ |
| presentationContentAmount | int | จำนวนเนื้อหาในงานนำเสนอที่สร้างขึ้น |

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief);
     pres.save("result.pptx", SaveFormat.Pptx);
 } finally {
     if (aiWebClient != null) aiWebClient.close();
 }
``` |

**ผลลัพธ์:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

สร้างอินสแตนซ์งานนำเสนอจากคำอธิบายข้อความ ให้หัวข้อ, ไอเดีย, คำคม หรือส่วนของข้อความในภาษาที่ต้องการ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| description | java.lang.String | หัวข้อ, ไอเดีย, คำคม หรือส่วนของข้อความ |
| presentationContentAmount | int | จำนวนเนื้อหาในงานนำเสนอที่สร้างขึ้น |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอที่จะใช้เป็นเทมเพลตสำหรับการจัดวางและออกแบบ แทนเทมเพลตเริ่มต้น |

--------------------

ตัวอย่างด้านล่างใช้ [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) เริ่มต้น ซึ่งสร้างโดยคอนสตรักเตอร์ SlidesAIAgent() ที่ไม่มีพารามิเตอร์และเชื่อมต่อกับ LLM ของ Aspose หากต้องการใช้ผู้ให้บริการ AI ตัวอื่น จัดหา LLM ของคุณเอง หรือปรับแต่งการเชื่อมต่อ (เช่น โดยให้ java.net.HttpURLConnection ของคุณ) ให้ส่งการนำไปใช้ [IAIWebClient](../../com.aspose.slides/iaiwebclient) ไปยังคอนสตรักเตอร์ SlidesAIAgent(IAIWebClient)

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 IPresentation template = new Presentation("masterPresentation.pptx");
 try {
     OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
     try {
         SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
         IPresentation pres =
             aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief, template);
         pres.save("result.pptx", SaveFormat.Pptx);
     } finally {
         if (aiWebClient != null) aiWebClient.close();
     }
 } finally {
     if (template != null) template.dispose();
 }
``` |

**ผลลัพธ์:**
[IPresentation](../../com.aspose.slides/ipresentation)