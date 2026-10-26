---
title: Is()
second_title: Aspose.Slides برای C++ مرجع API
description: بررسی می‌کند که آیا شیء اشاره شده از نوع خاص یا نوع فرزند آن است. رفتار مشابه عملگر 'is' در C# را دنبال می‌کند.
type: docs
weight: 300
url: /fa/system/smartptr/is/
---
## SmartPtr::Is(const System::TypeInfo\&) const متد

Checks if pointed object is of specific type or its child type. Follows C# 'is' semantics.

```cpp
bool System::SmartPtr<T>::Is(const System::TypeInfo &target) const
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | Specifies target type to check against. |

### مقدار بازگشتی

True if C# 'is'-style check is positive and false otherwise.

## توضیحات

Implementation.

## موارد مرتبط

* کلاس [TypeInfo](../../typeinfo/)
* کلاس [SmartPtr](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)