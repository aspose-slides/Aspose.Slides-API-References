---
title: ITheme
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แทนธีมหนึ่ง.
type: docs
url: /th/com.aspose.slides/itheme/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

แทนธีมหนึ่ง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | คืนค่าโครงสร้างสี. |
| [getFontScheme()](#getFontScheme--) | คืนค่าโครงสร้างฟอนต์. |
| [getFormatScheme()](#getFormatScheme--) | คืนค่าโครงสร้างรูปแบบรูปร่าง. |
| [getEffective()](#getEffective--) | ดึงข้อมูลธีมที่มีผลพร้อมการสืบทอด. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

คืนค่าโครงสร้างสี. อ่านอย่างเดียว [IColorScheme](../../com.aspose.slides/icolorscheme).

**คืนค่า:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

คืนค่าโครงสร้างฟอนต์. อ่านอย่างเดียว [IFontScheme](../../com.aspose.slides/ifontscheme).

**คืนค่า:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

คืนค่าโครงสร้างรูปแบบรูปร่าง. อ่านอย่างเดียว [IFormatScheme](../../com.aspose.slides/iformatscheme).

**คืนค่า:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```

ดึงข้อมูลธีมที่มีผลพร้อมการสืบทอด.

**คืนค่า:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - หนึ่ง [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).