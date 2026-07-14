---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งมีคุณสมบัติการเติมลวดลายที่มีประสิทธิภาพ.
type: docs
url: /th/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติการเติมลวดลายที่มีประสิทธิภาพ.

--------------------

อินเทอร์เฟซนี้ใช้เป็นส่วนหนึ่งของ [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) และ [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | คืนค่ารูปแบบลวดลาย. |
| [getForeColor()](#getForeColor--) | คืนค่าสีแนวหน้าลวดลาย. |
| [getBackColor()](#getBackColor--) | คืนค่าสีพื้นหลังลวดลาย. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | สร้างภาพไทล์สำหรับการเติมลวดลายด้วยสีที่ระบุ. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


คืนค่ารูปแบบลวดลาย. อ่านอย่างเดียว [PatternStyle](../../com.aspose.slides/patternstyle).

**คืนค่า:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```


คืนค่าสีแนวหน้าลวดลาย. อ่านอย่างเดียว java.lang.Integer.

**คืนค่า:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```


คืนค่าสีพื้นหลังลวดลาย. อ่านอย่างเดียว java.lang.Integer.

**คืนค่า:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```


สร้างภาพไทล์สำหรับการเติมลวดลายด้วยสีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| background | java.lang.Integer | java.lang.Integer ของพื้นหลังสำหรับลวดลาย. |
| foreground | java.lang.Integer | java.lang.Integer ของแนวหน้าสำหรับลวดลาย. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - ไทล์ [IImage](../../com.aspose.slides/iimage).