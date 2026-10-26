---
title: IsEmpty()
second_title: Aspose.Slides لـ C++ دليل API
description: يتحقق مما إذا كانت السلسلة فارغة.
type: docs
weight: 14
url: /ar/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) طريقة

يتحقق مما إذا كانت السلسلة فارغة.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) للتحقق من كونها فارغة. |

### قيمة الإرجاع

صحيح إذا كانت السلسلة فارغة (طول صفر)، خطأ في غير ذلك.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) طريقة

يتحقق مما إذا كانت المجموعة فارغة.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع المجموعة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | المجموعة للتحقق. |

### قيمة الإرجاع

صحيح إذا كان عدد عناصر المجموعة يساوي صفر، خطأ في غير ذلك.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* بنية [TestTools](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)