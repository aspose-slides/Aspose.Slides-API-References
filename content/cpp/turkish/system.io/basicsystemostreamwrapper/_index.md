---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides for C++ API Referansı
description: "Temel sistem IO akışı tamponu olarak BasicSystemIOStreamBuf kullanan bir std::ostream benzeri sarmalayıcıyı temsil eder."
type: docs
weight: 79
url: /tr/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper sınıfı


İç tampon olarak [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) kullanan bir std::ostream benzeri sarmalayıcıyı temsil eder.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | İşaretçileri sıfırlamak ve [swap()](./swap/)'yi çağırmak için taşıma yapıcı ve taşıma atama operatöründe kullanılır. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Yeni bir [BasicSystemOStreamWrapper](./) örneği oluşturur. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | Kopya yapıcı. Silinmiş. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Taşıma yapıcı. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | Kopya atama operatörü. Silinmiş. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Taşıma atama operatörü. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | *this ve **right**'ı değiştirmek için çağırılır, eşit olmadıkları sürece. |
## Typedef'lar

| Typedef | Açıklama |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
## Ayrıca Bakınız

* Ad Alanı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)