---
title: OpenAIWebClient
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ไคลเอนต์เว็บ OpenAI แบบน้ำหนักเบาที่สร้างในตัว
type: docs
url: /th/com.aspose.slides/openaiwebclient/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

ไคลเอนต์เว็บ OpenAI แบบน้ำหนักเบาที่สร้างในตัว
## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | สร้างอินสแตนซ์ของไคลเอนต์เว็บ OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | สร้างอินสแตนซ์ของไคลเอนต์เว็บ OpenAI. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | ส่งคำสั่งแชทไปยังโมเดล AI โดยใช้อินสแตนซ์ที่จัดการโดยภายนอกและคืนข้อความตอบกลับสำหรับคำสั่งที่ให้. |
| [createConversation()](#createConversation--) | สร้างอินสแตนซ์การสนทนา. |
| [close()](#close--) | ปล่อยทรัพยากรที่ใช้โดยอินสแตนซ์นี้. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```


สร้างอินสแตนซ์ของไคลเอนต์เว็บ OpenAI.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| model | java.lang.String | โมเดลภาษาของ OpenAI. ค่าที่เป็นไปได้: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | คีย์ API ของ OpenAI |
| organizationId | java.lang.String | ID ขององค์กร (ไม่บังคับ) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```


สร้างอินสแตนซ์ของไคลเอนต์เว็บ OpenAI.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| model | java.lang.String | โมเดลภาษาของ OpenAI. ค่าที่เป็นไปได้: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | คีย์ API ของ OpenAI |
| organizationId | java.lang.String | ID ขององค์กร (ไม่บังคับ) |
| httpClient | java.net.HttpURLConnection | อินสแตนซ์ HttpURLConnection ที่จัดการโดยภายนอก. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


ส่งคำสั่งแชทไปยังโมเดล AI โดยใช้อินสแตนซ์ที่จัดการโดยภายนอกและคืนข้อความตอบกลับสำหรับคำสั่งที่ให้.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| instruction | java.lang.String | คำสั่งหรือข้อความที่ต้องการให้โมเดล AI ประมวลผล |

**ค่าที่ส่งกลับ:**
java.lang.String - ข้อความที่สร้างโดยโมเดล AI เพื่อตอบสนองต่อคำสั่งที่ให้

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


สร้างอินสแตนซ์การสนทนา. แตกต่างจากการเรียก AI ปกติ, การสนทนาจะเก็บบริบททั้งหมดไว้.

**ค่าที่ส่งกลับ:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - อินสแตนซ์ของ [IAIConversation](../../com.aspose.slides/iaiconversation)

### close() {#close--}
```
public final void close()
```


ปล่อยทรัพยากรที่ใช้โดยอินสแตนซ์นี้.