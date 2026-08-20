---
title: FontData
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงคำนิยามของแบบอักษร.
type: docs
url: /th/com.aspose.slides/fontdata/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่นำไปใช้:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

แสดงคำนิยามของแบบอักษร แบบคงที่.
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Creates a new FontData object with the specified font name. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFontName()](#getFontName--) | ส่งคืนชื่อแบบอักษร. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | ส่งคืนชื่อแบบอักษรโดยแทนที่การอ้างอิงธีมด้วยแบบอักษรที่ใช้จริง. |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าระหว่างสองอินสแตนซ์ของ FontData เท่ากันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทที่กำหนด ใช้ได้กับอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่น ตารางแฮช. |
| [toString()](#toString--) | ส่งคืนการแสดงผลเป็นสตริง. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

สร้างอ็อบเจ็กต์ FontData ใหม่ด้วยชื่อแบบอักษรที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontName | java.lang.String | ชื่อแบบอักษร. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

ส่งคืนชื่อแบบอักษร อ่าน/เขียน String.

**ส่งคืน:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

ส่งคืนชื่อแบบอักษรโดยแทนที่การอ้างอิงธีมด้วยแบบอักษรที่ใช้จริง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | ธีมที่ควรใช้เพื่อดึงชื่อแบบอักษรที่กำหนดธีม ค่าต้องมาจากผู้เรียก ดู [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**ส่งคืน:**
java.lang.String - ชื่อแบบอักษร.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่าระหว่างสองอินสแตนซ์ของ FontData เท่ากันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | FontData ที่จะเปรียบเทียบกับ FontData ปัจจุบัน. |

**ส่งคืน:**
boolean - **true** หาก FontData ที่ระบุเท่ากับ FontData ปัจจุบัน; มิฉะนั้น **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทที่กำหนด ใช้ได้กับอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่น ตารางแฮช.

**ส่งคืน:**
int - แฮชโค้ดของ FontData.
### toString() {#toString--}
```
public String toString()
```

ส่งคืนการแสดงผลเป็นสตริง.

**ส่งคืน:**
java.lang.String - การแสดงผลเป็นสตริง.