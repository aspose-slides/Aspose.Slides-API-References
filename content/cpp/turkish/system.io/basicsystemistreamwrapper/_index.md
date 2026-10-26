---
title: BasicSystemIStreamWrapper
second_title: Aspose.Slides için C++ API Referansı
description: "İç tampon olarak BasicSystemIOStreamBuf kullanan bir std::istream-benzeri sarmalayıcıyı temsil eder."
type: docs
weight: 66
url: /tr/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper sınıf


İç tampon olarak [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) kullanan bir std::istream-benzeri sarmalayıcıyı temsil eder.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | Taşıma yapıcı ve taşıma atama operatöründe işaretçileri sıfırlamak ve [swap()](./swap/) çağırmak için kullanılır. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | [BasicSystemIStreamWrapper](./) yeni bir örnek oluşturur. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | Kopya yapıcı. Silinmiş. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | Taşıma yapıcı. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | Kopya atama operatörü. Silinmiş. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | Taşıma atama operatörü. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | *this ve **right** eşit değilse takas yapılır. |
## Tip Tanımlamaları

| Tip Tanımı | Açıklama |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
## Ayrıca Bakınız

* Ad alanı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)