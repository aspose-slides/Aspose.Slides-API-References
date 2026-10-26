---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: كائن ثابت يحتوي على خصائص النمط الفعّالة.
type: docs
url: /ar/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

كائن ثابت يحتوي على خصائص النمط الفعّالة.

--------------------

يُستخدم هذا الواجهة مع واجهة [ITheme](../../com.aspose.slides/itheme) لإرجاع قيم التنسيق الفعّالة مع تطبيق الوراثة.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | يعيد مخطط اللون. |
| [getFontScheme()](#getFontScheme--) | يعيد مخطط الخط. |
| [getFormatScheme()](#getFormatScheme--) | يعيد مخطط تنسيق الشكل. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```

يعيد مخطط اللون.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| styleColor | java.lang.Integer | Color java.lang.Integer |

**الإرجاع:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - مخطط اللون [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

يعيد مخطط الخط. للقراءة فقط [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**الإرجاع:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

يعيد مخطط تنسيق الشكل. للقراءة فقط [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**الإرجاع:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)