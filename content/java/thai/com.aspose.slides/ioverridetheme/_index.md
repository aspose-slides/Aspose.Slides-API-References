---
title: IOverrideTheme
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แทนธีมที่ทำการ overriding.
type: docs
url: /th/com.aspose.slides/ioverridetheme/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

เป็นตัวแทนของธีมที่ทำการ overriding.
## เมธอด

| Method | Description |
| --- | --- |
| [isEmpty()](#isEmpty--) | ค่าจริงหมายความว่า ColorScheme, FontScheme, FormatScheme เป็น null และการ overriding ใด ๆ ด้วยอ็อบเจ็กต์ธีมนี้จะถูกปิดใช้งาน. |
| [initColorScheme()](#initColorScheme--) | เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding ColorScheme ของ InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding ColorScheme ของ InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding ColorScheme ของ InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | เริ่มต้น FontScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding FontScheme ของ InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | เริ่มต้น FontScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding FontScheme ของ InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | เริ่มต้น FontScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding FontScheme ของ InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | เริ่มต้น FormatScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding FormatScheme ของ InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | เริ่มต้น FormatScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding FormatScheme ของ InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | เริ่มต้น FormatScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding FormatScheme ของ InheritedTheme. |
| [clear()](#clear--) | ตั้งค่า ColorScheme, FontScheme, FormatScheme ให้เป็น null เพื่อปิดการ overriding ใด ๆ ด้วยอ็อบเจ็กต์ธีมนี้. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

ค่าจริงหมายความว่า ColorScheme, FontScheme, FormatScheme เป็น null และการ overriding ใด ๆ ด้วยอ็อบเจ็กต์ธีมนี้จะถูกปิดใช้งาน. บูลีนแบบอ่านอย่างเดียว.

**คืนค่า:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding ColorScheme ของ InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding ColorScheme ของ InheritedTheme.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | ข้อมูลที่จะใช้เริ่มต้นจาก |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

เริ่มต้น ColorScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding ColorScheme ของ InheritedTheme.และทำการเริ่มต้นข้อมูลของอ็อบเจ็กต์ใหม่นี้ด้วยข้อมูลของ ColorScheme ของ InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

เริ่มต้น FontScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding FontScheme ของ InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

เริ่มต้น FontScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding FontScheme ของ InheritedTheme.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | ข้อมูลที่จะใช้เริ่มต้นจาก |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

เริ่มต้น FontScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding FontScheme ของ InheritedTheme.และทำการเริ่มต้นข้อมูลของอ็อบเจ็กต์ใหม่นี้ด้วยข้อมูลของ FontScheme ของ InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

เริ่มต้น FormatScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding FormatScheme ของ InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

เริ่มต้น FormatScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding FormatScheme ของ InheritedTheme.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | ข้อมูลที่จะใช้เริ่มต้นจาก |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

เริ่มต้น FormatScheme ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding FormatScheme ของ InheritedTheme.และทำการเริ่มต้นข้อมูลของอ็อบเจ็กต์ใหม่นี้ด้วยข้อมูลของ FormatScheme ของ InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

ตั้งค่า ColorScheme, FontScheme, FormatScheme ให้เป็น null เพื่อปิดการ overriding ใด ๆ ด้วยอ็อบเจ็กต์ธีมนี้.