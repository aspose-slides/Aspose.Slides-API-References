---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: การนำไปใช้ในตัวที่สร้างมาตรฐานซึ่งเชื่อมต่อกับผู้ให้บริการ LLM ที่เข้ากันได้กับ OpenAI ที่ URL ฐานที่ระบุ.
type: docs
url: /th/com.aspose.slides/openaicompatiblewebclient/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

การนำไปใช้ [IAIWebClient](../../com.aspose.slides/iaiwebclient) ในตัวที่สร้างมาตรฐานซึ่งเชื่อมต่อกับผู้ให้บริการ LLM ที่เข้ากันได้กับ OpenAI ที่ URL ฐานที่ระบุ
## ตัวสร้าง

| Constructor | Description |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | สร้างอินสแตนซ์ของเว็บคลไเอนท์ที่เข้ากันได้กับ OpenAI |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | สร้างอินสแตนซ์ของเว็บคลไเอนท์ที่เข้ากันได้กับ OpenAI ที่ใช้ HttpURLConnection ที่จัดการโดยภายนอก |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | ส่งคำแนะนำแชทไปยังโมเดล AI โดยใช้อินสแตนซ์ HttpURLConnection ที่จัดการโดยภายนอกและคืนข้อความตอบกลับต่อคำสั่งที่ให้ |
| [createConversation()](#createConversation--) | สร้างอินสแตนซ์ของการสนทนา |
| [dispose()](#dispose--) | ปลดปล่อยทรัพยากรที่ใช้โดยอินสแตนซ์นี้ |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

สร้างอินสแตนซ์ของเว็บคลไเอนท์ที่เข้ากันได้กับ OpenAI

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| model | java.lang.String | ชื่อโมเดลที่สนับสนุนโดยผู้ให้บริการ LLM |
| apiKey | java.lang.String | คีย์ API (โทเค็น) |
| baseUrl | java.lang.String | URL ฐานของ LLM ที่เข้ากันได้กับ OpenAI |

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

สร้างอินสแตนซ์ของเว็บคลไเอนท์ที่เข้ากันได้กับ OpenAI ที่ใช้ HttpURLConnection ที่จัดการโดยภายนอก อินสแตนซ์ HttpURLConnection ที่ให้มา จะไม่ถูกทำลายโดยอินสแตนซ์นี้และยังคงเป็นของผู้เรียกใช้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| model | java.lang.String | ชื่อโมเดลที่สนับสนุนโดยผู้ให้บริการ LLM |
| apiKey | java.lang.String | คีย์ API (โทเค็น) |
| baseUrl | java.lang.String | URL ฐานของ LLM ที่เข้ากันได้กับ OpenAI |
| httpClient | java.net.HttpURLConnection | อินสแตนซ์ HttpURLConnection ที่จัดการโดยภายนอก |

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

ส่งคำแนะนำแชทไปยังโมเดล AI โดยใช้อินสแตนซ์ HttpURLConnection ที่จัดการโดยภายนอกและคืนข้อความตอบกลับต่อคำสั่งที่ให้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| instruction | java.lang.String | คำแนะนำหรือข้อความที่จะประมวลผลโดยโมเดล AI |

**ผลลัพธ์:**
java.lang.String - ข้อความที่สร้างโดยโมเดล AI ในการตอบกลับต่อคำสั่งที่ให้

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

สร้างอินสแตนซ์ของการสนทนา ไม่เหมือนการเรียก AI ปกติ การสนทนาจะเก็บบริบททั้งหมด

**ผลลัพธ์:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - อินสแตนซ์ของ [IAIConversation](../../com.aspose.slides/iaiconversation)

### dispose() {#dispose--}
```
public final void dispose()
```

ปลดปล่อยทรัพยากรที่ใช้โดยอินสแตนซ์นี้.