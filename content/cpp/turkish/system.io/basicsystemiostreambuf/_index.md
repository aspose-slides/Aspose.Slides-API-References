---
title: BasicSystemIOStreamBuf
second_title: Aspose.Slides için C++ API Referansı
description: "System::IO::Stream benzeri akışları saran bir tamponu temsil eder ve bunların bir std::iostream benzeri akışın dahili tamponu olarak kullanılmasına olanak tanır."
type: docs
weight: 40
url: /tr/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf sınıfı

[System::IO::Stream](../stream/) benzeri akışları saran bir tamponu temsil eder ve bunların bir std::iostream benzeri akışın dahili tamponu olarak kullanılmasına olanak tanır.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Yöntemler

| Metod | Açıklama |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | Taşıma yapıcı ve taşıma atama operatöründe işaretçileri sıfırlamak ve [swap()](./swap/) çağırmak için kullanılır. |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Yeni bir [BasicSystemIOStreamBuf](./) örneği oluşturur. |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Yeni bir [BasicSystemIOStreamBuf](./) örneği oluşturur. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Kopya yapıcı. Silinmiş. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Taşıma yapıcı. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Kopya atama operatörü. Silinmiş. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Taşıma atama operatörü. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | Eşit değillerse *this ve right'ı takas etmek için çağrılır. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Yıkıcı. |

## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Ayrıca Bakınız

* İsim uzayı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)