---
title: BasicSystemIStreamWrapper
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يمثل غلافًا شبيهًا بـ std::istream يستخدم BasicSystemIOStreamBuf كملف مؤقت داخلي."
type: docs
weight: 66
url: /ar/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper فئة


يمثل غلافًا مشابهًا لـ std::istream يستخدم [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) كملف مؤقت داخلي.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## الطرق

| Method | Description |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | يُستخدم في بنّاء النقل ومُعامل إسناد النقل لإعادة ضبط المؤشرات واستدعاء [swap()](./swap/). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | يبني نسخة جديدة من الـ [BasicSystemIStreamWrapper](./). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | منشئ نسخة. محذوف. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | منشئ نقل. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | عامل إسناد نسخة. محذوف. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | عامل إسناد نقل. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | استدعاء لتبديل *this و **right** إذا لم يكونا متساويين. |
## تعريفات الأنواع

| Typedef | Description |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
## راجع أيضًا

* المساحة الاسمية [System::IO](../)
* المكتبة [Aspose.Slides](../../)