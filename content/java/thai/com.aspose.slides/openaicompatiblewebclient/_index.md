---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides สำหรับ Java API Reference
description: การทำงานในตัวที่เชื่อมต่อกับผู้ให้บริการ LLM ที่เข้ากันได้กับ OpenAI ที่ URL ฐานที่ระบุ
type: docs
url: /th/com.aspose.slides/openaicompatiblewebclient/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

การทำงานที่สร้างขึ้นโดยอัตโนมัติ [IAIWebClient](../../com.aspose.slides/iaiwebclient) ที่เชื่อมต่อกับผู้ให้บริการ LLM ที่เข้ากันได้กับ OpenAI ที่ URL ฐานที่ระบุ
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | สร้างอินสแตนซ์ของไคลเอนต์เว็บที่เข้ากันได้กับ OpenAI |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | สร้างอินสแตนซ์ของไคลเอนต์เว็บที่เข้ากันได้กับ OpenAI ที่ใช้ HttpClient ที่จัดการจากภายนอก |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | สร้างอินสแตนซ์ของการสนทนา |
| [dispose()](#dispose--) | ปล่อยทรัพยากรที่อินสแตนซ์นี้ใช้ |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

สร้างอินสแตนซ์ของไคลเอนต์เว็บที่เข้ากันได้กับ OpenAI

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| model | java.lang.String | ชื่อโมเดลที่ผู้ให้บริการ LLM รองรับ |
| apiKey | java.lang.String | คีย์ API (โทเค็น) |
| baseUrl | java.lang.String | URL ฐานของ LLM ที่เข้ากันได้กับ OpenAI |

```
using (OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1"))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

สร้างอินสแตนซ์ของไคลเอนต์เว็บที่เข้ากันได้กับ OpenAI ที่ใช้ HttpClient ที่จัดการจากภายนอก  HttpClient ที่ให้มา ไม่ถูกทำลายโดยอินสแตนซ์นี้และยังคงเป็นของผู้เรียกใช้งาน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| model | java.lang.String | ชื่อโมเดลที่ผู้ให้บริการ LLM รองรับ |
| apiKey | java.lang.String | คีย์ API (โทเค็น) |
| baseUrl | java.lang.String | URL ฐานของ LLM ที่เข้ากันได้กับ OpenAI |
| httpClient | java.net.HttpURLConnection | อินสแตนซ์ HttpClient ที่จัดการจากภายนอก |

```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

ส่งคำสั่งแชทไปยังโมเดล AI โดยใช้อินสแตนซ์ HttpConnection ที่ให้มาและคืนข้อความตอบกลับต่อคำสั่งที่ให้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| instruction | java.lang.String |  |

**คืนค่า:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

สร้างอินสแตนซ์ของการสนทนา  การสนทนาจะรักษาบริบททั้งหมดต่างจากการเรียก AI ปกติ

**คืนค่า:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - เป็นอินสแตนซ์ของ [IAIConversation](../../com.aspose.slides/iaiconversation)
### dispose() {#dispose--}
```
public final void dispose()
```

ปล่อยทรัพยากรที่อินสแตนซ์นี้ใช้.