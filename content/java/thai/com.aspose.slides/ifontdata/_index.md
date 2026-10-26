---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description: แสดงถึงการกำหนดแบบอักษร.
type: docs
url: /th/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

แสดงถึงการกำหนดแบบอักษร.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFontName()](#getFontName--) | ส่งคืนชื่อแบบอักษร. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | ส่งคืนชื่อแบบอักษรโดยแทนที่การอ้างอิงธีมด้วยแบบอักษรที่ใช้จริง. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

ส่งคืนชื่อแบบอักษร. อ่านอย่างเดียว String.

**ส่งคืน:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

ส่งคืนชื่อแบบอักษรโดยแทนที่การอ้างอิงธีมด้วยแบบอักษรที่ใช้จริง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | ธีมที่ควรนำชื่อแบบอักษรตามธีมมาใช้. ขึ้นอยู่กับผู้เรียกเพื่อให้ค่าเป็นค่าที่ถูกต้อง. |

**ส่งคืน:**
java.lang.String - ชื่อแบบอักษร.