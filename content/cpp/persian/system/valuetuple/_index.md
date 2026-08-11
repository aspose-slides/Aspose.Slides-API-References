---
title: ValueTuple
second_title: Aspose.Slides برای C++ مرجع API
description: کلاسی که یک ساختار داده‌ای ValueTuple را نشان می‌دهد.
type: docs
weight: 1444
url: /fa/system/valuetuple/
---
## کلاس ValueTuple

کلاسی که ساختار داده‌ای [ValueTuple](./) را نشان می‌دهد.

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | تشخیص می‌دهد که آیا اشیای جاری و مشخص‌شده یک‌سان هستند. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | مرجع مقدار مؤلفهٔ شیء [ValueTuple](./) را بر می‌گرداند. |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | مقدار مؤلفهٔ شیء [ValueTuple](./) را بر می‌گرداند. |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | شیء را به این جفت مقدار تجزیه می‌کند. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | مرجع شیء [TypeInfo](../typeinfo/) را که نمایانگر اطلاعات نوع کلاس [ValueTuple](./) است بر می‌گرداند. |
| [ValueTuple](./valuetuple/)() |  |
| [ValueTuple](./valuetuple/)(Args...) | یک شیء جفت مقدار می‌سازد. |

## مراجع

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)