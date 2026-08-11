---
title: Equals()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که آیا بازه زمانی نمایان‌ساز شیء جاری برابر با بازه زمانی نمایان‌ساز شیء مشخص‌شده است یا خیر.
type: docs
weight: 40
url: /fa/system/timespan/equals/
---
## TimeSpan::Equals(TimeSpan) const متد


تعیین می‌کند که آیا بازه زمانی نمایان‌ساز شیء جاری برابر با بازه زمانی نمایان‌ساز شیء مشخص‌شده است یا خیر.

```cpp
constexpr bool System::TimeSpan::Equals(TimeSpan value) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [TimeSpan](../) | شیء [TimeSpan](../) برای مقایسه با شیء جاری |

### مقدار بازگشتی

True اگر شیء جاری و شیء مشخص‌شده همان بازه زمانی را نمایان‌ساز باشند، در غیر اینصورت - false

## TimeSpan::Equals(const SharedPtr\<Object\>\&) const متد


تعیین می‌کند که آیا بازه زمانی نمایان‌ساز شیء جاری برابر با بازه زمانی نمایان‌ساز شیء مشخص‌شده است یا خیر.

```cpp
bool System::TimeSpan::Equals(const SharedPtr<Object> &obj) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | شیء [TimeSpan](../) برای مقایسه با شیء جاری |

### مقدار بازگشتی

True اگر شیء جاری و شیء مشخص‌شده همان بازه زمانی را نمایان‌ساز باشند، در غیر اینصورت - false

## TimeSpan::Equals(TimeSpan, TimeSpan) متد


در صورتی که اشیاء مشخص‌شده همان بازه زمانی را نمایان‌ساز باشند true برمی‌گرداند، در غیر اینصورت false.

```cpp
static constexpr bool System::TimeSpan::Equals(TimeSpan a, TimeSpan b)
```

## مراجع

* Typedef [SharedPtr](../../sharedptr/)
* کلاس [TimeSpan](../)
* کلاس [Object](../../object/)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)