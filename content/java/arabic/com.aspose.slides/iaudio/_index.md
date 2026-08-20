---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: Represents an embedded audio file.
type: docs
url: /ar/com.aspose.slides/iaudio/
---```
public interface IAudio
```

يمثل ملف صوت مضمّن.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getContentType()](#getContentType--) | إرجاع نوع MIME للصوت، مُشفَّر في (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | إرجاع نسخة من بيانات الصوت. |
| [getStream()](#getStream--) | إرجاع Stream stream للقراءة. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


إرجاع نوع MIME للصوت، مُشفَّر في (\#getBinaryData.getBinaryData). للقراءة فقط String.

**القيمة المرجعة:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


إرجاع نسخة من بيانات الصوت. في حالة كميات كبيرة من البيانات، يُنصح باستخدام طريقة \#getStream.getStream لتجنب تحميل بيانات الصوت غير الضروري إلى الذاكرة أو حتى حدوث OutOfMemoryException. للقراءة فقط byte[].

**القيمة المرجعة:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


إرجاع Stream stream للقراءة. استخدم 'using' أو أغلق التيار بعد الاستخدام.

**القيمة المرجعة:**
java.io.InputStream - تيار للقراءة.