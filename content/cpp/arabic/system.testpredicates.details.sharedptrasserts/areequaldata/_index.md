---
title: AreEqualData()
second_title: مرجع API Aspose.Slides للغة C++
description: "يقارن بالتساوي بين حاويتين باستخدام System::Object::Equals على العناصر. يعمل مع عناصر SmartPtr."
type: docs
weight: 14
url: /ar/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1&, const T2&) دالة

يُقارن المتساوي بين حاويتين باستخدام [System::Object::Equals](../../system/object/equals/) على العناصر. يعمل مع عناصر [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | نوع الحاوية LHS. |
| T2 | نوع الحاوية RHS. |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1& | مرجع الحاوية LHS. |
| rhs | const T2& | مرجع الحاوية RHS. |

### قيمة الإرجاع

صحيح إذا تطابقت العناصر المتضمنة والأحجام، وإلا خطأ.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1&, const T2&) دالة

يُقارن المتساوي بين حاويتين باستخدام العامل == على العناصر. يعمل مع عناصر غير SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | نوع الحاوية LHS. |
| T2 | نوع الحاوية RHS. |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1& | الحاوية LHS. |
| rhs | const T2& | الحاوية RHS. |

### قيمة الإرجاع

صحيح إذا تطابقت العناصر المتضمنة والأحجام، وإلا خطأ.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T&, const T&) دالة

يُقارن المتساوي بين حاويتين من نوع متطابق. يعمل مع عناصر غير SmartPtr.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | نوع الحاوية LHS. |
| T2 | نوع الحاوية RHS. |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T& | الحاوية LHS. |
| rhs | const T& | الحاوية RHS. |

### قيمة الإرجاع

صحيح إذا تطابقت العناصر المتضمنة والأحجام، وإلا خطأ.

## راجع أيضًا

* هيكل [IsSmartPtr](../../system/issmartptr/)
* مساحة الاسم [System::TestPredicates::Details::SharedPtrAsserts](../)
* مكتبة [Aspose.Slides](../../)