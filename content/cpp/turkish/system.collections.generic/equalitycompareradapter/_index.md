---
title: EqualityComparerAdapter
second_title: Aspose.Slides for C++ API Referansı
description: "Adapter, IEqualityComparer'ı STL tarzı koleksiyonlar ve algoritmalarla kullanmayı mümkün kılar. IEqualityComparer ayarlıysa kullanılır. Ayarlı değilse operator ==, Object::Equals veya T::Equals kullanılır, hangisi mevcutsa."
type: docs
weight: 664
url: /tr/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter struct

Adapter, [IEqualityComparer](../iequalitycomparer/) ile STL tarzı koleksiyon ve algoritmaların kullanılmasını mümkün kılar. [IEqualityComparer](../iequalitycomparer/) ayarlıysa kullanılır. Ayarlı değilse operator ==, [Object::Equals](../../system/object/equals/) veya T::Equals kullanılır, hangisi mevcutsa.

```cpp
template<class T>class EqualityComparerAdapter
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Karşılaştırılan tip. |

## Metotlar

| Metot | Açıklama |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | Hiçbir karşılaştırıcı kullanmadan adaptör oluşturur. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Verilen karşılaştırıcı ile adaptör oluşturur. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | İki nesneyi karşılaştırır. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Karşılaştırıcı ayarlar. |

## Ayrıca Bakınız

* AdAlanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)