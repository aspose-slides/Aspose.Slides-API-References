---
title: BasicSystemIOStreamBuf
second_title: مرجع API Aspose.Slides برای C++
description: "یک بافر را نمایش می‌دهد که جریان‌های مشابه System::IO::Stream را می‌پوشاند و اجازه می‌دهد به‌عنوان بافر داخلی جریان‌های مشابه std::iostream استفاده شوند."
type: docs
weight: 40
url: /fa/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf کلاس

یک بافر را که جریان‌های مشابه [System::IO::Stream](../stream/) را می‌پیچند و اجازه می‌دهد به‌عنوان بافر داخلی جریان‌های مشابه std::iostream استفاده شوند، نمایان می‌سازد.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## متدها

| متد | توضیح |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | در سازندهٔ جابه‌جایی و عملگر انتساب جابه‌جایی برای بازنشانی اشاره‌گرها و فراخوانی [swap()](./swap/) استفاده می‌شود. |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | یک نمونهٔ جدید از [BasicSystemIOStreamBuf](./) را می‌سازد. |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | یک نمونهٔ جدید از [BasicSystemIOStreamBuf](./) را می‌سازد. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | سازندهٔ کپی. حذف شده. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | سازندهٔ جابه‌جایی. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | عملگر انتساب کپی. حذف شده. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | عملگر انتساب جابه‌جایی. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | برای تعویض *this و right استفاده می‌شود، اگر برابر نباشند. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | سازندهٔ مخرب. |
## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |
## مراجع

* فضای‌نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)