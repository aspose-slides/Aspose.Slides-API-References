---
title: Captions
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل ترجمات WebVTT المغلقة.
type: docs
url: /ar/com.aspose.slides/captions/
---
**Inheritance:**  
الوراثة:

java.lang.Object

**All Implemented Interfaces:**  
جميع الواجهات المنفذة:

[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

يمثِّل ترجمات WebVTT المغلقة.

## Methods
## الأساليب

| Method | Description |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | إرجاع المعرف الفريد عالمياً (GUID) للترجمات المغلقة. |
| [getLabel()](#getLabel--) | إرجاع أو تعيين تسمية الترجمات المغلقة. |
| [setLabel(String value)](#setLabel-java.lang.String-) | إرجاع أو تعيين تسمية الترجمات المغلقة. |
| [getBinaryData()](#getBinaryData--) | إرجاع البيانات الثنائية للترجمات المغلقة. |
| [getDataAsString()](#getDataAsString--) | إرجاع بيانات الترجمات المغلقة كسلسلة مشفَّرة UTF-8. قراءة فقط String. |

### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```

إرجاع المعرف الفريد عالمياً (GUID) للترجمات المغلقة. قراءة فقط java.util.UUID.

**Returns:**  
الإرجاع:
java.util.UUID

### getLabel() {#getLabel--}
```
public final String getLabel()
```

إرجاع أو تعيين تسمية الترجمات المغلقة. قراءة وكتابة String.

**Returns:**  
الإرجاع:
java.lang.String

### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```

إرجاع أو تعيين تسمية الترجمات المغلقة. قراءة وكتابة String.

**Parameters:**  
المعاملات:
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

إرجاع البيانات الثنائية للترجمات المغلقة. قراءة فقط byte[] .

**Returns:**  
الإرجاع:
byte[]

### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```

إرجاع بيانات الترجمات المغلقة كسلسلة مشفَّرة UTF-8. قراءة فقط String.

**Returns:**  
الإرجاع:
java.lang.String