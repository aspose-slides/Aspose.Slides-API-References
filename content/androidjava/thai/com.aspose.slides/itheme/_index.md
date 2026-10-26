---
title: ITheme
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงธีม.
type: docs
url: /th/com.aspose.slides/itheme/
---
**ส่วนต่อประสานที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

แสดงถึงธีมหนึ่ง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | คืนค่าสกีมสี. |
| [getFontScheme()](#getFontScheme--) | คืนสกีมฟอนต์. |
| [getFormatScheme()](#getFormatScheme--) | คืนสกีมรูปแบบรูปร่าง. |
| [getEffective()](#getEffective--) | ดึงข้อมูลธีมที่มีผลโดยใช้การสืบทอด. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


คืนค่าสกีมสี. อ่านอย่างเดียว [IColorScheme](../../com.aspose.slides/icolorscheme).

**คืนค่า:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


คืนสกีมฟอนต์. อ่านอย่างเดียว [IFontScheme](../../com.aspose.slides/ifontscheme).

**คืนค่า:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


คืนสกีมรูปแบบรูปร่าง. อ่านอย่างเดียว [IFormatScheme](../../com.aspose.slides/iformatscheme).

**คืนค่า:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


ดึงข้อมูลธีมที่มีผลโดยใช้การสืบทอด.

**คืนค่า:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - เป็น [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).