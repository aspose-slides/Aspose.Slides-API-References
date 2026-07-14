---
title: IOverrideThemeManager
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ให้การเข้าถึงประเภทต่าง ๆ ของธีมที่ถูกแทนที่
type: docs
url: /th/com.aspose.slides/ioverridethememanager/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

ให้การเข้าถึงประเภทต่าง ๆ ของธีมที่ถูกแทนที่
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | ระบุว่า OverrideTheme แทนที่ธีมที่มีผลสืบทอดหรือไม่ |
| [getOverrideTheme()](#getOverrideTheme--) | คืนค่าอ็อบเจ็กต์ธีมที่กำลังแทนที่ |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | คืนค่าอ็อบเจ็กต์ธีมที่กำลังแทนที่ |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

ระบุว่า OverrideTheme แทนที่ธีมที่มีผลสืบทอดหรือไม่ เพื่อเปิดใช้งาน OverrideTheme สำหรับการแทนที่ ให้ใช้เมธอด OverrideTheme.Init*() เพื่อปิดการใช้งาน OverrideTheme จากการแทนที่ ให้ใช้เมธอด OverrideTheme.Clear()  boolean แบบอ่านอย่างเดียว.

**คืนค่า:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

คืนค่าอ็อบเจ็กต์ธีมที่กำลังแทนที่. อ่าน/เขียน [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**คืนค่า:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

คืนค่าอ็อบเจ็กต์ธีมที่กำลังแทนที่. อ่าน/เขียน [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |