---
title: IsNullOrEmpty()
second_title: Aspose.Slides برای C++ راهنمای API
description: بررسی می‌کند که آیا مجموعه null یا خالی است.
type: docs
weight: 27
url: /fa/system/testtools/isnullorempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) متد

بررسی می‌کند که آیا مجموعه null یا خالی است.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع مجموعه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | مجموعه برای بررسی. |

### مقدار بازگشت

True اگر مجموعه null باشد یا شمارش عنصر صفر داشته باشد، در غیر این صورت false.

## TestTools::IsNullOrEmpty(const System::String\&) متد

بررسی می‌کند که آیا رشته null یا خالی است.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) برای بررسی. |

### مقدار بازگشت

True اگر رشته null باشد یا طول صفر داشته باشد، در غیر این صورت false.

## موارد مرتبط

* Typedef [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* ساختار [TestTools](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)