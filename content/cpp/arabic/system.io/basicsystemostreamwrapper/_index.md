---
title: BasicSystemOStreamWrapper
second_title: مرجع API Aspose.Slides لـ C++
description: "يمثل غلافًا شبيهًا بـ std::ostream يستخدم BasicSystemIOStreamBuf كذاكرة داخلية."
type: docs
weight: 79
url: /ar/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper فئة

يمثل غلافًا شبيهًا بـ std::ostream يستخدم [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) كذاكرة داخلية.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | يُستخدم في مُنشئ النقل ومُعامل الإسناد بالنقل لإعادة تعيين المؤشرات واستدعاء [swap()](./swap/). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | يقوم بإنشاء نسخة جديدة من [BasicSystemOStreamWrapper](./). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | منشئ النسخ. محذوف. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | منشئ النقل. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | عامل الإسناد النسخي. محذوف. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | عامل الإسناد بالنقل. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | استدعاء لتبديل *this و **right** إذا لم يكونا متساوين. |

## الأنواع المعرفة

| نوع تعريف | الوصف |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## انظر أيضًا

* نطاق [System::IO](../)
* مكتبة [Aspose.Slides](../../)