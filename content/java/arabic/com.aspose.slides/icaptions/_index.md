---
title: ICaptions
second_title: Aspose.Slides لواجهة برمجة تطبيقات Java
description: يمثل الترجمات المغلقة بتنسيق WebVTT.
type: docs
url: /ar/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

يمثل الترجمات المغلقة بتنسيق WebVTT.
## Methods

| الطريقة | الوصف |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | يعيد المعرف الفريد عالمياً (GUID) للتعليقات المغلقة. |
| [getLabel()](#getLabel--) | يعيد أو يعيّن تسمية التعليقات المغلقة. |
| [setLabel(String value)](#setLabel-java.lang.String-) | يعيد أو يعيّن تسمية التعليقات المغلقة. |
| [getBinaryData()](#getBinaryData--) | يعيد البيانات الثنائية للتعليقات المغلقة. |
| [getDataAsString()](#getDataAsString--) | يعيد بيانات التعليقات المغلقة كسلسلة UTF-8 مُشفَّرة (للقراءة فقط String). |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


يعيد المعرف الفريد عالمياً (GUID) للتعليقات المغلقة. (للقراءة فقط java.util.UUID).

**القيمة المرجعة:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


يعيد أو يعيّن تسمية التعليقات المغلقة. (للقراءة والكتابة String).

**القيمة المرجعة:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


يعيد أو يعيّن تسمية التعليقات المغلقة. (للقراءة والكتابة String).

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


يعيد البيانات الثنائية للتعليقات المغلقة. (للقراءة فقط byte[]).

**القيمة المرجعة:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


يعيد بيانات التعليقات المغلقة كسلسلة UTF-8 مُشفَّرة (للقراءة فقط String).

**القيمة المرجعة:**
java.lang.String