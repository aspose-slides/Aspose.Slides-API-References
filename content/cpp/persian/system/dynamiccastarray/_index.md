---
title: DynamicCastArray()
second_title: Aspose.Slides برای مرجع API C++
description: تبدیل عناصر آرایهٔ مشخص‌شده به نوع دیگری را انجام می‌دهد.
type: docs
weight: 2991
url: /fa/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) تابع


عملگر تبدیل عناصر آرایهٔ مشخص‌شده به نوع دیگری را انجام می‌دهد.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| To | نوعی که عناصر آرایهٔ مشخص‌شده به آن تبدیل می‌شوند |
| From | نوع عناصری که در آرایهٔ مورد نظر وجود دارند و باید تبدیل شوند |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | اشاره‌گر مشترک به آرایه‌ای که شامل عناصری است که باید تبدیل شوند |

### مقدار بازگشتی

یک اشاره‌گر به آرایهٔ جدیدی که شامل عناصری از نوع **To** معادل عناصر **from** است

منسوخ شده
:   برای سازگاری عقبگرد افزوده شده است. به جای آن از ExplicitCast استفاده کنید.

## موارد مرتبط

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)