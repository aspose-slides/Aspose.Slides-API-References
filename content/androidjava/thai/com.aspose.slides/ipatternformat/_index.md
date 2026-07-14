---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /th/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

แสดงถึงรูปแบบลายเพื่อเติมรูปร่าง.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | คืนค่า หรือกำหนดสไตล์ของลวดลาย. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | คืนค่า หรือกำหนดสไตล์ของลวดลาย. |
| [getForeColor()](#getForeColor--) | คืนค่าสีลวดลายพื้นหน้า. |
| [getBackColor()](#getBackColor--) | คืนค่าสีลวดลายพื้นหลัง. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | สร้างภาพไทล์สำหรับการเติมลวดลายด้วยสีที่ระบุ. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | สร้างภาพไทล์สำหรับการเติมลวดลาย. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

คืนค่า หรือกำหนดสไตล์ของลวดลาย. อ่าน/เขียน [PatternStyle](../../com.aspose.slides/patternstyle).

**คืนค่า:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

คืนค่า หรือกำหนดสไตล์ของลวดลาย. อ่าน/เขียน [PatternStyle](../../com.aspose.slides/patternstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

คืนค่าสีลวดลายพื้นหน้า. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

คืนค่าสีลวดลายพื้นหลัง. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```

สร้างภาพไทล์สำหรับการเติมลวดลายด้วยสีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| background | java.lang.Integer | java.lang.Integer ของพื้นหลังสำหรับลวดลาย. |
| foreground | java.lang.Integer | java.lang.Integer ของพื้นหน้า สำหรับลวดลาย. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - ไทล์ android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```

สร้างภาพไทล์สำหรับการเติมลวดลาย.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| styleColor | java.lang.Integer | java.lang.Integer เริ่มต้นที่กำหนดในวัตถุ StyleEx ของ ShapeEx. สีของการเติมอาจพึ่งพานี้. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - ไทล์ android.graphics.Bitmap.