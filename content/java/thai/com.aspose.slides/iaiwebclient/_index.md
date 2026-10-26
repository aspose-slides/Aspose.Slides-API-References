---
title: IAIWebClient
second_title: Aspose.Slides for Java API Reference
description: ส่วนต่อประสานไคลเอนต์ AI สำหรับเว็บ
type: docs
url: /th/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI Web client interface. This interface enables to substitute different AI language models. Classes that implement this interface are supposed to be used along with SlidesAIAgent.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sends a chat instruction to the AI model using a provided HttpConnection instance and return response message to the given instruction. |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

ส่งคำสั่งแชทไปยังโมเดล AI โดยใช้อินสแตนซ์ HttpConnection ที่ให้มาและคืนข้อความตอบกลับสำหรับคำสั่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| instruction | java.lang.String | คำสั่งหรือข้อความที่ต้องการให้โมเดล AI ประมวลผล |

**คืนค่า:**
java.lang.String - ข้อความที่โมเดล AI สร้างขึ้นเพื่อตอบสนองต่อคำสั่งที่ให้

### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

สร้างอินสแตนซ์ของการสนทนา โดยการสนทนาจะคงบริบททั้งหมดไว้แตกต่างจากการเรียก AI ปกติ

**คืนค่า:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - อินสแตนซ์ของ [IAIConversation](../../com.aspose.slides/iaiconversation)