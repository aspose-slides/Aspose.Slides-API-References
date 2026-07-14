---
title: SlidesAIAgent
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ให้คุณสมบัติที่ขับเคลื่อนด้วย AI สำหรับการประมวลผลงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/slidesaiagent/
---
**การสืบทอด:**
java.lang.Object
```
public class SlidesAIAgent
```

ให้คุณสมบัติที่ขับเคลื่อนด้วย AI สำหรับการประมวลผลงานนำเสนอ.
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent คอนสตรัคเตอร์ |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | แปลงานนำเสนอเป็นภาษาที่ระบุโดยใช้ AI (รุ่นซิงโครนัส) |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | สร้างอินสแตนซ์งานนำเสนอจากคำอธิบายเป็นข้อความ |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | สร้างอินสแตนซ์งานนำเสนอจากคำอธิบายเป็นข้อความ |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

SlidesAIAgent คอนสตรัคเตอร์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | อินสแตนซ์ไคลเอนต์ AI |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```

แปลงานนำเสนอเป็นภาษาที่ระบุโดยใช้ AI (รุ่นซิงโครนัส)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอเป้าหมาย |
| language | java.lang.String | ภาษาที่ต้องการ

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

สร้างอินสแตนซ์งานนำเสนอจากคำอธิบายเป็นข้อความ ให้หัวข้อ, ไอเดีย, คำคม หรือส่วนของข้อความในภาษาที่ต้องการ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| description | java.lang.String | หัวข้อ, ไอเดีย, คำคม หรือส่วนของข้อความ |
| presentationContentAmount | int | ปริมาณเนื้อหาในงานนำเสนอที่ได้

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
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

สร้างอินสแตนซ์งานนำเสนอจากคำอธิบายเป็นข้อความ ให้หัวข้อ, ไอเดีย, คำคม หรือส่วนของข้อความในภาษาที่ต้องการ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| description | java.lang.String | หัวข้อ, ไอเดีย, คำคม หรือส่วนของข้อความ |
| presentationContentAmount | int | ปริมาณเนื้อหาในงานนำเสนอที่ได้ |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอที่ใช้เป็นแม่แบบสำหรับการจัดวางและการออกแบบ, แทนที่แม่แบบเริ่มต้น

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
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