---
title: Clear()
second_title: Aspose.Slides برای مرجع API C++
description: پشتیبانی نمی‌شود زیرا آرایه‌ای که توسط شیء فعلی نمایان می‌شود فقط خواندنی است.
type: docs
weight: 53
url: /fa/system/array/clear/
---
## Array::Clear() متد

پشتیبانی نمی‌شود زیرا آرایهٔ نمایان‌گر شیء فعلی فقط-خواندنی است.

```cpp
virtual void System::Array<T>::Clear() override
```

## Array::Clear(const ArrayPtr\<Type\>\&, int, int) متد

مقدارهای **count** را که از اندیس **startIndex** در آرایه مشخص‌شده شروع می‌شوند، با مقادیر پیش‌فرض جایگزین می‌کند.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Type | نوع عناصر در آرایه هدف |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | آرایه هدف |
| startIndex | int | [Index](../../index/) که شروع به جایگزینی موارد می‌کند |
| count | int | تعداد مواردی که باید جایگزین شوند |

## موارد مرتبط

* Typedef [ArrayPtr](../../arrayptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)