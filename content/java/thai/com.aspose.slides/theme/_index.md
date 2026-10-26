---
title: Theme
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของธีม.
type: docs
url: /th/com.aspose.slides/theme/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**  
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject  
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

เป็นตัวแทนของธีม.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | ส่งคืนชุดสี. |
| [getFontScheme()](#getFontScheme--) | ส่งคืนชุดแบบอักษร. |
| [getFormatScheme()](#getFormatScheme--) | ส่งคืนชุดรูปแบบรูปร่าง. |
| [getPresentation()](#getPresentation--) | ส่งคืนการนำเสนอพาเรนต์. |
| [getEffective()](#getEffective--) | รับข้อมูลธีมที่มีประสิทธิภาพพร้อมการสืบทอดที่ได้ใช้. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |

### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

ส่งคืนชุดสี. อ่านอย่างเดียว [IColorScheme](../../com.aspose.slides/icolorscheme).

**ผลลัพธ์:**
[IColorScheme](../../com.aspose.slides/icolorscheme)

### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

ส่งคืนชุดแบบอักษร. อ่านอย่างเดียว [IFontScheme](../../com.aspose.slides/ifontscheme).

**ผลลัพธ์:**
[IFontScheme](../../com.aspose.slides/ifontscheme)

### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

ส่งคืนชุดรูปแบบรูปร่าง. อ่านอย่างเดียว [IFormatScheme](../../com.aspose.slides/iformatscheme).

**ผลลัพธ์:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ส่งคืนการนำเสนอพาเรนต์. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**ผลลัพธ์:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

รับข้อมูลธีมที่มีประสิทธิภาพพร้อมการสืบทอดที่ได้ใช้.

--------------------

> ```
> This example demonstrates getting effective theme properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IThemeEffectiveData effectiveTheme  = pres.getSlides().get_Item(0).getThemeManager().getOverrideTheme().getEffective();
>  	System.out.println("Font scheme name: " + effectiveTheme.getFontScheme().getName());
>  	System.out.println("Major latin font: " + effectiveTheme.getFontScheme().getMajor().getLatinFont().getFontName());
>  	System.out.println("Minor latin font: " + effectiveTheme.getFontScheme().getMinor().getLatinFont().getFontName());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - หนึ่ง [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนวัตถุ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**ผลลัพธ์:**
com.aspose.slides.IDOMObject

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

ส่งคืน IPresentationComponent พาเรนต์. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**ผลลัพธ์:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**ผลลัพธ์:**
long