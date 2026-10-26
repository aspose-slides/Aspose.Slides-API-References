---
title: IOverrideThemeManager
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ให้การเข้าถึงประเภทต่าง ๆ ของธีมที่ถูกแทนที่.
type: docs
url: /th/com.aspose.slides/ioverridethememanager/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

ให้การเข้าถึงประเภทต่าง ๆ ของธีมที่ถูกแทนที่.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | กำหนดว่า OverrideTheme จะทำการแทนที่ธีมที่สืบทอดมาหรือไม่ |
| [getOverrideTheme()](#getOverrideTheme--) | คืนค่าอ็อบเจกต์ธีมที่กำลังแทนที่ |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | คืนค่าอ็อบเจกต์ธีมที่กำลังแทนที่ |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


กำหนดว่า OverrideTheme จะทำการแทนที่ธีมที่สืบทอดมาหรือไม่ เพื่อเปิดใช้ OverrideTheme สำหรับการแทนที่ ให้ใช้เมธอด OverrideTheme.Init\*() หากต้องการปิดการแทนที่ของ OverrideTheme ให้ใช้เมธอด OverrideTheme.Clear()  เป็น boolean แบบอ่านอย่างเดียว.

**คืนค่า:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```


คืนค่าอ็อบเจกต์ธีมที่กำลังแทนที่. อ่าน/เขียน [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**คืนค่า:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```


คืนค่าอ็อบเจกต์ธีมที่กำลังแทนที่. อ่าน/เขียน [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |