---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective theme properties.
type: docs
url: /ar/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص السمة الفعّالة.

--------------------

هذه الواجهة تُستخدم مع الواجهة [ITheme](../../com.aspose.slides/itheme) لإرجاع قيم تنسيق فعّالة مع تطبيق الوراثة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | يرجع مخطط الألوان. |
| [getFontScheme()](#getFontScheme--) | يرجع مخطط الخط. |
| [getFormatScheme()](#getFormatScheme--) | يرجع مخطط تنسيق الشكل. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```

يرجع مخطط الألوان.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**الإرجاع:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - مخطط الألوان [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

يرجع مخطط الخط. قراءة فقط [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**الإرجاع:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

يرجع مخطط تنسيق الشكل. قراءة فقط [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**الإرجاع:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)