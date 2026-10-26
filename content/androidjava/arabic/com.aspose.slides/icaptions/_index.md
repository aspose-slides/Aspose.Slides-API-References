---
title: ICaptions
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: يمثل ترجمات WebVTT المغلقة.
type: docs
url: /ar/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

يمثل ترجمات WebVTT المغلقة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | يرجع معرفًا فريدًا عالميًا (GUID) للترجمات المغلقة. |
| [getLabel()](#getLabel--) | يرجع أو يعيّن تسمية الترجمات المغلقة. |
| [setLabel(String value)](#setLabel-java.lang.String-) | يرجع أو يعيّن تسمية الترجمات المغلقة. |
| [getBinaryData()](#getBinaryData--) | يرجع البيانات الثنائية للترجمات المغلقة. |
| [getDataAsString()](#getDataAsString--) | يرجع بيانات الترجمات المغلقة كسلسلة مشفّرة UTF-8 للقراءة فقط String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

يرجع معرفًا فريدًا عالميًا (GUID) للترجمات المغلقة. للقراءة فقط java.util.UUID.

**الإرجاع:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

يرجع أو يعيّن تسمية الترجمات المغلقة. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

يرجع أو يعيّن تسمية الترجمات المغلقة. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

يرجع البيانات الثنائية للترجمات المغلوقة. للقراءة فقط byte[].

**الإرجاع:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

يرجع بيانات الترجمات المغلقة كسلسلة مشفّرة UTF-8 للقراءة فقط String.

**الإرجاع:**
java.lang.String