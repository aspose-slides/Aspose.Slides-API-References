---
title: IPatternFormat
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: เป็นตัวแทนของรูปแบบที่ใช้เติมรูปร่าง.
type: docs
url: /th/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

เป็นตัวแทนของรูปแบบที่ใช้เติมรูปร่าง.
## เมธอด

| Method | Description |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | คืนค่า หรือกำหนดสไตล์รูปแบบ. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | คืนค่า หรือกำหนดสไตล์รูปแบบ. |
| [getForeColor()](#getForeColor--) | คืนค่าสีพื้นหน้า. |
| [getBackColor()](#getBackColor--) | คืนค่าสีพื้นหลัง. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | สร้างภาพไทล์สำหรับการเติมลายด้วยสีที่ระบุ. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | สร้างภาพไทล์สำหรับการเติมลาย. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

คืนค่า หรือกำหนดสไตล์รูปแบบ. อ่าน/เขียน [PatternStyle](../../com.aspose.slides/patternstyle).

**Returns:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

คืนค่า หรือกำหนดสไตล์รูปแบบ. อ่าน/เขียน [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

คืนค่าสีพื้นหน้า. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

คืนค่าสีพื้นหลัง. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```

สร้างภาพไทล์สำหรับการเติมลายด้วยสีที่ระบุ.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| background | java.awt.Color | สีพื้นหลัง java.awt.Color สำหรับลาย. |
| foreground | java.awt.Color | สีพื้นหน้า java.awt.Color สำหรับลาย. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - ไทล์ java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```

สร้างภาพไทล์สำหรับการเติมลาย.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | สี java.awt.Color เริ่มต้นที่กำหนดในวัตถุ StyleEx ของ ShapeEx. สีของการเติมอาจขึ้นอยู่กับค่านี้. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - ไทล์ java.awt.image.BufferedImage.