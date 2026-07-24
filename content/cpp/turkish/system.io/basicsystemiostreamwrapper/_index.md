---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides for C++ API Referansı
description: "İç tampon olarak BasicSystemIOStreamBuf kullanan std::iostream benzeri bir sarmalayıcıyı temsil eder."
type: docs
weight: 53
url: /tr/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper sınıfı

İç tampon olarak [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) kullanan std::iostream benzeri bir sarmalayıcıyı temsil eder.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Yöntemler

| Metod | Açıklama |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | İşaretçileri sıfırlamak ve [swap()](./swap/)'yi çağırmak için taşıma kurucu ve taşıma atama operatöründe kullanılır. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | [BasicSystemIOStreamWrapper](./)'in yeni bir örneğini oluşturur. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | Kopya kurucusu. Silinmiş. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | Taşıma kurucusu. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | Kopya atama operatörü. Silinmiş. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | Taşıma atama operatörü. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | Eşit değillerse *this ve **right**'i takas etmek için çağırır. |

## Typedefler

| Typedef | Açıklama |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Ayrıca Bakınız

* Ad alanı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)