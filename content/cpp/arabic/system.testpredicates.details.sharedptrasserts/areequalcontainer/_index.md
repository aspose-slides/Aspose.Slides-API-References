---
title: AreEqualContainer()
second_title: مرجع API Aspose.Slides للغة C++
description: يقارن المتساوي بين حاويتين باستخدام operator == على العناصر. يعمل مع العناصر غير SmartPtr.
type: docs
weight: 1
url: /ar/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) دالة

يقارن المتساوي بين حاويتين باستخدام operator == على العناصر. يعمل مع العناصر غير SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T1 | نوع الحاوية LHS. |
| T2 | نوع الحاوية RHS. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs | const T1\& | حاوية LHS. |
| rhs | const T2\& | حاوية RHS. |

### قيمة الإرجاع

صحيح إذا تطابقت العناصر والأحجام الموجودة، خطأ خلاف ذلك.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) دالة

يقارن المتساوي بين حاويتين باستخدام [System::Object::Equals](../../system/object/equals/) على العناصر. يعمل مع عناصر [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T1 | نوع الحاوية LHS. |
| T2 | نوع الحاوية RHS. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs | const T1\& | مرجع حاوية LHS. |
| rhs | const T2\& | مرجع حاوية RHS. |

### قيمة الإرجاع

صحيح إذا تطابقت العناصر والأحجام الموجودة، خطأ خلاف ذلك.

## انظر أيضًا

* بنية [IsSmartPtr](../../system/issmartptr/)
* نطاق [System::TestPredicates::Details::SharedPtrAsserts](../)
* مكتبة [Aspose.Slides](../../)