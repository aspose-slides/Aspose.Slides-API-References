---
title: IsEmpty()
second_title: مرجع API Aspose.Slides برای C++
description: بررسی می‌کند که آیا رشته خالی است.
type: docs
weight: 14
url: /fa/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) متد

بررسی می‌کند که آیا رشته خالی است یا خیر.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) برای بررسی خالی بودن. |

### مقدار بازگشت

True اگر رشته خالی باشد (طول صفر)، false در غیر این صورت.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) متد

بررسی می‌کند که آیا مجموعه خالی است یا خیر.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
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

True اگر مجموعه دارای شمارش صفر عنصر باشد، false در غیر این صورت.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* ساختار [TestTools](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)