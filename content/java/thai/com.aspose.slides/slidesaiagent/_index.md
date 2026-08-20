---
title: SlidesAIAgent
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: ให้ฟีเจอร์ขับเคลื่อนด้วย AI สำหรับการประมวลผลงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/slidesaiagent/
---
**การสืบทอด:**  
java.lang.Object  
```
public class SlidesAIAgent
```

ให้คุณลักษณะขับเคลื่อนด้วย AI สำหรับการประมวลผลงานนำเสนอ.  

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | เริ่มต้นอินสแตนซ์ใหม่ของ [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) ด้วยไคลเอนต์ AI ที่กำหนดเอง. |
| [SlidesAIAgent()](#SlidesAIAgent--) | เริ่มต้นอินสแตนซ์ใหม่ของ [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) โดยใช้ [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) ที่มาพร้อมการตั้งค่าเริ่มต้น. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | แปลงานนำเสนอเป็นภาษาที่ระบุโดยใช้ AI (เวอร์ชันประสานเวลา). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | สร้างอินสแตนซ์งานนำเสนอจากคำอธิบายข้อความ. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | สร้างอินสแตนซ์งานนำเสนอจากคำอธิบายข้อความ. |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

เริ่มต้นอินสแตนซ์ใหม่ของ [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) ด้วยไคลเอนต์ AI ที่กำหนดเอง ใช้ overload นี้เพื่อระบุผู้ให้บริการ AI, จัดหา LLM ของคุณเอง, หรือปรับแต่งการเชื่อมต่อ (เช่นโดยการให้ java.net.HttpURLConnection ของคุณเอง) สามารถใช้การทำงานใด ๆ ของ [IAIWebClient](../../com.aspose.slides/iaiwebclient) ได้ หากต้องการใช้ [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) ที่มาพร้อมการตั้งค่าเริ่มต้น ให้ใช้ overload SlidesAIAgent() แทน  

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | อินสแตนซ์ไคลเอนต์ AI สามารถใช้การทำงานใด ๆ ของ [IAIWebClient](../../com.aspose.slides/iaiwebclient) ได้. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

เริ่มต้นอินสแตนซ์ใหม่ของ [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) โดยใช้ [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) ที่มาพร้อมการตั้งค่าเริ่มต้น ลูกค้าจะเชื่อมต่อกับ LLM ของ Aspose เองและไม่ต้องการการตั้งค่าเพิ่มเติม หากต้องการใช้ไคลเอนต์ AI ตัวอื่น ให้ใช้ overload SlidesAIAgent(IAIWebClient) แทน  

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

แปลงานนำเสนอเป็นภาษาที่ระบุโดยใช้ AI (เวอร์ชันประสานเวลา).  

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอเป้าหมาย |
| language | java.lang.String | ภาษาปลายทาง |

--------------------

ตัวอย่างด้านล่างใช้ [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) เริ่มต้น ซึ่งสร้างโดยคอนสตรัคเตอร์ SlidesAIAgent() ที่ไม่มีพารามิเตอร์และเชื่อมต่อกับ LLM ของ Aspose เอง หากต้องการใช้ผู้ให้บริการ AI ตัวอื่น จัดหา LLM ของคุณเอง หรือปรับแต่งการเชื่อมต่อ (เช่นโดยการให้ java.net.HttpURLConnection ของคุณเอง) ให้ส่งการทำงานของ [IAIWebClient](../../com.aspose.slides/iaiwebclient) ไปยังคอนสตรัคเตอร์ SlidesAIAgent(IAIWebClient).  

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

สร้างอินสแตนซ์งานนำเสนอจากคำอธิบายข้อความ ให้หัวข้อ, ความคิด, คำคม หรือข้อความสั้นในภาษาที่ต้องการ.  

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| description | java.lang.String | หัวข้อ, ความคิด, คำคม หรือข้อความสั้นในภาษาที่ต้องการ. |
| presentationContentAmount | int | จำนวนเนื้อหาในงานนำเสนอที่สร้าง. |

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

สร้างอินสแตนซ์งานนำเสนอจากคำอธิบายข้อความ ให้หัวข้อ, ความคิด, คำคม หรือข้อความสั้นในภาษาที่ต้องการ.  

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| description | java.lang.String | หัวข้อ, ความคิด, คำคม หรือข้อความสั้นในภาษาที่ต้องการ. |
| presentationContentAmount | int | จำนวนเนื้อหาในงานนำเสนอที่สร้าง. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอที่ใช้เป็นแม่แบบสำหรับเลย์เอาต์และการออกแบบ, แทนที่แม่แบบเริ่มต้น. |

--------------------

ตัวอย่างด้านล่างใช้ [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) เริ่มต้น ซึ่งสร้างโดยคอนสตรัคเตอร์ SlidesAIAgent() ที่ไม่มีพารามิเตอร์และเชื่อมต่อกับ LLM ของ Aspose เอง หากต้องการใช้ผู้ให้บริการ AI ตัวอื่น จัดหา LLM ของคุณเอง หรือปรับแต่งการเชื่อมต่อ (เช่นโดยการให้ java.net.HttpURLConnection ของคุณเอง) ให้ส่งการทำงานของ [IAIWebClient](../../com.aspose.slides/iaiwebclient) ไปยังคอนสตรัคเตอร์ SlidesAIAgent(IAIWebClient).  

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