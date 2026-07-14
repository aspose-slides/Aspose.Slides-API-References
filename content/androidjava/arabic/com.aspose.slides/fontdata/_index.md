---
title: FontData
second_title: Aspose.Slides للأندرويد عبر مرجع API جافا
description: يمثل تعريفًا للخط.
type: docs
url: /ar/com.aspose.slides/fontdata/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

يمثل تعريفًا للخط. غير قابل للتغيير.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | ينشئ كائن FontData جديدًا بالاسم المحدد للخط. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFontName()](#getFontName--) | يعيد اسم الخط. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | يعيد اسم الخط، مع استبدال إشارة السمة بخط فعلي مستخدم. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان كائنان من FontData متساويين. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة والهياكل البياناتية مثل جدول التجزئة. |
| [toString()](#toString--) | يعيد تمثيلًا نصيًا. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

ينشئ كائن FontData جديدًا بالاسم المحدد للخط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | اسم الخط. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

يعيد اسم الخط. قابل للقراءة/الكتابة String.

**الإرجاع:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

يعيد اسم الخط، مع استبدال إشارة السمة بخط فعلي مستخدم.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | السمة التي يجب أخذ اسم الخط المظهر منها. يعود للمستدعي توفير قيمة صحيحة. انظر [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**الإرجاع:**
java.lang.String - اسم الخط.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كان كائنان من FontData متساويين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | كائن FontData للمقارنة مع FontData الحالي. |

**الإرجاع:**
boolean - **true** إذا كان FontData المحدد يساوي FontData الحالي؛ وإلا **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة والهياكل البياناتية مثل جدول التجزئة.

**الإرجاع:**
int - رمز التجزئة لـ FontData.
### toString() {#toString--}
```
public String toString()
```

يعيد تمثيلًا نصيًا.

**الإرجاع:**
java.lang.String - تمثيل نصي.