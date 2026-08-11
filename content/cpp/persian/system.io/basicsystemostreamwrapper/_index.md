---
title: BasicSystemOStreamWrapper
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر یک wrapper شبیه std::ostream است که از BasicSystemIOStreamBuf به عنوان بافر داخلی استفاده می‌کند."
type: docs
weight: 79
url: /fa/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper کلاس

نمایانگر یک wrapper شبیه std::ostream است که از [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) به عنوان بافر داخلی استفاده می‌کند.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## متدها

| متد | توضیح |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | در سازندهٔ جابه‌جاری و عملگر انتساب جابه‌جایی برای بازنشانی اشاره‌گرها و فراخوانی [swap()](./swap/) استفاده می‌شود. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | یک نمونهٔ جدید از [BasicSystemOStreamWrapper](./) را می‌سازد. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | سازندهٔ نسخه‌برداری. حذف شده. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | سازندهٔ جابه‌جایی. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | عملگر انتساب نسخه‌برداری. حذف شده. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | عملگر انتساب جابه‌جایی. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | فراخوانی برای تعویض *this و **right** در صورتی که برابر نباشند. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## موارد مرتبط

* فضای نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)