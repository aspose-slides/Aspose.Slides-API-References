---
title: BasicSystemIStreamWrapper
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر یک wrapper شبیه std::istream است که از BasicSystemIOStreamBuf به عنوان بافر داخلی استفاده می‌کند."
type: docs
weight: 66
url: /fa/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper کلاس

نمایانگر یک wrapper شبیه std::istream است که از [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) به عنوان بافر داخلی استفاده می‌کند.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## متدها

| متد | توضیح |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | در سازنده جابه‌جایی و عملگر اختصاص جابه‌جایی برای بازنشانی اشاره‌گرها و فراخوانی [swap()](./swap/) استفاده می‌شود. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | یک نمونه جدید از [BasicSystemIStreamWrapper](./) را ایجاد می‌کند. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | سازنده کپی. حذف شده. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | سازنده جابه‌جایی. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | عملگر اختصاص کپی. حذف شده. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | عملگر اختصاص جابه‌جایی. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | فراخوانی برای جابجایی *this و **right** در صورتی که برابر نباشند. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## مراجع دیگر

* فضای نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)