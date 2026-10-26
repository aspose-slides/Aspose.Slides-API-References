---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: การทำงานในตัวที่สร้างมาแล้วซึ่งเชื่อมต่อกับผู้ให้บริการ LLM ที่เข้ากันได้กับ OpenAI ณ URL ฐานที่ระบุ
type: docs
url: /th/com.aspose.slides/openaicompatiblewebclient/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IIAWebClient, System.IDisposable
```

การทำงานในตัว [IAIWebClient](../../com.aspose.slides/iaiwebclient) ที่เชื่อมต่อกับผู้ให้บริการ LLM ที่เข้ากันได้กับ OpenAI ที่กำหนด URL ฐาน

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | สร้างอินสแตนซ์ของเว็บไคลเอนต์ที่เข้ากันได้กับ OpenAI |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | สร้างอินสแตนซ์ของเว็บไคลเอนต์ที่เข้ากันได้กับ OpenAI ที่ใช้ HttpURLConnection ที่จัดการจากภายนอก |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | ส่งคำสั่งแช็ตไปยังโมเดล AI โดยใช้อินสแตนซ์ HttpURLConnection ที่จัดการจากภายนอกและคืนข้อความตอบกลับสำหรับคำสั่งที่กำหนด |
| [createConversation()](#createConversation--) | สร้างอินสแตนซ์ของการสนทนา |
| [dispose()](#dispose--) | ปล่อยทรัพยากรที่ใช้โดยอินสแตนซ์นี้ |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

สร้างอินสแตนซ์ของเว็บไคลเอนต์ที่เข้ากันได้กับ OpenAI.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| model | java.lang.String | ชื่อโมเดลที่ผู้ให้บริการ LLM รองรับ. |
| apiKey | java.lang.String | คีย์ API (โทเคน). |
| baseUrl | java.lang.String | URL ฐานของ LLM ที่เข้ากันได้กับ OpenAI. |
```
OpenAICompatibleWebClient aiClient =
         new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1");
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
``` |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

สร้างอินสแตนซ์ของเว็บไคลเอนต์ที่เข้ากันได้กับ OpenAI ที่ใช้ HttpURLConnection ที่จัดการจากภายนอก โดย HttpURLConnection ที่ส่งเข้ามานั้นจะไม่ถูกทำลายโดยอินสแตนซ์นี้และยังคงเป็นของผู้เรียกใช้.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| model | java.lang.String | ชื่อโมเดลที่ผู้ให้บริการ LLM รองรับ. |
| apiKey | java.lang.String | คีย์ API (โทเคน). |
| baseUrl | java.lang.String | URL ฐานของ LLM ที่เข้ากันได้กับ OpenAI. |
| httpClient | java.net.HttpURLConnection | อินสแตนซ์ HttpURLConnection ที่จัดการจากภายนอก. |
```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     OpenAICompatibleWebClient aiClient =
             new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

ส่งคำสั่งแช็ตไปยังโมเดล AI โดยใช้อินสแตนซ์ HttpURLConnection ที่จัดการจากภายนอกและคืนข้อความตอบกลับสำหรับคำสั่งที่ให้.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| instruction | java.lang.String | คำสั่งหรือข้อความที่จะให้โมเดล AI ประมวลผล. |

**ผลลัพธ์:**
java.lang.String - ข้อความที่โมเดล AI สร้างขึ้นเพื่อตอบกลับต่อคำสั่งที่ให้.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

สร้างอินสแตนซ์ของการสนทนา โดยการสนทนาจะรักษาบริบททั้งหมดไว้ ต่างจากการเรียก AI ปกติ.

**ผลลัพธ์:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - อินสแตนซ์ [IAIConversation](../../com.aspose.slides/iaiconversation)

### dispose() {#dispose--}
```
public final void dispose()
```

ปล่อยทรัพยากรที่ใช้งานโดยอินสแตนซ์นี้.