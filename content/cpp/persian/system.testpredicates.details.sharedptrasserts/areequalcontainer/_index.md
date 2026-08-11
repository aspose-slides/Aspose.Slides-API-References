---
title: AreEqualContainer()
second_title: مرجع API Aspose.Slides برای C++
description: دو مخزن را به صورت برابر با استفاده از عملگر == بر روی عناصر مقایسه می‌کند. برای عناصری که SmartPtr نیستند کار می‌کند.
type: docs
weight: 1
url: /fa/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) تابع

به‌صورت برابر دو مخزن را با استفاده از operator == روی عناصر مقایسه می‌کند. برای عناصری که SmartPtr نیستند کار می‌کند.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع مخزن LHS. |
| T2 | نوع مخزن RHS. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs | const T1\& | مخزن LHS. |
| rhs | const T2\& | مخزن RHS. |

### مقدار بازگشت

اگر عناصر موجود و اندازه‌ها مطابقت داشته باشند true، در غیر این صورت false.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) تابع

به‌صورت برابر دو مخزن را با استفاده از [System::Object::Equals](../../system/object/equals/) روی عناصر مقایسه می‌کند. برای عناصر [SmartPtr](../../system/smartptr/) کار می‌کند.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع مخزن LHS. |
| T2 | نوع مخزن RHS. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs | const T1\& | مرجع مخزن LHS. |
| rhs | const T2\& | مرجع مخزن RHS. |

### مقدار بازگشت

اگر عناصر موجود و اندازه‌ها مطابقت داشته باشند true، در غیر این صورت false.

## موارد مرتبط

* Struct [IsSmartPtr](../../system/issmartptr/)
* فضای‌نام [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)