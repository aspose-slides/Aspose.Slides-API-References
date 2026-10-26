---
title: operator()()
second_title: Aspose.Slides için C++ API Referansı
description: operator < mevcut olan tipler için karşılaştırma fonksiyonu.
type: docs
weight: 27
url: /tr/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q&, const Q&) const metod

[Comparison](../../../system/comparison/) fonksiyonu, < operatörü mevcut olan tipler için.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Q | Karşılaştırılan tip; tip dönüşümü kullanılabilirliği için şablon. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const Q& | Karşılaştırılacak ilk değer. |
| y | const Q& | Karşılaştırılacak ikinci değer. |

### Dönüş Değeri

Doğru ise **x**, **y**'den daha küçük kabul edilir, aksi takdirde yanlış.

## ComparerAdapter::operator()(const Q&, const Q&) const metod

[Comparison](../../../system/comparison/) fonksiyonu, < operatörü mevcut olmayan tipler için.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Q | Karşılaştırılan tip; tip dönüşümü kullanılabilirliği için şablon. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const Q& | Karşılaştırılacak ilk değer. |
| y | const Q& | Karşılaştırılacak ikinci değer. |

### Dönüş Değeri

Doğru ise karşılaştırıcı ayarlanmış ve **x**, **y**'den daha küçük kabul edilir, aksi takdirde yanlış.

## İlgili

* Struct [ComparerAdapter](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)