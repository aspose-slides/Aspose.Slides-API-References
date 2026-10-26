---
title: FontData
second_title: مرجع API لـ Aspose.Slides for Java
description: يمثل تعريفًا للخط.
type: docs
url: /ar/com.aspose.slides/fontdata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

يمثل تعريفًا للخط. غير قابل للتغيير.
## Constructors

| Constructor | Description |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | ينشئ كائن FontData جديدًا بالاسم المحدد للخط. |
## Methods

| Method | Description |
| --- | --- |
| [getFontName()](#getFontName--) | يرجع اسم الخط. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | يرجع اسم الخط، مستبدلًا إشارة الثيم بخط فعلي مُستخدم. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان مثّالاَين من FontData متساويين. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة والهياكل مثل جدول التجزئة. |
| [toString()](#toString--) | يرجع تمثيلًا نصيًا. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

ينشئ كائن FontData جديدًا بالاسم المحدد للخط.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | اسم الخط. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

يرجع اسم الخط. قراءة/كتابة String.

**Returns:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

يرجع اسم الخط، مستبدلًا إشارة الثيم بخط فعلي مُستخدم.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | الثيم الذي يجب أخذ اسم الخط المرتبط به. يعود للمستدعي توفير قيمة صحيحة. انظر [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Returns:**
java.lang.String - اسم الخط.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كان مثّالاَين من FontData متساويين.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | الـ FontData للمقارنة مع الـ FontData الحالي. |

**Returns:**
boolean - **true** إذا كان الـ FontData المحدد يساوي الـ FontData الحالي؛ وإلا، **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة والهياكل مثل جدول التجزئة.

**Returns:**
int - رمز التجزئة للـ FontData.
### toString() {#toString--}
```
public String toString()
```

يرجع تمثيلًا نصيًا.

**Returns:**
java.lang.String - تمثيل String.