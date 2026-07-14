---
title: Theme
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک تم.
type: docs
url: /fa/com.aspose.slides/theme/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

نمایانگر یک تم.
## متدها

| متد | توضیح |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Returns the color scheme. |
| [getFontScheme()](#getFontScheme--) | Returns the font scheme. |
| [getFormatScheme()](#getFormatScheme--) | Returns the shape format scheme. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation. |
| [getEffective()](#getEffective--) | Gets effective theme data with the inheritance applied. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

باز می‌گرداند طرح رنگ. فقط‌خواندنی [IColorScheme](../../com.aspose.slides/icolorscheme).

**بازگشت:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

باز می‌گرداند طرح قلم. فقط‌خواندنی [IFontScheme](../../com.aspose.slides/ifontscheme).

**بازگشت:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

باز می‌گرداند طرح فرمت شکل. فقط‌خواندنی [IFormatScheme](../../com.aspose.slides/iformatscheme).

**بازگشت:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

باز می‌گرداند ارائه والد. فقط‌خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

دریافت داده‌های تم مؤثر با اعمال ارث‌بری.

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

**بازگشت:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - یک [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

باز می‌گرداند شیء Parent_Immediate. فقط‌خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

باز می‌گرداند IPresentationComponent والد. فقط‌خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**بازگشت:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

نسخه. فقط‌خواندنی long.

**بازگشت:**
long