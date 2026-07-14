---
title: BaseOverrideThemeManager
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: คลาสพื้นฐานสำหรับคลาสที่ให้การเข้าถึงธีมที่ถูกแทนที่ประเภทต่าง ๆ
type: docs
url: /th/com.aspose.slides/baseoverridethememanager/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

คลาสพื้นฐานสำหรับคลาสที่ให้การเข้าถึงธีมที่ถูกแทนที่ประเภทต่างๆ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | คืนค่าอ็อบเจ็กต์ธีมที่แทนที่ |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | คืนค่าอ็อบเจ็กต์ธีมที่แทนที่ |
| [createThemeEffective()](#createThemeEffective--) | คืนค่าอ็อบเจ็กต์ธีม |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | กำหนดว่า OverrideTheme แทนที่ธีมที่มีผลสืบทอดหรือไม่ |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | ใช้สคีมสีเพิ่มเติมกับสไลด์ |

### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

คืนค่าอ็อบเจ็กต์ธีมที่แทนที่. อ่าน/เขียน [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**คืนค่า:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

คืนค่าอ็อบเจ็กต์ธีมที่แทนที่. อ่าน/เขียน [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

คืนค่าอ็อบเจ็กต์ธีม

**คืนค่า:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

กำหนดว่า OverrideTheme แทนที่ธีมที่มีผลสืบทอดหรือไม่. เพื่อเปิดใช้งาน OverrideTheme สำหรับการแทนที่ให้ใช้เมธอด OverrideTheme.Init\*(). เพื่อปิดการใช้งาน OverrideTheme จากการแทนที่ให้ใช้เมธอด OverrideTheme.Clear(). อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

ใช้สคีมสีเพิ่มเติมกับสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | อ็อบเจ็กต์ [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) |