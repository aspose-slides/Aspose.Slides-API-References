---
title: With()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينسخ سجل المرجع ويطبق عليه عامل تهيئة.
type: docs
weight: 2614
url: /ar/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) دالة


ينسخ سجل المرجع ويطبق عامل التهيئة عليه.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```


### معاملات القالب

| معامل | الوصف |
| --- | --- |
| T | نوع السجل للنسخ. |
| A | نوع عامل التهيئة. |

### وسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | مؤشر مشترك للكائن المراد نسخه وتهيئته. |
| initializer | const A\& | عامل التهيئة الذي يُطبَّق على نسخة السجل. |

### قيمة الإرجاع

مؤشر مشترك للسجل المستنسخ.

## System::With(const T\&, const A\&) دالة


ينسخ سجل الهيكل ويطبق عامل التهيئة عليه.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```


### معاملات القالب

| معامل | الوصف |
| --- | --- |
| T | نوع السجل للنسخ. |
| A | نوع عامل التهيئة. |

### وسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| record | const T\& | السجل للنسخ والتهيئة. |
| initializer | const A\& | عامل التهيئة الذي يُطبَّق على نسخة السجل. |

### قيمة الإرجاع

السجل المنسوخ.

## انظر أيضًا

* تعريف النوع [SharedPtr](../sharedptr/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)