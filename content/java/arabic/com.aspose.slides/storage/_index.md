---
title: Storage
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides لـ Java
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

| المنشئ | الوصف |
| --- | --- |
| [Storage()](#Storage--) |  |
## الطرق

| الطريقة | الوصف |
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

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| key | java.lang.String | المفتاح للقيمة. |
| value | TValue | القيمة. |

**القيمة المرجعة:**
TValue - قيمة البيانات إذا كانت موجودة في مجموعة البيانات، وإلا null.

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


يحصل على البيانات من التخزين.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| key | java.lang.String | مفتاح القيمة. |

**القيمة المرجعة:**
TValue - قيمة البيانات إذا كانت موجودة في مجموعة البيانات، وإلا null.

### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


يحدد ما إذا كان التخزين يحتوي على عنصر بالمفتاح المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| key | java.lang.String | مفتاح القيمة. |

**القيمة المرجعة:**
boolean - صحيح إذا كان التخزين يحتوي على عنصر بالمفتاح المحدد، خطأ غير ذلك.