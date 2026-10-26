---
title: PatternFormat
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงลวดลายที่ใช้เติมรูปทรง
type: docs
url: /th/com.aspose.slides/patternformat/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

เป็นแพทเทิร์นเพื่อเติมรูปทรง
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | คืนค่า หรือกำหนดสไตล์ของลวดลาย |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | คืนค่า หรือกำหนดสไตล์ของลวดลาย |
| [getForeColor()](#getForeColor--) | คืนค่าสีพื้นหน้าของลวดลาย |
| [getBackColor()](#getBackColor--) | คืนค่าสีพื้นหลังของลวดลาย |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | สร้างภาพไทล์สำหรับการเติมลวดลายด้วยสีที่ระบุ |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | สร้างภาพไทล์สำหรับการเติมลวดลาย |

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่าน-อย่าง-เดียว long.

**คืนค่า:**
long

### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

คืนค่า หรือกำหนดสไตล์ของลวดลาย. อ่าน/เขียน [PatternStyle](../../com.aspose.slides/patternstyle).

**คืนค่า:**
byte

### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

คืนค่า หรือกำหนดสไตล์ของลวดลาย. อ่าน/เขียน [PatternStyle](../../com.aspose.slides/patternstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

คืนค่าสีพื้นหน้าของลวดลาย. อ่าน-อย่าง-เดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

คืนค่าสีพื้นหลังของลวดลาย. อ่าน-อย่าง-เดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```

สร้างภาพไทล์สำหรับการเติมลวดลายด้วยสีที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| background | java.lang.Integer | สีพื้นหลัง java.lang.Integer สำหรับลวดลาย |
| foreground | java.lang.Integer | สีพื้นหน้า java.lang.Integer สำหรับลวดลาย |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - ไทล์ [IImage](../../com.aspose.slides/iimage).

### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```

สร้างภาพไทล์สำหรับการเติมลวดลาย

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| styleColor | java.lang.Integer | java.lang.Integer เริ่มต้น |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - ไทล์ [IImage](../../com.aspose.slides/iimage).