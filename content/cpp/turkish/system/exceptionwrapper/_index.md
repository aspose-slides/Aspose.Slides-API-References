---
title: ExceptionWrapper
second_title: Aspose.Slides for C++ API Referansı
description: Exception sınıfından türetilen istisnaların sarmalayıcısını temsil eden şablon.
type: docs
weight: 833
url: /tr/system/exceptionwrapper/
---
## ExceptionWrapper sınıf

Template that represents wrapper of exceptions that are derived from Exception class.

```cpp
template<typename T>class ExceptionWrapper
```

## Metotlar

| Method | Description |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | [ExceptionWrapper](./) sınıfının hiçbir istisna temsil etmeyen null örneğini oluşturur. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | [ExceptionWrapper](./) sınıfının geçen göstergesi içeren bir örneğini oluşturur. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | Kopya yapıcı. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | Taşıma yapıcı. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Parametreleri Exception sınıfının kurucularına ileten ve yeni bir Exception sınıfı örneğini tutan akıllı göstergeyi oluşturan kurucu. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | SharedPtr<Object>'e örtük dönüşüm operatörü |
| T * [operator->](./operator_minus_greater/)() const | Exception nesnesinin üyelerine erişim sağlar. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | Atama operatörü. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | Taşıma atama operatörü. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Exception türü için [System::TypeInfo](../typeinfo/) nesnesini almanın kısayolu. |
## Typedef'ler

| Typedef | Description |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Dönüştürme işlevleri için kullanılır. |
## Ayrıca Bakınız

* İsim Uzayı [System](../)
* Kütüphane [Aspose.Slides](../../)