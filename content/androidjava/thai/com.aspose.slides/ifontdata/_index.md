---
title: IFontData
second_title: Aspose.Slides for Android via Java API Reference
description: แสดงคำนิยามของแบบอักษร.
type: docs
url: /th/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

แสดงคำนิยามของแบบอักษร.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFontName()](#getFontName--) | คืนค่าชื่อแบบอักษร. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | คืนค่าชื่อแบบอักษรโดยแทนที่การอ้างอิงธีมด้วยแบบอักษรที่ใช้จริง. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


คืนค่าชื่อแบบอักษร. Read-only String.

**Returns:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


คืนค่าชื่อแบบอักษรโดยแทนที่การอ้างอิงธีมด้วยแบบอักษรที่ใช้จริง.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | ธีมที่ควรดึงชื่อแบบอักษรตามธีมออกมา จะต้องให้ค่าอย่างถูกต้องโดยผู้เรียก. |

**Returns:**
java.lang.String - ชื่อแบบอักษร.