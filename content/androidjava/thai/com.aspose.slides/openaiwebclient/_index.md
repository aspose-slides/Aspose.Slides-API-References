---
title: OpenAIWebClient
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: การดำเนินการในตัว  ที่เชื่อมต่อกับ OpenAI API.
type: docs
url: /th/com.aspose.slides/openaiwebclient/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำตามทั้งหมด:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

การดำเนินการ [IAIWebClient](../../com.aspose.slides/iaiwebclient) ที่ฝังมากับระบบเพื่อเชื่อมต่อกับ OpenAI API.
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | สร้างอินสแตนซ์ของไคลเอ็นต์เว็บ OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | สร้างอินสแตนซ์ของไคลเอ็นต์เว็บ OpenAI ที่ใช้ HttpClient ที่จัดการโดยภายนอก. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | สร้างอินสแตนซ์ของการสนทนา. |
| [close()](#close--) | ปลดปล่อยทรัพยากรที่ใช้โดยอินสแตนซ์นี้. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

สร้างอินสแตนซ์ของไคลเอ็นต์เว็บ OpenAI.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| model | java.lang.String | โมเดลภาษาของ OpenAI. ค่าที่เป็นไปได้: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
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

สร้างอินสแตนซ์ของไคลเอ็นต์เว็บ OpenAI ที่ใช้ HttpClient ที่จัดการโดยภายนอก. HttpClient ที่ให้มาจะไม่ถูกทำลายโดยอินสแตนซ์นี้และยังคงเป็นของผู้เรียกใช้.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| model | java.lang.String | โมเดลภาษาของ OpenAI. ค่าที่เป็นไปได้: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | คีย์ API ของ OpenAI |
| organizationId | java.lang.String | รหัสองค์กร (ไม่บังคับ) |
| httpClient | java.net.HttpURLConnection | อินสแตนซ์ HttpClient ที่จัดการโดยภายนอก |

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

ส่งคำสั่งแชทไปยังโมเดล AI โดยใช้อินสแตนซ์ HttpConnection ที่ให้มาและส่งคืนข้อความตอบกลับต่อคำสั่งที่กำหนด.

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

สร้างอินสแตนซ์ของการสนทนา. แตกต่างจากการเรียก AI ปกติ การสนทนาจะคงบริบททั้งหมดไว้.

**คืนค่า:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - อินสแตนซ์ [IAIConversation](../../com.aspose.slides/iaiconversation)
### close() {#close--}
```
public final void close()
```

ปลดปล่อยทรัพยากรที่ใช้โดยอินสแตนซ์นี้.