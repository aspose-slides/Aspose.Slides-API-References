---
title: BaseOverrideThemeManager
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: คลาสฐานสำหรับคลาสที่ให้การเข้าถึงประเภทต่าง ๆ ของธีมที่ถูกแทนที่
type: docs
url: /th/com.aspose.slides/baseoverridethememanager/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**All Implemented Interfaces:**  
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)  
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

คลาสฐานสำหรับคลาสที่ให้การเข้าถึงประเภทต่าง ๆ ของธีมที่ถูกแทนที่  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | ส่งคืนอ็อบเจ็กต์ธีมที่ถูกแทนที่ |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | ส่งคืนอ็อบเจ็กต์ธีมที่ถูกแทนที่ |
| [createThemeEffective()](#createThemeEffective--) | ส่งคืนอ็อบเจ็กต์ธีม |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | กำหนดว่า OverrideTheme แทนที่ธีมที่มีประสิทธิภาพที่สืบทอดหรือไม่ |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | ใช้โหมดสีเพิ่มเติมกับสไลด์ |

### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

ส่งคืนอ็อบเจ็กต์ธีมที่ถูกแทนที่. อ่าน/เขียน [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**คืนค่า:**  
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)

### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

ส่งคืนอ็อบเจ็กต์ธีมที่ถูกแทนที่. อ่าน/เขียน [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

ส่งคืนอ็อบเจ็กต์ธีม.

**คืนค่า:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

กำหนดว่า OverrideTheme แทนที่ธีมที่มีประสิทธิภาพที่สืบทอดหรือไม่. เพื่อเปิดใช้งาน OverrideTheme สำหรับการแทนที่ ให้ใช้เมธอด OverrideTheme.Init\*(). เพื่อปิดการใช้งาน OverrideTheme จากการแทนที่ ให้ใช้เมธอด OverrideTheme.Clear(). บูลีนอ่านอย่างเดียว.

**คืนค่า:**  
boolean

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

ใช้โหมดสีเพิ่มเติมกับสไลด์.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | อ็อบเจ็กต์ [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) |
