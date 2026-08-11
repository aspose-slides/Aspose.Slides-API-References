---
title: UnknownToObject()
second_title: Aspose.Slides برای C++ مرجع API
description: نوع نامشخص را به Object تبدیل می‌کند و هر دو وضعیت نوع اشاره‌گر هوشمند و نوع مقدار را مدیریت می‌نماید.
type: docs
weight: 118
url: /fa/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) متد

نوع نامشخص را به [Object](../../object/) تبدیل می‌کند و هر دو وضعیت نوع اشاره‌گر هوشمند و نوع مقدار را مدیریت می‌نماید.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوعی برای تبدیل به [Object](../../object/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | T | [Object](../../object/) برای تبدیل. |

### مقدار بازگشتی

اشاره‌گر هوشمند به [Object](../../object/) که یا اشاره‌گر تبدیل‌شده یا مقدار بسته‌ شده است.

## ObjectExt::UnknownToObject(const T\&) متد

نوع نامشخص را به [Object](../../object/) تبدیل می‌کند و هم‌زمان برای موارد اشاره‌گر هوشمند و نوع مقدار مدیریت می‌شود.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوعی برای تبدیل به [Object](../../object/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) برای تبدیل. |

### مقدار بازگشتی

اشاره‌گر هوشمند به [Object](../../object/) که یا اشاره‌گر تبدیل‌شده یا مقدار بسته‌ شده است.

## موارد مرتبط

* کلاس [SmartPtr](../../smartptr/)
* کلاس [Object](../../object/)
* کلاس [ObjectExt](../)
* ساختار [IsSmartPtr](../../issmartptr/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)