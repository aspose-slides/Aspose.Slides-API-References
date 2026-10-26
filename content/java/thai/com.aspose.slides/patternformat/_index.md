---
title: PatternFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงรูปแบบเพื่อเติมรูปทรง
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

แสดงถึงรูปแบบเพื่อเติมรูปทรง.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | คืนค่า หรือกำหนดสไตล์ของรูปแบบ. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | คืนค่า หรือกำหนดสไตล์ของรูปแบบ. |
| [getForeColor()](#getForeColor--) | คืนค่าสีพื้นหน้าแบบลาย. |
| [getBackColor()](#getBackColor--) | คืนค่าสีพื้นหลังแบบลาย. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | สร้างภาพไทล์สำหรับการเติมรูปแบบด้วยสีที่กำหนด. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | สร้างภาพไทล์สำหรับการเติมรูปแบบ. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียวแบบ long.

**คืนค่า:**
long

### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

คืนค่า หรือกำหนดสไตล์ของรูปแบบ. อ่าน/เขียน [PatternStyle](../../com.aspose.slides/patternstyle).

**คืนค่า:**
byte

### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

คืนค่า หรือกำหนดสไตล์ของรูปแบบ. อ่าน/เขียน [PatternStyle](../../com.aspose.slides/patternstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

คืนค่าสีพื้นหน้าแบบลาย. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

คืนค่าสีพื้นหลังแบบลาย. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

สร้างภาพไทล์สำหรับการเติมรูปแบบด้วยสีที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| background | java.awt.Color | สีพื้นหลัง java.awt.Color สำหรับรูปแบบ. |
| foreground | java.awt.Color | สีพื้นหน้า java.awt.Color สำหรับรูปแบบ. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - ไทล์ [IImage](../../com.aspose.slides/iimage).

### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

สร้างภาพไทล์สำหรับการเติมรูปแบบ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| styleColor | java.awt.Color | สี java.awt.Color เริ่มต้น |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - ไทล์ [IImage](../../com.aspose.slides/iimage).