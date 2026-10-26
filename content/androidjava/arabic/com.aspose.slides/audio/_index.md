---
title: Audio
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يمثل ملف صوت مدمج.
type: docs
url: /ar/com.aspose.slides/audio/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)  
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

يمثل ملف صوت مدمج.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getContentType()](#getContentType--) | إرجاع نوع MIME للصوت، مُشفّر في (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | إرجاع نوع MIME للصوت، مُشفّر في (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | إرجاع نسخة من بيانات الصوت. |
| [getStream()](#getStream--) | إرجاع Stream للقراءة. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

إرجاع نوع MIME للصوت، مُشفّر في (\#getBinaryData.getBinaryData). قراءة فقط String.

**القيمة المرجعة:**  
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

إرجاع نوع MIME للصوت، مُشفّر في (\#getBinaryData.getBinaryData). قراءة فقط String.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

إرجاع نسخة من بيانات الصوت. في حالة وجود كمية كبيرة من البيانات يُفضَّل استخدام طريقة \#getStream.getStream لتفادي تحميل بيانات الصوت بالكامل في الذاكرة أو حدوث OutOfMemoryException. قراءة فقط byte[].

**القيمة المرجعة:**  
byte[]

### getStream() {#getStream--}
```
public final InputStream getStream()
```

إرجاع Stream للقراءة. استخدم 'using' أو أغلق الـ stream بعد الاستخدام.

**القيمة المرجعة:**  
java.io.InputStream - Stream للقراءة.