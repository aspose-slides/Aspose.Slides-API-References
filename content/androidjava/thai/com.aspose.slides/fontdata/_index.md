---
title: FontData
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง Java API
description: แสดงถึงการกำหนดแบบอักษร.
type: docs
url: /th/com.aspose.slides/fontdata/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

เป็นการกำหนดแบบอักษร. ไม่เปลี่ยนแปลง.
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | สร้างอ็อบเจกต์ FontData ใหม่ด้วยชื่อแบบอักษรที่กำหนด. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFontName()](#getFontName--) | ส่งคืนชื่อแบบอักษร. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | ส่งคืนชื่อแบบอักษรโดยแทนที่การอ้างอิงธีมด้วยแบบอักษรที่ใช้งานจริง. |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าตัวอย่าง FontData สองตัวเท่ากันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับชนิดเฉพาะ, เหมาะสำหรับใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่น ตารางแฮช. |
| [toString()](#toString--) | ส่งคืนการแสดงผลเป็นสตริง. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

สร้างอ็อบเจกต์ FontData ใหม่ด้วยชื่อแบบอักษรที่กำหนด.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontName | java.lang.String | ชื่อแบบอักษร. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

ส่งคืนชื่อแบบอักษร. String อ่าน/เขียน.

**Returns:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

ส่งคืนชื่อแบบอักษรโดยแทนที่การอ้างอิงธีมด้วยแบบอักษรที่ใช้งานจริง.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | ธีมที่ควรนำชื่อแบบอักษรตามธีมมาจาก. ขึ้นอยู่กับผู้เรียกเพื่อให้ค่าที่ถูกต้อง. ดู [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Returns:**
java.lang.String - ชื่อแบบอักษร.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่าตัวอย่าง FontData สองตัวเท่ากันหรือไม่.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | FontData ที่จะเปรียบเทียบกับ FontData ปัจจุบัน. |

**Returns:**
boolean - **true** หาก FontData ที่ระบุเท่ากับ FontData ปัจจุบัน; มิฉะนั้น **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับชนิดเฉพาะ, เหมาะสำหรับใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่น ตารางแฮช.

**Returns:**
int - รหัสแฮชของ FontData.
### toString() {#toString--}
```
public String toString()
```

ส่งคืนการแสดงผลเป็นสตริง.

**Returns:**
java.lang.String - การแสดงผลเป็นสตริง.