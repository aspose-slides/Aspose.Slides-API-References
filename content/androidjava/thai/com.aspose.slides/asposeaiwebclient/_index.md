---
title: AsposeAIWebClient
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: การนำไปใช้ในตัวเลือกที่สร้างมาแล้วซึ่งเชื่อมต่อกับ LLM ของ Aspose
type: docs
url: /th/com.aspose.slides/asposeaiwebclient/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำให้เป็นทั้งหมด:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

การนำไปใช้ในตัวเลือก [IAIWebClient](../../com.aspose.slides/iaiwebclient) ที่เชื่อมต่อกับ LLM ของ Aspose เอง นี่เป็นไคลเอนต์เริ่มต้นที่ใช้โดยคอนสตรัคเตอร์ SlidesAIAgent() ที่ไม่มีพารามิเตอร์
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับจุดสิ้นสุด LLM เริ่มต้นของ Aspose |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับจุดสิ้นสุด LLM เริ่มต้นของ Aspose โดยใช้ HttpURLConnection ที่จัดการภายนอก |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับ URL จุดสิ้นสุดแบบกำหนดเอง |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับ URL จุดสิ้นสุดแบบกำหนดเองโดยใช้ HttpURLConnection ที่จัดการภายนอก |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | ส่งคำสั่งแชทไปยังโมเดล AI และคืนข้อความตอบกลับตามคำสั่งที่ให้ |
| [createConversation()](#createConversation--) | สร้างอินสแตนซ์ของการสนทนา |
| [dispose()](#dispose--) | ปล่อยทรัพยากรที่ใช้โดยอินสแตนซ์นี้ |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```


สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับจุดสิ้นสุด LLM เริ่มต้นของ Aspose นี่คือไคลเอนต์ที่ใช้โดยคอนสตรัคเตอร์ SlidesAIAgent() ที่ไม่มีพารามิเตอร์ ดังนั้นการสร้างโดยตรงจึงจำเป็นเฉพาะเมื่อต้องการส่งไคลเอนต์ให้กับคอนสตรัคเตอร์ SlidesAIAgent(IAIWebClient) โดยตรง

```
AsposeAIWebClient aiClient = new AsposeAIWebClient();
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
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```


สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับจุดสิ้นสุด LLM เริ่มต้นของ Aspose โดยใช้ HttpURLConnection ที่จัดการภายนอก อินสแตนซ์ HttpURLConnection ที่ให้มาจะไม่ถูกทำลายโดยอินสแตนซ์นี้และยังคงเป็นของผู้เรียกใช้

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | อินสแตนซ์ HttpURLConnection ที่จัดการภายนอก

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
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

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```


สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับ URL จุดสิ้นสุดแบบกำหนดเอง ใช้โอเวอร์โหลดนี้เมื่อคุณมี URL ที่ทีม Aspose.Slides จัดหาให้; มิฉะนั้นให้ใช้โอเวอร์โหลด AsposeAIWebClient() พร้อม URL เริ่มต้น

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL จุดสิ้นสุดของ Aspose LLM ที่ทีม Aspose.Slides จัดหาให้

```
AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl);
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

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```


สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับ URL จุดสิ้นสุดแบบกำหนดเองโดยใช้ HttpURLConnection ที่จัดการภายนอก อินสแตนซ์ HttpURLConnection ที่ให้มาจะไม่ถูกทำลายโดยอินสแตนซ์นี้และยังคงเป็นของผู้เรียกใช้ ใช้โอเวอร์โหลดนี้เมื่อคุณมี URL ที่ทีม Aspose.Slides จัดหาให้และต้องการจัดหา HttpURLConnection ของคุณเอง; หากต้องการใช้ HttpURLConnection ของคุณกับ URL เริ่มต้น ให้ใช้โอเวอร์โหลด AsposeAIWebClient(HttpURLConnection) แทน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL จุดสิ้นสุดของ Aspose LLM ที่ทีม Aspose.Slides จัดหาให้ |
| httpClient | java.net.HttpURLConnection | อินสแตนซ์ HttpURLConnection ที่จัดการภายนอก

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
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


ส่งคำสั่งแชทไปยังโมเดล AI และคืนข้อความตอบกลับตามคำสั่งที่ให้

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| instruction | java.lang.String | คำสั่งหรือข้อความที่ต้องการให้โมเดล AI ประมวลผล |

**ผลลัพธ์:**
java.lang.String - ข้อความที่โมเดล AI สร้างขึ้นเพื่อตอบต่อคำสั่งที่ให้
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


สร้างอินสแตนซ์ของการสนทนา ต่างจากการเรียก AI ปกติ การสนทนาจะเก็บบริบททั้งหมด

**ผลลัพธ์:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - อินสแตนซ์ [IAIConversation](../../com.aspose.slides/iaiconversation)
### dispose() {#dispose--}
```
public final void dispose()
```


ปลดปล่อยทรัพยากรที่ใช้โดยอินสแตนซ์นี้.