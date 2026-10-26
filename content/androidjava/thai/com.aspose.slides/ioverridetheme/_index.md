---
title: IOverrideTheme
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง Java API
description: แสดงธีมที่กำลังแทนที่.
type: docs
url: /th/com.aspose.slides/ioverridetheme/
---
**ส่วนต่อประสานที่ทำไว้ทั้งหมด:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

แทนธีมที่กำลังแทนที่
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isEmpty()](#isEmpty--) | ค่าจริงหมายถึงว่า ColorScheme, FontScheme, FormatScheme เป็นค่า null และการแทนที่ใด ๆ ด้วยอ็อบเจ็กต์ธีมนี้จะถูกปิดใช้งาน. |
| [initColorScheme()](#initColorScheme--) | เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ ColorScheme ของ InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ ColorScheme ของ InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ ColorScheme ของ InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | เริ่มต้น FontScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ FontScheme ของ InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | เริ่มต้น FontScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ FontScheme ของ InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | เริ่มต้น FontScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ FontScheme ของ InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | เริ่มต้น FormatScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ FormatScheme ของ InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | เริ่มต้น FormatScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ FormatScheme ของ InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | เริ่มต้น FormatScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ FormatScheme ของ InheritedTheme. |
| [clear()](#clear--) | ตั้งค่า ColorScheme, FontScheme, FormatScheme เป็น null เพื่อปิดการแทนที่ใด ๆ ด้วยอ็อบเจ็กต์ธีมนี้. |

### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

ค่าจริงหมายถึงว่า ColorScheme, FontScheme, FormatScheme เป็นค่า null และการแทนที่ใด ๆ ด้วยอ็อบเจ็กต์ธีมนี้จะถูกปิดใช้งาน. Boolean แบบอ่านอย่างเดียว.

**คืนค่า:**
boolean

### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ ColorScheme ของ InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ ColorScheme ของ InheritedTheme.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | ข้อมูลสำหรับเริ่มต้นจาก. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ ColorScheme ของ InheritedTheme. และเริ่มต้นข้อมูลของอ็อบเจ็กต์ใหม่นี้ด้วยข้อมูลของ ColorScheme ของ InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

เริ่มต้น FontScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ FontScheme ของ InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

เริ่มต้น FontScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ FontScheme ของ InheritedTheme.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | ข้อมูลสำหรับเริ่มต้นจาก. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

เริ่มต้น FontScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ FontScheme ของ InheritedTheme. และเริ่มต้นข้อมูลของอ็อบเจ็กต์ใหม่นี้ด้วยข้อมูลของ FontScheme ของ InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

เริ่มต้น FormatScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ FormatScheme ของ InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

เริ่มต้น FormatScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ FormatScheme ของ InheritedTheme.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | ข้อมูลสำหรับเริ่มต้นจาก. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

เริ่มต้น FormatScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับแทนที่ FormatScheme ของ InheritedTheme. และเริ่มต้นข้อมูลของอ็อบเจ็กต์ใหม่นี้ด้วยข้อมูลของ FormatScheme ของ InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

ตั้งค่า ColorScheme, FontScheme, FormatScheme เป็น null เพื่อปิดการแทนที่ใด ๆ ด้วยอ็อบเจ็กต์ธีมนี้.