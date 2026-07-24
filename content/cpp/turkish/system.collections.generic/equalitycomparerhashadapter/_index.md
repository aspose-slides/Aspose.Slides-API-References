---
title: EqualityComparerHashAdapter
second_title: Aspose.Slides için C++ API Referansı
description: Hash'leme için IEqualityComparer kullanmak üzere adaptör. Karşılaştırıcı nesnesi ayarlanmışsa onu kullanır; aksi takdirde DictionaryHashSelector struct kullanılarak seçilen mevcut hash yöntemini kullanır.
type: docs
weight: 677
url: /tr/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct

Adapter to use [IEqualityComparer](../iequalitycomparer/) for hashing. Uses comparator object, if set; otherwise, uses available hash method selected using [DictionaryHashSelector](../dictionaryhashselector/) struct.

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Hashed | tür. |

## Yöntemler

| Metot | Açıklama |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | Kullanılacak karşılaştırıcı olmadan adaptör oluşturur. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Kullanılacak verilen karşılaştırıcıyla adaptör oluşturur. |
| std::size_t [operator()](./operator_call/)(const T\&) const | Karma (hash) değerini hesaplar. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Kullanılacak karşılaştırıcıyı ayarlar. |

## Ayrıca Bakınız

* Ad alanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)