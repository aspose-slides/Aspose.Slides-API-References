---
title: Theme
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของธีม.
type: docs
url: /th/com.aspose.slides/theme/
---
**การสืบทอด:**  
java.lang.Object

**ทุกอินเทอร์เฟซที่ทำการใช้งาน:**  
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject  
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

เป็นตัวแทนของธีม.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | ส่งคืนชุดสี. |
| [getFontScheme()](#getFontScheme--) | ส่งคืนชุดแบบอักษร. |
| [getFormatScheme()](#getFormatScheme--) | ส่งคืนชุดรูปแบบรูปร่าง. |
| [getPresentation()](#getPresentation--) | ส่งคืนพรีเซนเทชันแม่. |
| [getEffective()](#getEffective--) | ได้รับข้อมูลธีมที่มีผลบังคับใช้งานการสืบทอด. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |

### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

ส่งคืนชุดสี. อ่านอย่างเดียว [IColorScheme](../../com.aspose.slides/icolorscheme).

**คืนค่า:**  
[IColorScheme](../../com.aspose.slides/icolorscheme)

### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

ส่งคืนชุดแบบอักษร. อ่านอย่างเดียว [IFontScheme](../../com.aspose.slides/ifontscheme).

**คืนค่า:**  
[IFontScheme](../../com.aspose.slides/ifontscheme)

### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

ส่งคืนชุดรูปแบบรูปร่าง. อ่านอย่างเดียว [IFormatScheme](../../com.aspose.slides/iformatscheme).

**คืนค่า:**  
[IFormatScheme](../../com.aspose.slides/iformatscheme)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ส่งคืนพรีเซนเทชันแม่. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

ได้ข้อมูลธีมที่มีผลบังคับใช้งานการสืบทอด.

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

**คืนค่า:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**  
com.aspose.slides.IDOMObject

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

ส่งคืน IPresentationComponent แม่. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**คืนค่า:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**  
long