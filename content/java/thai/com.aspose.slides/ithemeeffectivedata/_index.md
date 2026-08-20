---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective theme properties.
type: docs
url: /th/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติของธีมที่มีผล

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [ITheme](../../com.aspose.slides/itheme) เพื่อคืนค่าการจัดรูปแบบที่มีผลโดยมีการสืบทอดที่ใช้

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | คืนค่าโครงร่างสี |
| [getFontScheme()](#getFontScheme--) | คืนค่าโครงร่างแบบอักษร |
| [getFormatScheme()](#getFormatScheme--) | คืนค่าโครงร่างรูปแบบรูปร่าง |

### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```

คืนค่าโครงร่างสี

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**คืนค่า:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - โครงร่างสี [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)

### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

คืนค่าโครงร่างแบบอักษร. อ่านอย่างเดียว [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**คืนค่า:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)

### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

คืนค่าโครงร่างรูปแบบรูปร่าง. อ่านอย่างเดียว [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**คืนค่า:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)