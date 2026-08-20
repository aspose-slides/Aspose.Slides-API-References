---
title: Captions
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل ترجمات WebVTT المغلقة.
type: docs
url: /ar/com.aspose.slides/captions/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

يمثل ترجمات WebVTT المغلقة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | يعيد المعرف الفريد عالميًا (GUID) للترجمات المغلقة. |
| [getLabel()](#getLabel--) | يعيد أو يضبط تسمية الترجمات المغلقة. |
| [setLabel(String value)](#setLabel-java.lang.String-) | يعيد أو يضبط تسمية الترجمات المغلقة. |
| [getBinaryData()](#getBinaryData--) | يعيد البيانات الثنائية للترجمات المغلقة. |
| [getDataAsString()](#getDataAsString--) | يعيد بيانات الترجمات المغلوقة كسلسلة مُشفَّرة UTF-8. قراءة فقط String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```

يعيد المعرف الفريد عالميًا (GUID) للترجمات المغلقة. قراءة فقط java.util.UUID.

**الإرجاع:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```

يعيد أو يضبط تسمية الترجمات المغلقة. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```

يعيد أو يضبط تسمية الترجمات المغلقة. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

يعيد البيانات الثنائية للترجمات المغلقة. قراءة فقط byte[] .

**الإرجاع:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```

يعيد بيانات الترجمات المغلقة كسلسلة مُشفَّرة UTF-8. قراءة فقط String.

**الإرجاع:**
java.lang.String