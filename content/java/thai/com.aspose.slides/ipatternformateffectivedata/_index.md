---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective pattern filling properties.
type: docs
url: /th/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติการเติมลวดลายอย่างมีประสิทธิภาพ.

--------------------

อินเทอร์เฟซนี้ใช้เป็นส่วนหนึ่งของ [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) และ [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

## เมธอด

| Method | Description |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | คืนค่ารูปแบบลวดลาย. |
| [getForeColor()](#getForeColor--) | คืนค่าสีลวดลายพื้นหน้า. |
| [getBackColor()](#getBackColor--) | คืนค่าสีลวดลายพื้นหลัง. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | สร้างภาพไทล์สำหรับการเติมลวดลายด้วยสีที่ระบุ. |

### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

คืนค่ารูปแบบลวดลาย. อ่านอย่างเดียว [PatternStyle](../../com.aspose.slides/patternstyle).

**คืนค่า:**  
byte

### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```

คืนค่าสีลวดลายพื้นหน้า. อ่านอย่างเดียว java.awt.Color.

**คืนค่า:**  
java.awt.Color

### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```

คืนค่าสีลวดลายพื้นหลัง. อ่านอย่างเดียว java.awt.Color.

**คืนค่า:**  
java.awt.Color

### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```

สร้างภาพไทล์สำหรับการเติมลวดลายด้วยสีที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| background | java.awt.Color | สีพื้นหลัง java.awt.Color สำหรับลวดลาย. |
| foreground | java.awt.Color | สีพื้นหน้า java.awt.Color สำหรับลวดลาย. |

**คืนค่า:**  
[IImage](../../com.aspose.slides/iimage) - ไทล์ [IImage](../../com.aspose.slides/iimage).