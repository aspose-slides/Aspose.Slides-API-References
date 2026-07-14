---
title: ITheme
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل سمة.
type: docs
url: /ar/com.aspose.slides/itheme/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

يمثل سمة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | يرجع مخطط الألوان. |
| [getFontScheme()](#getFontScheme--) | يرجع مخطط الخط. |
| [getFormatScheme()](#getFormatScheme--) | يرجع مخطط تنسيق الشكل. |
| [getEffective()](#getEffective--) | يحصل على بيانات السمة الفعّالة مع تطبيق الوراثة. |
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
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


يحصل على بيانات السمة الفعّالة مع تطبيق الوراثة.

**الإرجاع:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).