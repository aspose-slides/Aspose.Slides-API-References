---
title: Theme
second_title: مرجع API Aspose.Slides برای جاوا
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
| [getColorScheme()](#getColorScheme--) | رنگ‌بندی طرح را برمی‌گرداند. |
| [getFontScheme()](#getFontScheme--) | فانتزی طرح را برمی‌گرداند. |
| [getFormatScheme()](#getFormatScheme--) | طرح قالب‌بندی شکل را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائهٔ والد را برمی‌گرداند. |
| [getEffective()](#getEffective--) | داده‌های تم مؤثر را با اعمال ارث‌بری دریافت می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |

### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

رنگ‌بندی طرح را برمی‌گرداند. فقط خواندنی [IColorScheme](../../com.aspose.slides/icolorscheme).

**بازگشت:**  
[IColorScheme](../../com.aspose.slides/icolorscheme)

### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

فانتزی طرح را برمی‌گرداند. فقط خواندنی [IFontScheme](../../com.aspose.slides/ifontscheme).

**بازگشت:**  
[IFontScheme](../../com.aspose.slides/ifontscheme)

### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

طرح قالب‌بندی شکل را برمی‌گرداند. فقط خواندنی [IFormatScheme](../../com.aspose.slides/iformatscheme).

**بازگشت:**  
[IFormatScheme](../../com.aspose.slides/iformatscheme)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائهٔ والد را برمی‌گرداند. فقط خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

داده‌های تم مؤثر را با اعمال ارث‌بری دریافت می‌کند.

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

شی Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**بازگشت:**  
com.aspose.slides.IDOMObject

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

پدر IPresentationComponent را برمی‌گرداند. فقط خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**بازگشت:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

نسخه. فقط خواندنی long.

**بازگشت:**  
long