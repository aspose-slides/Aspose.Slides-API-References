---
title: ComparerAdapter
second_title: Aspose.Slides için C++ API Referansı
description: STL ortamında IComparer kullanmak için adaptör. IComparer ayarlanmışsa kullanır; aksi takdirde operator < (varsa) kullanır veya (yoksa) false döndürür.
type: docs
weight: 638
url: /tr/system.collections.generic/compareradapter/
---
## ComparerAdapter yapısı

STL ortamında [IComparer](../icomparer/) kullanmak için adaptör. [IComparer](../icomparer/) ayarlanmışsa kullanır; aksi takdirde operator < (varsa) kullanır veya (yoksa) false döndürür.

```cpp
template<class T>class ComparerAdapter
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Karşılaştırılan tür. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | Karşılaştırıcı olmadan adaptörü oluşturur. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Adaptörü oluşturur. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) işlevi, operator < mevcut olan tipler için. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) işlevi, operator < mevcut olmayan tipler için. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | Karşılaştırıcı nesnesini ayarlar. |

## Ayrıca Bakınız

* İsim alanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)