---
title: IAudio
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an embedded audio file.
type: docs
url: /ar/com.aspose.slides/iaudio/
---```
public interface IAudio
```

يمثل ملف صوت مدمج.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getContentType()](#getContentType--) | يعيد نوع MIME للصوت، المشفر في (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | يعيد نسخة من بيانات الصوت. |
| [getStream()](#getStream--) | يعيد تدفق Stream للقراءة. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


يعيد نوع MIME للصوت، المشفر في (\#getBinaryData.getBinaryData). String للقراءة فقط.

**القيمة المرجعة:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


يعيد نسخة من بيانات الصوت. في حالة كمية كبيرة من البيانات، يُنصح باستخدام طريقة \#getStream.getStream لتجنب تحميل بيانات الصوت غير الضروري في الذاكرة أو حدوث OutOfMemoryException. byte[] للقراءة فقط.

**القيمة المرجعة:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


يعيد تدفق Stream للقراءة. استخدم 'using' أو أغلق التدفق بعد الاستخدام.

**القيمة المرجعة:**
java.io.InputStream - تدفق للقراءة.