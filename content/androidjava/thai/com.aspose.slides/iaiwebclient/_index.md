---
title: IAIWebClient
second_title: Aspose.Slides for Android via Java API Reference
description: อินเทอร์เฟซลูกค้า AI เว็บ.
type: docs
url: /th/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

อินเทอร์เฟซลูกค้า AI เว็บ นี้ช่วยให้สามารถแทนที่โมเดลภาษา AI ต่าง ๆ ได้ คลาสที่ทำการ Implement อินเทอร์เฟซนี้ควรใช้ร่วมกับ SlidesAIAgent.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | ส่งคำสั่งแชทไปยังโมเดล AI โดยใช้อินสแตนซ์ HttpConnection ที่ให้มาและคืนข้อความตอบกลับตามคำสั่งที่ระบุ |
| [createConversation()](#createConversation--) | สร้างอินสแตนซ์การสนทนา |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

ส่งคำสั่งแชทไปยังโมเดล AI โดยใช้อินสแตนซ์ HttpConnection ที่ให้มาและคืนข้อความตอบกลับตามคำสั่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| instruction | java.lang.String | คำสั่งหรือข้อความที่ต้องการให้โมเดล AI ประมวลผล |

**คืนค่า:**
java.lang.String - ข้อความที่โมเดล AI สร้างขึ้นเป็นการตอบสนองต่อคำสั่งที่ระบุ

### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

สร้างอินสแตนซ์การสนทนา ซึ่งแตกต่างจากการเรียก AI ปกติ การสนทนาจะเก็บบริบททั้งหมดไว้

**คืนค่า:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - อินสแตนซ์ของ [IAIConversation](../../com.aspose.slides/iaiconversation)