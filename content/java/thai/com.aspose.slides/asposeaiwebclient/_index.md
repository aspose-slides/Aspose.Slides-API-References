---
title: AsposeAIWebClient
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: การใช้งานในตัวที่เชื่อมต่อกับ LLM ของ Aspose
type: docs
url: /th/com.aspose.slides/asposeaiwebclient/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

การใช้งาน [IAIWebClient](../../com.aspose.slides/iaiwebclient) ในตัวที่สร้างมาแล้วซึ่งเชื่อมต่อกับ LLM ของ Aspose เอง นี่คือไคลเอนต์เริ่มต้นที่ใช้โดยคอนสตรัคเตอร์  SlidesAIAgent()  ที่ไม่มีพารามิเตอร์

## คอนสตรัคเตอร์

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับปลายทาง Aspose LLM เริ่มต้น |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับปลายทาง Aspose LLM เริ่มต้นโดยใช้ HttpClient ที่จัดการจากภายนอก |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับ URL ของปลายทางที่กำหนดเอง |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับ URL ของปลายทางที่กำหนดเองโดยใช้ HttpClient ที่จัดการจากภายนอก |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | สร้างอินสแตนซ์ของการสนทนา |
| [dispose()](#dispose--) | ปลดปล่อยทรัพยากรที่ใช้โดยอินสแตนซ์นี้ |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับปลายทาง Aspose LLM เริ่มต้น นี่คือไคลเอนต์ที่ใช้โดยคอนสตรัคเตอร์  SlidesAIAgent()  ที่ไม่มีพารามิเตอร์ ดังนั้นการสร้างโดยเจตนาโดยตรงจำเป็นเฉพาะเมื่อต้องส่งไคลเอนต์ไปยังคอนสตรัคเตอร์  SlidesAIAgent(IAIWebClient)  โดยตรง

```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient())
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับปลายทาง Aspose LLM เริ่มต้นโดยใช้ HttpClient ที่จัดการจากภายนอก อินสแตนซ์ HttpClient ที่ให้มาจะไม่ถูกทำลายโดยอินสแตนซ์นี้และจะยังคงเป็นของผู้เรียกใช้

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | อินสแตนซ์ HttpClient ที่จัดการจากภายนอก |

```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับ URL ของปลายทางที่กำหนดเอง ใช้การโอเวอร์โหลดนี้เมื่อคุณมี URL ที่ทีม Aspose.Slides ให้ไว้; มิฉะนั้นให้ใช้การโอเวอร์โหลด  AsposeAIWebClient()  ที่มี URL เริ่มต้น

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL ของปลายทาง Aspose LLM ที่ทีม Aspose.Slides ให้ไว้ |

```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับ URL ของปลายทางที่กำหนดเองโดยใช้ HttpClient ที่จัดการจากภายนอก อินสแตนซ์ HttpClient ที่ให้มาจะไม่ถูกทำลายโดยอินสแตนซ์นี้และจะยังคงเป็นของผู้เรียกใช้ ใช้การโอเวอร์โหลดนี้เมื่อคุณมี URL ที่ทีม Aspose.Slides ให้ไว้และต้องการใช้ HttpClient ของตนเอง; หากต้องการใช้ HttpClient ของตนเองกับ URL เริ่มต้น ให้ใช้การโอเวอร์โหลด  AsposeAIWebClient(HttpClient)  แทน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL ของปลายทาง Aspose LLM ที่ทีม Aspose.Slides ให้ไว้ |
| httpClient | java.net.HttpURLConnection | อินสแตนซ์ HttpClient ที่จัดการจากภายนอก |

```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
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

ส่งคำสั่งแชทไปยังโมเดล AI โดยใช้อินสแตนซ์ HttpConnection ที่ให้มาและคืนค่าข้อความตอบกลับตามคำสั่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| instruction | java.lang.String |  |

**ค่าที่ส่งกลับ:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

สร้างอินสแตนซ์ของการสนทนา แตกต่างจากการเรียก AI ปกติ การสนทนาจะเก็บบริบททั้งหมดไว้

**ค่าที่ส่งกลับ:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - อินสแตนซ์ [IAIConversation](../../com.aspose.slides/iaiconversation)

### dispose() {#dispose--}
```
public final void dispose()
```

ปลดปล่อยทรัพยากรที่ใช้โดยอินสแตนซ์นี้.