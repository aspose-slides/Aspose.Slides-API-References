---
title: MasterTheme
second_title: Aspose.Slides لمرجع API جافا
description: يمثل سمة رئيسية.
type: docs
url: /ar/com.aspose.slides/mastertheme/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**جميع الواجهات التي تم تنفيذها:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

يمثل سمة رئيسية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | يرجع مخطط الألوان. |
| [getFontScheme()](#getFontScheme--) | يرجع مخطط الخط. |
| [getFormatScheme()](#getFormatScheme--) | يرجع مخطط تنسيق الشكل. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | يرجع مجموعة مخططات الألوان الإضافية. |
| [getName()](#getName--) | يرجع اسم السمة. |
| [setName(String value)](#setName-java.lang.String-) | يرجع اسم السمة. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

يرجع مخطط الألوان. للقراءة فقط [IColorScheme](../../com.aspose.slides/icolorscheme).

**الإرجاع:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

يرجع مخطط الخط. للقراءة فقط [IFontScheme](../../com.aspose.slides/ifontscheme).

**الإرجاع:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

يرجع مخطط تنسيق الشكل. للقراءة فقط [IFormatScheme](../../com.aspose.slides/iformatscheme).

**الإرجاع:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

يرجع مجموعة مخططات الألوان الإضافية. لا تؤثر هذه المخططات على مظهر العرض التقدمي، ويمكن اختيارها كمخطط الألوان الرئيسي لشريحة. للقراءة فقط [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**الإرجاع:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```

يرجع اسم السمة. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

يرجع اسم السمة. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. للقراءة فقط long.

**الإرجاع:**
long