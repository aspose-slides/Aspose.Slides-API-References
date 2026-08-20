---
title: Audio
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل ملف صوت مضمّن.
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

يمثل ملف صوت مضمّن.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getContentType()](#getContentType--) | يعيد نوع MIME لصوت، مشفر في (\#getBinaryData.getBinaryData). قراءة فقط String. |
| [setContentType(String value)](#setContentType-java.lang.String-) | يعيد نوع MIME لصوت، مشفر في (\#getBinaryData.getBinaryData). قراءة فقط String. |
| [getBinaryData()](#getBinaryData--) | يعيد نسخة من بيانات الصوت. |
| [getStream()](#getStream--) | يعيد Stream stream للقراءة. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

يعيد نوع MIME لصوت، مشفر في (\#getBinaryData.getBinaryData). قراءة فقط String.

**القيمة المرجعة:**  
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

يعيد نوع MIME لصوت، مشفر في (\#getBinaryData.getBinaryData). قراءة فقط String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

يعيد نسخة من بيانات الصوت. في حالة كمية كبيرة من البيانات، يُنصح باستخدام طريقة \#getStream.getStream لتجنب تحميل بيانات الصوت غير الضروري في الذاكرة أو حتى حدوث OutOfMemoryException. قراءة فقط byte[].

**القيمة المرجعة:**  
byte[]

### getStream() {#getStream--}
```
public final InputStream getStream()
```

يعيد Stream stream للقراءة. استخدم 'using' أو أغلق التدفق بعد الاستخدام.

**القيمة المرجعة:**  
java.io.InputStream - Stream للقراءة.