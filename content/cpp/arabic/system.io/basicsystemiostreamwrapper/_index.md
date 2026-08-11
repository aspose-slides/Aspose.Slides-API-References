---
title: BasicSystemIOStreamWrapper
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يمثل غلافًا شبيهًا بـ std::iostream يستخدم BasicSystemIOStreamBuf كعازل داخلي."
type: docs
weight: 53
url: /ar/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper فئة

يمثل غلافًا شبيهًا بـ std::iostream يستخدم [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) كعازل داخلي.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | يُستخدم في مُنشئ النقل ومُعامل الإسناد بنقل الحركة لإعادة تعيين المؤشرات واستدعاء [swap()](./swap/). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | ينشئ نسخة جديدة من [BasicSystemIOStreamWrapper](./). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | منشئ نسخة. محذوف. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | منشئ نقل. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | عامل إسناد نسخة. محذوف. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | عامل إسناد نقل. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | استدعاء لتبديل *this و **right** إذا لم يكونا متساويين. |

## تعريفات الأنواع

| تعريف نوع | الوصف |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## انظر أيضًا

* مساحة الأسماء [System::IO](../)
* مكتبة [Aspose.Slides](../../)