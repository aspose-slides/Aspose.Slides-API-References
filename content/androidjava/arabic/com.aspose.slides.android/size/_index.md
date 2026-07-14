---
title: Size
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: فئة لوصف أبعاد العرض والارتفاع بوحدة تعسفية.
type: docs
url: /ar/com.aspose.slides.android/size/
---
**الوراثة:**
java.lang.Object
```
public class Size
```

فئة لوصف أبعاد العرض والارتفاع بوحدة تعسفية.
## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | إنشاء مثال جديد من Size. |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getWidth()](#getWidth--) | الحصول على عرض الحجم. |
| [getHeight()](#getHeight--) | الحصول على ارتفاع الحجم. |
| [equals(Object obj)](#equals-java.lang.Object-) | التحقق مما إذا كان هذا الحجم مساوياً لحجم آخر. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | إرجاع الحجم ممثلاً كسلسلة بالنص بالتنسيق "WxH" |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```

إنشاء مثال جديد من Size.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| width | int | عرض الحجم |
| height | int | ارتفاع الحجم |

### getWidth() {#getWidth--}
```
public int getWidth()
```

الحصول على عرض الحجم.

**القيمة المرجعة:**
int - العرض
### getHeight() {#getHeight--}
```
public int getHeight()
```

الحصول على ارتفاع الحجم.

**القيمة المرجعة:**
int - الارتفاع
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

التحقق مما إذا كان هذا الحجم مساوياً لحجم آخر.

يكون حجماني متساويين إذا وفقط إذا كان كل من عرضهما وارتفاعهما متساويين.

كائن الحجم لا يكون مطلقاً مساويًا لأي نوع آخر من الكائنات.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object |  |

**القيمة المرجعة:**
boolean - true إذا كانت الكائنات متساوية، false خلاف ذلك
### hashCode() {#hashCode--}
```
public int hashCode()
```

**القيمة المرجعة:**
int
### toString() {#toString--}
```
public String toString()
```

إرجاع الحجم ممثلاً كسلسلة بالنص بالتنسيق "WxH"

**القيمة المرجعة:**
java.lang.String - تمثيل النصي للحجم