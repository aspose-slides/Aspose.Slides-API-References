---
title: Theme
second_title: مرجع API Aspose.Slides للغة Java
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
| [getColorScheme()](#getColorScheme--) | يعيد مخطط الألوان. |
| [getFontScheme()](#getFontScheme--) | يعيد مخطط الخط. |
| [getFormatScheme()](#getFormatScheme--) | يعيد مخطط تنسيق الشكل. |
| [getPresentation()](#getPresentation--) | يعيد الـ presentation الأصل. |
| [getEffective()](#getEffective--) | يحصل على بيانات السمة الفعالة مع تطبيق الوراثة. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

يعيد مخطط الألوان. للقراءة فقط [IColorScheme](../../com.aspose.slides/icolorscheme).

**القيمة المرجعة:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

يعيد مخطط الخط. للقراءة فقط [IFontScheme](../../com.aspose.slides/ifontscheme).

**القيمة المرجعة:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

يعيد مخطط تنسيق الشكل. للقراءة فقط [IFormatScheme](../../com.aspose.slides/iformatscheme).

**القيمة المرجعة:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد الـ presentation الأصل. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

يحصل على بيانات السمة الفعالة مع تطبيق الوراثة.

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


**القيمة المرجعة:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - كـ [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. للقراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

يعيد الـ IPresentationComponent الأصل. للقراءة فقط [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**القيمة المرجعة:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

الإصدار. للقراءة فقط long.

**القيمة المرجعة:**
long