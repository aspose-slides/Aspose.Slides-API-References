---
title: KeyValuePair
second_title: Aspose.Slides for C++ API Referansı
description: "Anahtar ve değerin çifti. Bu tip yığına tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tipteki nesneleri yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 378
url: /tr/system.collections.generic/keyvaluepair/
---
## KeyValuePair sınıf


Pair of key and value. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | Anahtarı alır. |
| const TValue\& [get_Value](./get_value/)() const | Değeri alır. |
| int [GetHashCode](./gethashcode/)() const | Anahtar ve değerin özetlerini XORlayarak anahtar-değer çifti karmasını hesaplar. |
| **bool** [IsNull](./isnull/)() const | Her zaman false döndürür. |
| [KeyValuePair](./keyvaluepair/)() | Null anahtar-değer çifti başlatıcısı. |
| [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Yapıcı. |
| [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Tip dönüştürme yapıcı. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | IComparer<KeyValuePair<TKey, TValue>> sınıflarından miras alan sınıflar için yama, hiçbir şeyi karşılaştırmaz. |
| [String](../../system/string/) [ToString](./tostring/)() const | Anahtar-değer çiftini stringe dönüştürür. |

## İlgili

* İsim Alanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)