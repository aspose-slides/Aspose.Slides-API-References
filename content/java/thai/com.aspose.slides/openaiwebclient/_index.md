---
title: OpenAIWebClient
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: การดำเนินการในตัวที่เชื่อมต่อกับ OpenAI API.
type: docs
url: /th/com.aspose.slides/openaiwebclient/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่ทำไว้ทั้งหมด:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

การดำเนินการ [IAIWebClient](../../com.aspose.slides/iaiwebclient) ที่สร้างไว้ล่วงหน้าเชื่อมต่อกับ API ของ OpenAI.
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | รายละเอียด |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | สร้างอินสแตนซ์ของไคลเอนต์เว็บ OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | สร้างอินสแตนซ์ของไคลเอนต์เว็บ OpenAI ที่ใช้ HttpClient ที่จัดการจากภายนอก. |
## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | สร้างอินสแตนซ์ของการสนทนา. |
| [close()](#close--) | ปลดปล่อยทรัพยากรที่ใช้โดยอินสแตนซ์นี้. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

สร้างอินสแตนซ์ของไคลเอนต์เว็บ OpenAI.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| model | java.lang.String | โมเดลภาษาของ OpenAI ค่าที่เป็นไปได้: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | คีย์ API ของ OpenAI. |
| organizationId | java.lang.String | รหัสองค์กร (ไม่บังคับ). |

```
using (OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |
### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

สร้างอินสแตนซ์ของไคลเอนต์เว็บ OpenAI ที่ใช้ HttpClient ที่จัดการจากภายนอก HttpClient ที่ระบุจะไม่ถูกทำลายโดยอินสแตนซ์นี้และยังคงเป็นของผู้เรียกใช้.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| model | java.lang.String | โมเดลภาษของ OpenAI ค่าที่เป็นไปได้: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | คีย์ API ของ OpenAI |
| organizationId | java.lang.String | รหัสองค์กร (ไม่บังคับ) |
| httpClient | java.net.HttpURLConnection | อินสแตนซ์ HttpClient ที่จัดการจากภายนอก |

```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null, httpClient);
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

ส่งคำสั่งแชทไปยังโมเดล AI โดยใช้อินสแตนซ์ HttpConnection ที่ให้มาและคืนข้อความตอบกลับสำหรับคำสั่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| instruction | java.lang.String |  |

**ผลลัพธ์:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

สร้างอินสแตนซ์ของการสนทนา ต่างจากการเรียก AI ปกติ การสนทนาจะรักษาบริบททั้งหมดไว้.

**ผลลัพธ์:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - อินสแตนซ์ของ [IAIConversation](../../com.aspose.slides/iaiconversation)
### close() {#close--}
```
public final void close()
```

ปลดปล่อยทรัพยากรที่ใช้โดยอินสแตนซ์นี้.