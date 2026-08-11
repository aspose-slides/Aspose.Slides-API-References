---
title: ObjectToUnknown()
second_title: Aspose.Slides برای C++ مرجع API
description: Object را به نوع ناشناخته تبدیل می‌کند و هر دو نوع smart pointer و وضعیت bpxed را پردازش می‌نماید.
type: docs
weight: 131
url: /fa/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) متد

تبدیل [Object](../../object/) به نوع ناشناخته، با پردازش هر دو نوع اشاره‌گر هوشمند و وضعیت مقدار bpxed.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوعی که باید [Object](../../object/) به آن تبدیل شود. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) برای تبدیل. |

### مقدار بازگشت

یا مقدار بازبسته یا اشاره‌گر تبدیل‌شده.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) متد

تبدیل [Object](../../object/) به نوع ناشناخته، با پردازش هر دو نوع اشاره‌گر هوشمند و وضعیت مقدار بسته‌شده.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوعی که باید [Object](../../object/) به آن تبدیل شود. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) برای تبدیل. |

### مقدار بازگشت

یا مقدار بازبسته یا اشاره‌گر تبدیل‌شده.

## موارد مرتبط

* کلاس [SmartPtr](../../smartptr/)
* کلاس [Object](../../object/)
* کلاس [ObjectExt](../)
* ساختار [IsSmartPtr](../../issmartptr/)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)