---
title: Compare()
second_title: Aspose.Slides برای C++ مرجع API
description: دو مقدار را مقایسه می‌کند.
type: docs
weight: 2731
url: /fa/system/compare/
---
## System::Compare(const TA\&, const TB\&) تابع

دو مقدار را مقایسه می‌کند.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TA | نوع اولین مقایسه‌کننده |
| TB | نوع دومین مقایسه‌کننده |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | const TA\& | اولین مقایسه‌کننده |
| b | const TB\& | دومین مقایسه‌کننده |

### مقدار بازگشت

- 1 اگر **a** کمتر از **b** باشد؛ 0 اگر مقادیر برابر باشند؛ 1 اگر **a** بزرگ‌تر از **b** باشد

## System::Compare(const TA\&, const TB\&) تابع

دو مقدار عددی شناور را مقایسه می‌کند.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TA | نوع اولین مقایسه‌کننده |
| TB | نوع دومین مقایسه‌کننده |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | const TA\& | اولین مقایسه‌کننده |
| b | const TB\& | دومین مقایسه‌کننده |

### مقدار بازگشت

- 1 اگر **a** کمتر از **b** باشد؛ 0 اگر مقادیر برابر باشند؛ 1 اگر **a** بزرگ‌تر از **b** باشد

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)