---
title: Zip64Mode
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: ระบุเมื่อใดควรใช้ส่วนขยายรูปแบบ ZIP64 สำหรับไฟล์ OpenXML
type: docs
url: /th/com.aspose.slides/zip64mode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

ระบุเมื่อใดควรใช้ส่วนขยายรูปแบบ ZIP64 สำหรับไฟล์ OpenXML

--------------------

ไฟล์ OpenXML เป็นไฟล์ ZIP-archive ที่มีขีดจำกัด 4 GB (2^32 bytes) สำหรับขนาดไฟล์ที่ไม่ได้บีบอัด, ขนาดไฟล์ที่บีบอัด, และขนาดทั้งหมดของอาร์ไคฟ์ รวมถึงขีดจำกัด 65 535 (2^16-1) ไฟล์ในอาร์ไคฟ์ ส่วนขยายรูปแบบ ZIP64 เพิ่มขีดจำกัดเหล่านี้เป็น 2^64

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [Never](#Never) | ไม่ใช้ส่วนขยายรูปแบบ ZIP64 |
| [IfNecessary](#IfNecessary) | ใช้ส่วนขยายรูปแบบ ZIP64 หากจำเป็น |
| [Always](#Always) | ใช้ส่วนขยายรูปแบบ ZIP64 เสมอ |
### ไม่ใช้ {#Never}
```
public static final int Never
```

ไม่ใช้ส่วนขยายรูปแบบ ZIP64

### หากจำเป็น {#IfNecessary}
```
public static final int IfNecessary
```

ใช้ส่วนขยายรูปแบบ ZIP64 หากจำเป็น

### เสมอ {#Always}
```
public static final int Always
```

ใช้ส่วนขยายรูปแบบ ZIP64 เสมอ