---
title: LINQ_ThenBy()
second_title: مرجع API Aspose.Slides برای C++
description: یک ترتیب‌بندی پسین از عناصر در یک دنباله به صورت صعودی بر اساس یک کلید انجام می‌دهد.
type: docs
weight: 27
url: /fa/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) method

عملیات مرتب‌سازی پسین عناصر در یک دنباله به ترتیب صعودی بر اساس یک کلید را انجام می‌دهد.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Key | نوع کلیدی که توسط keySelector برگردانده می‌شود. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | یک تابع برای استخراج یک کلید از هر عنصر. |

### مقدار بازگشتی

[System::Linq::IOrderedEnumerable](../) که عناصر آن بر اساس یک کلید مرتب شده‌اند.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) method

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IOrderedEnumerable](../)
* کلاس [Func](../../../system/func/)
* فضای‌نام [System::Linq](../../)
* کتابخانه [Aspose.Slides](../../../)