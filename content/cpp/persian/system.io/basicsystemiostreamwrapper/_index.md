---
title: BasicSystemIOStreamWrapper
second_title: مرجع API Aspose.Slides برای C++
description: "نمایش‌دهنده‌ی یک wrapper شبیه std::iostream است که BasicSystemIOStreamBuf را به‌ عنوان بافر داخلی استفاده می‌کند."
type: docs
weight: 53
url: /fa/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper کلاس

نمایش‌دهنده یک wrapper شبیه std::iostream است که [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) را به‌ عنوان بافر داخلی استفاده می‌کند.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## متدها

| Method | توضیح |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | در سازنده انتقال و عملگر انتساب انتقال برای بازنشانی اشاره‌گرها و فراخوانی [swap()](./swap/) استفاده می‌شود. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | یک نمونه جدید از [BasicSystemIOStreamWrapper](./) می‌سازد. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | سازنده کپی. حذف شده. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | سازنده انتقال. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | عملگر انتساب کپی. حذف شده. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | عملگر انتساب انتقال. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | در صورتی که برابر نباشند، برای تعویض *this و **right** فراخوانی می‌شود. |

## تعاریف نوع

| Typedef | توضیح |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## موارد مرتبط

* فضای نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)