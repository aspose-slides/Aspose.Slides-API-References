---
title: Span
second_title: Aspose.Slides için C++ API Referansı
description: "Arbitrary belleğin ardışık bir bölgesini temsil eder; C++20'nin std::span'ine benzer."
type: docs
weight: 1262
url: /tr/system/span/
---
## Span sınıfı

Arbitrary belleğin ardışık bir bölgesini temsil eder; C++20'nin std::span'ine benzer.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi. Bu sınıf, nesnelerin ardışık dizileriyle güvenli bir şekilde çalışmak için tip güvenli bir yol sağlar. Dizileri, yığın dizilerini veya ham işaretçileri saran ve sınır denetimini sürdüren bir şekilde kullanılabilir. [Span](./) belleği işaret ettiği belleği sahiplenmez - sadece mevcut belleğe bir görünümdür. |

## Yöntemler

| Metod | Açıklama |
| --- | --- |
| void [Clear](./clear/)() const | Tüm öğeleri varsayılan değere ayarlayarak span'in içeriğini temizler. |
| void [Fill](./fill/)(const T\&) const | Span'i belirtilen değerle doldurur. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Bir diziyi [Span](./)'ye dönüştürür. |

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)