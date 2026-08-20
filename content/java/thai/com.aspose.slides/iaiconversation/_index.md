---
title: IAIConversation
second_title: Aspose.Slides for Java API Reference
description: เป็นตัวแทนของอินสแตนซ์การสนทนา.
type: docs
url: /th/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

เป็นตัวแทนของอินสแตนซ์การสนทนา. ไม่เหมือนการเรียก AI ธรรมดา การสนทนาจะรักษาบริบททั้งหมดไว้
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | ส่งข้อความคำขอการสนทนารวมถึงบริบททั้งหมดและส่งกลับการตอบกลับ. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

ส่งข้อความคำขอการสนทนารวมถึงบริบททั้งหมดและส่งกลับการตอบกลับ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| instruction | java.lang.String | คำสั่งหรือข้อความที่จะประมวลผลโดยโมเดล AI. |

**คืนค่า:**
java.lang.String - ข้อความที่สร้างโดยโมเดล AI เพื่อตอบสนองต่อคำสั่งที่ให้ในบริบทการสนทนา.