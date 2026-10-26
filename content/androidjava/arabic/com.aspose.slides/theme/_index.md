---
title: Theme
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل سمة.
type: docs
url: /ar/com.aspose.slides/theme/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

يمثل سمة.
## الطرق

| الطريقة | الوصف |
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


يرجع مخطط الألوان. للقراءة فقط [IColorScheme](../../com.aspose.slides/icolorscheme).

**الإرجاع:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


يرجع مخطط الخط. للقراءة فقط [IFontScheme](../../com.aspose.slides/ifontscheme).

**الإرجاع:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


يرجع مخطط تنسيق الشكل. للقراءة فقط [IFormatScheme](../../com.aspose.slides/iformatscheme).

**الإرجاع:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


يرجع العرض التقديمي الأصل. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```


يحصل على بيانات السمة الفعّالة مع تطبيق الوراثة.

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


**الإرجاع:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - كائن [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


يرجع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


يرجع IPresentationComponent الأصل. للقراءة فقط [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**الإرجاع:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```


الإصدار. للقراءة فقط long.

**الإرجاع:**
long