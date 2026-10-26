---
title: LinkEmbedDecision
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: กำหนดวิธีที่วัตถุจะถูกประมวลผลระหว่างการบันทึก.
type: docs
url: /th/com.aspose.slides/linkembeddecision/
---
**การสืบทอด:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

กำหนดวิธีที่วัตถุจะถูกประมวลผลระหว่างการบันทึก.
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [Link](#Link) | วัตถุจะถูกจัดเก็บนอกระบบโดยอ้างอิงผ่าน URL |
| [Embed](#Embed) | วัตถุควรฝังลงในไฟล์ที่สร้างขึ้นหากเป็นไปได้ |
| [Ignore](#Ignore) | วัตถุจะถูกละเว้น |
### ลิงก์ {#Link}
```
public static final int Link
```

วัตถุจะถูกจัดเก็บนอกระบบโดยอ้างอิงผ่าน URL

### ฝัง {#Embed}
```
public static final int Embed
```

วัตถุควรฝังลงในไฟล์ที่สร้างขึ้นหากเป็นไปได้ หากการฝังเป็นไปไม่ได้ จะเรียกใช้ GetUrl และขึ้นอยู่กับผลลัพธ์ วัตถุจะถูกอ้างอิงผ่าน URL หรือถูกละเว้น

### ละเว้น {#Ignore}
```
public static final int Ignore
```

วัตถุจะถูกละเว้น.