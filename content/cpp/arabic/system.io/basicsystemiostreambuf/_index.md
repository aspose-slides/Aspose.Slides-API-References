---
title: BasicSystemIOStreamBuf
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل مخزنًا يلتف حول تدفقات شبيهة بـ System::IO::Stream ويسمح باستخدامها كمخزن داخلي لتدفقات شبيهة بـ std::iostream."
type: docs
weight: 40
url: /ar/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf فئة

يمثل مخزنًا يلتف حول تدفقات شبيهة بـ [System::IO::Stream](../stream/) ويتيح استخدامها كمخزن داخلي لتدفقات شبيهة بـ std::iostream.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | يُستخدم في مُنشئ النقل ومُعامل الإسناد بالنقل لإعادة تعيين المؤشرات واستدعاء [swap()](./swap/). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | ينشئ نسخة جديدة من [BasicSystemIOStreamBuf](./). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | ينشئ نسخة جديدة من [BasicSystemIOStreamBuf](./). |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | منشئ نسخة. محذوف. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | منشئ النقل. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | مشغل إسناد النسخ. محذوف. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | مشغل إسناد النقل. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | استدعاء لتبديل *this و right إذا لم تكونا متساويتين. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | المدمر. |

## التعريفات

| تعريف | الوصف |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## انظر أيضًا

* النطاق [System::IO](../)
* المكتبة [Aspose.Slides](../../)