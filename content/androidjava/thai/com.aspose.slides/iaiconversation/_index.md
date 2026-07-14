---
title: IAIConversation
second_title: Aspose.Slides for Android via Java API Reference
description: เป็นตัวแทนของอินสแตนซ์การสนทนา.
type: docs
url: /th/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

เป็นตัวแทนของอินสแตนซ์การสนทนา. แตกต่างจากการเรียก AI ปกติ การสนทนาจะรักษาบริบททั้งหมดไว้.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | ส่งข้อความคำขอการสนทนาพร้อมบริบททั้งหมดและส่งคืนผลตอบกลับ. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

ส่งข้อความคำขอการสนทนาพร้อมบริบททั้งหมดและส่งคืนผลตอบกลับ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| instruction | java.lang.String | คำสั่งหรือข้อความที่จะดำเนินการโดยโมเดล AI. |

**ผลลัพธ์:**
java.lang.String - ข้อความที่สร้างโดยโมเดล AI เพื่อตอบสนองต่อคำสั่งที่ให้ไว้ในบริบทของการสนทนา.