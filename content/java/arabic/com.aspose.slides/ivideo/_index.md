---
title: IVideo
second_title: Aspose.Slides for Java API Reference
description: يمثل فيديوً مضمّنًا في العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/ivideo/
---```
public interface IVideo
```

يمثل فيديوً مضمّنًا في العرض التقديمي.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getContentType()](#getContentType--) | يعيد نوع MIME للفيديو، مشفرًا في (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | يعيد نسخة من بيانات الصوت. |
| [getStream()](#getStream--) | يعيد Stream للقراءة. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

يعيد نوع MIME للفيديو، مشفرًا في (\#getBinaryData.getBinaryData). String للقراءة فقط.

**القيمة المرجعة:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

يعيد نسخة من بيانات الصوت. في حالة كمية كبيرة من البيانات، يُنصح باستخدام طريقة \#getStream.getStream لتفادي تحميل بيانات الفيديو غير الضروري في الذاكرة أو حتى حدوث OutOfMemoryException. byte[] للقراءة فقط.

**القيمة المرجعة:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

يعيد تدفق Stream للقراءة. استخدم 'using' أو أغلق التدفق بعد الاستخدام.

**القيمة المرجعة:**  
java.io.InputStream - Stream للقراءة.