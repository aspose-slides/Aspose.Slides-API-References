---
title: GetDescription()
second_title: مرجع API Aspose.Slides برای C++
description: نام ثابت enumeration که مقدار مشخص‌شده را دارد برمی‌گرداند.
type: docs
weight: 53
url: /fa/system/enum/getdescription/
---
## Enum::GetDescription(T) متد

نام ثابت enumeration که مقدار مشخص‌شده را دارد برمی‌گرداند.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | T | مقدار ثابت enum که نام آن باید برگردانده شود |

### مقدار بازگشتی

نام ثابت enum مشخص‌شده

## موارد مرتبط

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)