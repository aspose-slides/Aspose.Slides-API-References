---
title: GetCustomAttributes()
second_title: مرجع API Aspose.Slides برای C++
description: یک آرایه شامل اشیائی که تمام ویژگی‌های سفارشی اعمال‌شده بر نوع را نشان می‌دهند برمی‌گرداند.
type: docs
weight: 586
url: /fa/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const method

یک آرایه حاوی اشیایی که نمایانگر تمام ویژگی‌های سفارشی اعمال‌شده به نوع هستند را برمی‌گرداند.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const method

یک آرایه حاوی اشیایی که نمایانگر ویژگی‌های خاص اعمال‌شده به نوع هستند را برمی‌گرداند.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | نوع ویژگی که جستجو می‌شود. |
| inherit | **bool** | اینکه آیا ویژگی‌های به ارث‌برده نیز جستجو شوند یا نه. |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* کلاس [SmartPtr](../../smartptr/)
* کلاس [TypeInfo](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)