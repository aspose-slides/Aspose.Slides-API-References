---
title: Zip64Mode
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ระบุช่วงเวลาที่จะใช้ส่วนขยายรูปแบบ ZIP64 สำหรับไฟล์ OpenXML.
type: docs
url: /th/com.aspose.slides/zip64mode/
---
**การสืบทอด:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

ระบุเวลาที่ควรใช้ส่วนขยายรูปแบบ ZIP64 สำหรับไฟล์ OpenXML.

--------------------

ไฟล์ OpenXML เป็นไฟล์ ZIP-archive ที่มีขีดจำกัด 4 GB (2^32 ไบต์) สำหรับขนาดไฟล์ที่ไม่ได้บีบอัด, ขนาดไฟล์ที่บีบอัด, และขนาดรวมของไฟล์อาร์ไคฟ์, รวมถึงขีดจำกัด 65,535 (2^16-1) ไฟล์ในอาร์ไคฟ์ด้วย ส่วนขยายรูปแบบ ZIP64 จะเพิ่มขีดจำกัดเหล่านี้เป็น 2^64.
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [Never](#Never) | ไม่ใช้ส่วนขยายรูปแบบ ZIP64. |
| [IfNecessary](#IfNecessary) | ใช้ส่วนขยายรูปแบบ ZIP64 หากจำเป็น. |
| [Always](#Always) | ใช้ส่วนขยายรูปแบบ ZIP64 เสมอ. |
### Never {#Never}
```
public static final int Never
```


ไม่ใช้ส่วนขยายรูปแบบ ZIP64.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```


ใช้ส่วนขยายรูปแบบ ZIP64 หากจำเป็น.

### Always {#Always}
```
public static final int Always
```


ใช้ส่วนขยายรูปแบบ ZIP64 เสมอ.