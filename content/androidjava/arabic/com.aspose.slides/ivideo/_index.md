---
title: IVideo
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل فيديوً مدمجًا في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/ivideo/
---```
public interface IVideo
```

يمثل فيديوً مدمجًا في عرض تقديمي.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getContentType()](#getContentType--) | يرجع نوع MIME للفيديو، مُرمَّزًا في (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | يرجع نسخة من بيانات الصوت. |
| [getStream()](#getStream--) | يرجع تدفق Stream للقراءة. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

يرجع نوع MIME للفيديو، مُرمَّزًا في (\#getBinaryData.getBinaryData). **String** للقراءة فقط.

**الإرجاع:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

يرجع نسخة من بيانات الصوت. في حالة كمية كبيرة من البيانات، يُنصَح باستخدام طريقة \#getStream.getStream لتجنّب تحميل بيانات الفيديو غير الضرورية إلى الذاكرة أو حدوث استثناء OutOfMemoryException. **byte[]** للقراءة فقط.

**الإرجاع:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

يرجع تدفق Stream للقراءة. استخدم ‎'using'‎ أو أغلق التدفق بعد الاستخدام.

**الإرجاع:**  
java.io.InputStream - تدفق للقراءة.