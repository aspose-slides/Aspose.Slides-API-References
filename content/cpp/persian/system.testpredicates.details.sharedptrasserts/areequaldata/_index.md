---
title: AreEqualData()
second_title: Aspose.Slides برای مرجع API C++
description: "مقایسه‌ی مساوی دو کانتینر با استفاده از System::Object::Equals بر روی عناصر. برای عناصر SmartPtr کار می‌کند."
type: docs
weight: 14
url: /fa/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) function

دو کانتینر را با استفاده از [System::Object::Equals](../../system/object/equals/) بر روی عناصر مقایسه می‌کند. برای عناصر [SmartPtr](../../system/smartptr/) کار می‌کند.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع کانتینر سمت چپ. |
| T2 | نوع کانتینر سمت راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs | const T1\& | مرجع کانتینر سمت چپ. |
| rhs | const T2\& | مرجع کانتینر سمت راست. |

### مقدار بازگشت

در صورتی که عناصر موجود و اندازه‌ها مطابقت داشته باشند True، در غیر این صورت false.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) function

دو کانتینر را با استفاده از عملگر == بر روی عناصر مقایسه می‌کند. برای عناصر غیر-SmartPtr کار می‌کند.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع کانتینر سمت چپ. |
| T2 | نوع کانتینر سمت راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs | const T1\& | کانتینر سمت چپ. |
| rhs | const T2\& | کانتینر سمت راست. |

### مقدار بازگشت

در صورتی که عناصر موجود و اندازه‌ها مطابقت داشته باشند True، در غیر این صورت false.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) function

دو کانتینر از نوع یکسان را به‌صورت برابر مقایسه می‌کند. برای عناصر غیر-SmartPtr کار می‌کند.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع کانتینر سمت چپ. |
| T2 | نوع کانتینر سمت راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs | const T\& | کانتینر سمت چپ. |
| rhs | const T\& | کانتینر سمت راست. |

### مقدار بازگشت

در صورتی که عناصر موجود و اندازه‌ها مطابقت داشته باشند True، در غیر این صورت false.

## موارد مرتبط

* ساختار [IsSmartPtr](../../system/issmartptr/)
* فضای‌نام [System::TestPredicates::Details::SharedPtrAsserts](../)
* کتابخانه [Aspose.Slides](../../)