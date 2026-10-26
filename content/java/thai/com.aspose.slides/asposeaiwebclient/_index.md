---
title: AsposeAIWebClient
second_title: Aspose.Slides สำหรับ Java API อ้างอิง
description: การทำงานในตัวที่เชื่อมต่อกับ LLM ของ Aspose เอง
type: docs
url: /th/com.aspose.slides/asposeaiwebclient/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่นำไปใช้:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

การทำงานของ [IAIWebClient](../../com.aspose.slides/iaiwebclient) ที่มีมาในตัวที่เชื่อมต่อกับ LLM ของ Aspose เอง นี่คือไคลเอนต์เริ่มต้นที่ใช้โดยคอนสตรัคเตอร์ SlidesAIAgent() ที่ไม่มีพารามิเตอร์

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับจุดสิ้นสุด LLM ของ Aspose เรียกค่าเริ่มต้น |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับจุดสิ้นสุด LLM ของ Aspose เรียกค่าเริ่มต้นโดยใช้ HttpURLConnection ที่จัดการจากภายนอก |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับ URL จุดสิ้นสุดที่กำหนดเอง |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับ URL จุดสิ้นสุดที่กำหนดเองโดยใช้ HttpURLConnection ที่จัดการจากภายนอก |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | ส่งคำสั่งแชทไปยังโมเดล AI และคืนข้อความตอบกลับตามคำสั่งที่ให้ |
| [createConversation()](#createConversation--) | สร้างอินสแตนซ์ของการสนทนา |
| [dispose()](#dispose--) | ปล่อยทรัพยากรที่ใช้งานโดยอินสแตนซ์นี้ |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับจุดสิ้นสุด LLM ของ Aspose เรียกค่าเริ่มต้น นี่คือไคลเอนต์ที่คอนสตรัคเตอร์ SlidesAIAgent() ที่ไม่มีพารามิเตอร์ใช้ ดังนั้นการสร้างแบบชัดเจนจำเป็นเฉพาะเมื่อส่งไคลเอนต์นี้โดยตรงให้กับคอนสตรัคเตอร์ SlidesAIAgent(IAIWebClient)

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

สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับจุดสิ้นสุด LLM ของ Aspose เรียกค่าเริ่มต้นโดยใช้ HttpURLConnection ที่จัดการจากภายนอก อินสแตนซ์ HttpURLConnection ที่ให้มาจะไม่ถูกทำลายโดยอินสแตนซ์นี้และยังคงเป็นของผู้เรียกใช้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | อินสแตนซ์ HttpURLConnection ที่จัดการจากภายนอก |

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

สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับ URL จุดสิ้นสุดที่กำหนดเอง ใช้โอเวอร์โหลดนี้เมื่อคุณมี URL ที่ทีม Aspose.Slides จัดให้; หากไม่ใช่ ให้ใช้โอเวอร์โหลด AsposeAIWebClient() กับ URL เรียกค่าเริ่มต้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL ของจุดสิ้นสุด LLM ของ Aspose ที่ทีม Aspose.Slides จัดให้ |

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

สร้างอินสแตนซ์ของ Aspose AI web client ที่เชื่อมต่อกับ URL จุดสิ้นสุดที่กำหนดเองโดยใช้ HttpURLConnection ที่จัดการจากภายนอก อินสแตนซ์ HttpURLConnection ที่ให้มาจะไม่ถูกทำลายโดยอินสแตนซ์นี้และยังคงเป็นของผู้เรียกใช้ ใช้โอเวอร์โหลดนี้เมื่อคุณมี URL ที่ทีม Aspose.Slides จัดให้และต้องการจัดหา HttpURLConnection ของคุณเอง; หากคุณต้องการเพียง HttpURLConnection ของคุณเองพร้อม URL เรียกค่าเริ่มต้น ให้ใช้โอเวอร์โหลด AsposeAIWebClient(HttpURLConnection) แทน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL ของจุดสิ้นสุด LLM ของ Aspose ที่ทีม Aspose.Slides จัดให้ |
| httpClient | java.net.HttpURLConnection | อินสแตนซ์ HttpURLConnection ที่จัดการจากภายนอก |

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| instruction | java.lang.String | คำสั่งหรือข้อความที่โมเดล AI ต้องประมวลผล |

**ผลลัพธ์:**
java.lang.String - ข้อความที่โมเดล AI สร้างขึ้นเพื่อตอบสนองต่อคำสั่งที่ให้

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

สร้างอินสแตนซ์ของการสนทนา ต่างจากการเรียก AI ปกติ การสนทนาจะรักษาบริบททั้งหมด

**ผลลัพธ์:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - เป็นอินสแตนซ์ของ [IAIConversation](../../com.aspose.slides/iaiconversation)

### dispose() {#dispose--}
```
public final void dispose()
```

ปล่อยทรัพยากรที่ใช้งานโดยอินสแตนซ์นี้.