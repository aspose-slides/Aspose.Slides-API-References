---
title: LinkEmbedDecision
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: กำหนดว่าวัตถุจะถูกประมวลผลอย่างไรระหว่างการบันทึก.
type: docs
url: /th/com.aspose.slides/linkembeddecision/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

กำหนดว่าวัตถุจะถูกประมวลผลอย่างไรระหว่างการบันทึก.
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [Link](#Link) | วัตถุจะถูกจัดเก็บภายนอก, อ้างอิงโดย URL |
| [Embed](#Embed) | วัตถุควรฝังลงในไฟล์ที่สร้างขึ้นหากเป็นไปได้. |
| [Ignore](#Ignore) | วัตถุจะถูกละเลย. |
### ลิงก์ {#Link}
```
public static final int Link
```

วัตถุจะถูกจัดเก็บภายนอก, อ้างอิงโดย URL

### ฝัง {#Embed}
```
public static final int Embed
```

วัตถุควรฝังลงในไฟล์ที่สร้างขึ้นหากเป็นไปได้. หากไม่สามารถฝังได้, GetUrl จะถูกเรียกใช้และ, ขึ้นอยู่กับผลลัพธ์, วัตถุจะอ้างอิงโดย URL หรือจะถูกละเลย.

### ละเลย {#Ignore}
```
public static final int Ignore
```

วัตถุจะถูกละเลย.