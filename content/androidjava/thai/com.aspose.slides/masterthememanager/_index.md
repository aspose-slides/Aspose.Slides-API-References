---
title: MasterThemeManager
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ให้การเข้าถึง master theme ของงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/masterthememanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

ให้การเข้าถึง master theme ของงานนำเสนอ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | คืนค่าออบเจกต์ธีมที่บังคับใช้ |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | คืนค่าออบเจกต์ธีมที่บังคับใช้ |
| [createThemeEffective()](#createThemeEffective--) | คืนค่าออบเจกต์ธีม |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | กำหนดว่า OverrideTheme จะเขียนทับธีมที่มีผลสืบทอด (Presentation.MasterTheme) หรือไม่ |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | กำหนดว่า OverrideTheme จะเขียนทับธีมที่มีผลสืบทอด (Presentation.MasterTheme) หรือไม่ |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | นำแผนสีเพิ่มเติมไปใช้กับสไลด์ |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

คืนค่าออบเจกต์ธีมที่บังคับใช้ อ่าน/เขียน [IMasterTheme](../../com.aspose.slides/imastertheme).

**คืนค่า:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

คืนค่าออบเจกต์ธีมที่บังคับใช้ อ่าน/เขียน [IMasterTheme](../../com.aspose.slides/imastertheme).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

คืนค่าออบเจกต์ธีม

**คืนค่า:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

กำหนดว่า OverrideTheme จะเขียนทับธีมที่มีผลสืบทอด (Presentation.MasterTheme) หรือไม่ อ่าน/เขียน boolean

**คืนค่า:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

กำหนดว่า OverrideTheme จะเขียนทับธีมที่มีผลสืบทอด (Presentation.MasterTheme) หรือไม่ อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

นำแผนสีเพิ่มเติมไปใช้กับสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) object. |