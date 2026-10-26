---
title: Storage
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل تخزينًا مؤقتًا للبيانات لـ .
type: docs
url: /ar/com.aspose.slides/storage/
---
**الوراثة:**
java.lang.Object
```
public final class Storage
```

يمثل تخزينًا مؤقتًا للبيانات لـ [WebDocument](../../com.aspose.slides/webdocument).
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [Storage()](#Storage--) |  |
## الأساليب

| الأسلوب | الوصف |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | يضع القيمة في التخزين. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | يحصل على البيانات من التخزين. |
| [containsKey(String key)](#containsKey-java.lang.String-) | يحدد ما إذا كان التخزين يحتوي على عنصر بالمفتاح المحدد. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


يضع القيمة في التخزين.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| key | java.lang.String | المفتاح للقيمة. |
| value | TValue | القيمة. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


يحصل على البيانات من التخزين.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| key | java.lang.String | مفتاح القيمة. |

**القيمة المرجعة:**
TValue - قيمة البيانات إذا كانت موجودة في مجموعة البيانات، null غير ذلك.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


يحدد ما إذا كان التخزين يحتوي على عنصر بالمفتاح المحدد.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| key | java.lang.String | مفتاح القيمة. |

**القيمة المرجعة:**
boolean - True إذا كان التخزين يحتوي على عنصر بالمفتاح المحدد، false غير ذلك.