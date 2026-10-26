---
title: IsNullOrEmpty()
second_title: مرجع API Aspose.Slides للغة C++
description: يتحقق مما إذا كانت المجموعة null أو فارغة.
type: docs
weight: 27
url: /ar/system/testtools/isnullarempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) طريقة

يتحقق مما إذا كانت المجموعة null أو فارغة.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع المجموعة. |

### معاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | مجموعة للفحص. |

### قيمة الإرجاع

صحيح إذا كانت المجموعة null أو عدد العناصر صفر، خطأ خلاف ذلك.

## TestTools::IsNullOrEmpty(const System::String\&) طريقة

يتحقق مما إذا كانت السلسلة null أو فارغة.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```

### معاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) للفحص. |

### قيمة الإرجاع

صحيح إذا كانت السلسلة null أو طولها صفر، خطأ خلاف ذلك.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* بنية [TestTools](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)