---
title: Video
second_title: Aspose.Slides لواجهة برمجة تطبيقات Java
description: يمثل صورة مدمجة في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/video/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

يمثل صورة مدمجة في عرض تقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getContentType()](#getContentType--) | يعيد نوع MIME لفيديو، مُشفَّر في (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | يعيد نسخة من بيانات الصوت. |
| [getStream()](#getStream--) | يعيد تدفق Stream للقراءة. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

يعيد نوع MIME لفيديو، مُشفَّر في (\#getBinaryData.getBinaryData). سلسلة للقراءة فقط.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

يعيد نسخة من بيانات الصوت. في حال وجود كمية كبيرة من البيانات، يُنصَح باستخدام طريقة \#getStream.getStream لتجنب تحميل بيانات الفيديو غير الضروري في الذاكرة أو حتى حدوث استثناء OutOfMemoryException. مصفوفة byte[] للقراءة فقط.

**Returns:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

يعيد تدفق Stream للقراءة. استخدم 'using' أو أغلق الدفق بعد الاستخدام.

**Returns:**
java.io.InputStream - تدفق للقراءة.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. كائن IDOMObject للقراءة فقط.

**Returns:**
com.aspose.slides.IDOMObject