---
title: idx_get()
second_title: مرجع API Aspose.Slides برای C++
description: یک کوکی را از مجموعه کوکی‌ها در ایندکس مشخص شده برمی‌گرداند.
type: docs
weight: 40
url: /fa/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) متد


یک کوکی را از مجموعه کوکی‌ها به‌صورت ایندکس مشخص شده برمی‌گرداند.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | ایندکس یک کوکی که باید برگردانده شود. |

### مقدار بازگشت

یک کوکی در ایندکس مشخص شده.

## CookieCollection::idx_get(String) متد


یک کوکی را از مجموعه کوکی‌ها بر اساس نام مشخص شده برمی‌گرداند.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام یک کوکی که باید برگردانده شود. |

### مقدار بازگشت

یک کوکی از مجموعه کوکی‌ها بر اساس نام مشخص شده در صورتی که یافت شود، در غیر این صورت nullptr.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Cookie](../../cookie/)
* کلاس [CookieCollection](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)