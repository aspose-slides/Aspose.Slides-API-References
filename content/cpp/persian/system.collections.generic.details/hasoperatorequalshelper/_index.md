---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides برای مرجع API C++
description: تابع کمکی برای تعیین اینکه آیا کلاس خاصی عملگر == دارد یا خیر.
type: docs
weight: 235
url: /fa/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) تابع


تابع کمکی برای تعیین این که آیا کلاس خاصی عملگر == دارد یا نه.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع برای بررسی. |
| Dummy | آرگومان ساختگی برای جادوی SFINAE. |

### مقدار بازگشت

مقدار std::true_type اگر operator == موجود باشد و در غیر این صورت false.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) تابع


تابع کمکی برای تعیین این که آیا کلاس خاصی عملگر == دارد یا نه.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```


### مقدار بازگشت

مقدار std::true_type اگر operator == موجود باشد و در غیر این صورت false.

## همچنین ببینید

* فضای‌نام [System::Collections::Generic::Details](../)
* کتابخانه [Aspose.Slides](../../)