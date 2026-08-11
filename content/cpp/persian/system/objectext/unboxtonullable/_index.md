---
title: UnboxToNullable()
second_title: مرجع API Aspose.Slides برای C++
description: شیء را به نوع nullable باز می‌کند.
type: docs
weight: 79
url: /fa/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) متد

شیء را به نوع nullable باز می‌کند.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع مقصد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) برای باز کردن. |
| safe | **bool** | اگر true باشد، در صورت شکست nullptr بر می‌گرداند، در غیر این صورت InvalidCastException را پرتاب می‌کند. |

### مقدار بازگشتی

Unboxed nullable value (could be null).

## موارد مرتبط

* کلاس [Nullable](../../nullable/)
* کلاس [SmartPtr](../../smartptr/)
* کلاس [Object](../../object/)
* کلاس [ObjectExt](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)