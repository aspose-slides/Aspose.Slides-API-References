---
title: Video
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل صورة مدمجة في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/video/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject  
```
public class Video implements IVideo, IDOMObject
```

يمثل صورة مدمجة في العرض التقديمي.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getContentType()](#getContentType--) | يرجع نوع MIME للفيديو، المشفر في (\#getBinaryData.getBinaryData). قابل للقراءة فقط String. |
| [getBinaryData()](#getBinaryData--) | يرجع نسخة من بيانات الصوت. |
| [getStream()](#getStream--) | يرجع Stream للقراءة. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

يرجع نوع MIME للفيديو، المشفر في (\#getBinaryData.getBinaryData). قابل للقراءة فقط String.

**الإرجاع:**  
java.lang.String

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

يرجع نسخة من بيانات الصوت. في حالة وجود كمية كبيرة من البيانات يُنصح باستخدام طريقة \#getStream.getStream لتفادي تحميل بيانات الفيديو بالكامل في الذاكرة أو حدوث استثناء OutOfMemoryException. قابل للقراءة فقط byte[].

**الإرجاع:**  
byte[]

### getStream() {#getStream--}
```
public final InputStream getStream()
```

يرجع Stream للقراءة. استخدم 'using' أو أغلق الـ stream بعد الاستخدام.

**الإرجاع:**  
java.io.InputStream - Stream للقراءة.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. قابل للقراءة فقط IDOMObject.

**الإرجاع:**  
com.aspose.slides.IDOMObject