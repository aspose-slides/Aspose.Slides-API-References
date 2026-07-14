---
title: MasterTheme
second_title: Aspose.Slides لنظام Android عبر مرجع واجهة برمجة التطبيقات Java
description: يمثل سمة رئيسية.
type: docs
url: /ar/com.aspose.slides/mastertheme/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

يمثل سمة رئيسية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | يُعيد مخطط الألوان. |
| [getFontScheme()](#getFontScheme--) | يُعيد مخطط الخط. |
| [getFormatScheme()](#getFormatScheme--) | يُعيد مخطط تنسيق الشكل. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | يُعيد مجموعة مخططات الألوان الإضافية. |
| [getName()](#getName--) | يُعيد اسم السمة. |
| [setName(String value)](#setName-java.lang.String-) | يُعيد اسم السمة. |
| [getVersion()](#getVersion--) |  |

### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

يعيد مخطط الألوان. للقراءة فقط [IColorScheme](../../com.aspose.slides/icolorscheme).

**القيمة المعادة:**
[IColorScheme](../../com.aspose.slides/icolorscheme)

### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

يعيد مخطط الخط. للقراءة فقط [IFontScheme](../../com.aspose.slides/ifontscheme).

**القيمة المعادة:**
[IFontScheme](../../com.aspose.slides/ifontscheme)

### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

يعيد مخطط تنسيق الشكل. للقراءة فقط [IFormatScheme](../../com.aspose.slides/iformatscheme).

**القيمة المعادة:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)

### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

يعيد مجموعة مخططات الألوان الإضافية. لا تؤثر هذه المخططات على مظهر العرض التقديمي، ويمكن اختيارها كمخطط الألوان الرئيسي لشريحة. للقراءة فقط [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**القيمة المعادة:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)

### getName() {#getName--}
```
public final String getName()
```

يعيد اسم السمة. قراءة/كتابة String.

**القيمة المعادة:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

يعيد اسم السمة. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. للقراءة فقط long.

**القيمة المعادة:**
long