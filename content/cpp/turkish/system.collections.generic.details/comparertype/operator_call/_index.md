---
title: operator()()
second_title: Aspose.Slides for C++ API Referansı
description: IComparable arayüzünü uygulayan değer tiplerini karşılaştırır.
type: docs
weight: 1
url: /tr/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const metot


[IComparable](../../../system/icomparable/) arayüzünü uygulayan değer tiplerini karşılaştırır.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| Q | Type to compare. |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| a | const Q\& | LHS value. |
| b | const Q\& | RHS value. |

### Dönüş Değeri

True if **a** is considered less than **b**, false otherwise.

## ComparerType::operator()(const Q\&, const Q\&) const metot


[IComparable](../../../system/icomparable/) arayüzünü uygulamayan ilkel değer tiplerini ve nesneleri karşılaştırır.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| Q | Type to compare. |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| a | const Q\& | LHS value. |
| b | const Q\& | RHS value. |

### Dönüş Değeri

True if **a** is considered less than **b**, false otherwise.

## ComparerType::operator()(const Q\&, const Q\&) const metot


Kayan nokta tiplerini karşılaştırır.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| Q | Type to compare. |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| a | const Q\& | LHS value. |
| b | const Q\& | RHS value. |

### Dönüş Değeri

True if **a** is considered less than **b**, false otherwise.

## Ayrıca Bakınız

* Sınıf [IComparable](../../../system/icomparable/)
* Yapı [has_method_compareto](../../has_method_compareto/)
* Yapı [ComparerType](../)
* Ad Alanı [System::Collections::Generic::Details](../../)
* Kütüphane [Aspose.Slides](../../../)