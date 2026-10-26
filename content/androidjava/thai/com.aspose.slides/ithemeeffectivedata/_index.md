---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: อ็อบเจ็กต์ไม่เปลี่ยนแปลงซึ่งมีคุณสมบัติของธีมที่มีผลบังคับใช้งาน.
type: docs
url: /th/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

อ็อบเจ็กต์ไม่เปลี่ยนแปลงซึ่งมีคุณสมบัติของธีมที่มีผลบังคับใช้งาน.

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [ITheme](../../com.aspose.slides/itheme) เพื่อคืนค่าการจัดรูปแบบที่มีผลบังคับใช้งานพร้อมกับการสืบทอด.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | คืนสคีมสี. |
| [getFontScheme()](#getFontScheme--) | คืนสกีมแบบอักษร. |
| [getFormatScheme()](#getFormatScheme--) | คืนสกีมรูปแบบรูปร่าง. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```


คืนสคีมสี.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| styleColor | java.lang.Integer | Color java.lang.Integer |

**ผลลัพธ์:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - สคีมสี [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


คืนสกีมแบบอักษร. อ่านอย่างเดียว [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**ผลลัพธ์:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


คืนสกีมรูปแบบรูปร่าง. อ่านอย่างเดียว [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**ผลลัพธ์:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)