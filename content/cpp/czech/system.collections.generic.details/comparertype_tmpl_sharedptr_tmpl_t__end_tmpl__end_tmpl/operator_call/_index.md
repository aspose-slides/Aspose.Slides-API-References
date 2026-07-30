---
title: operator()()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Porovnává typy ukazatelů implementující rozhraní IComparable.
type: docs
weight: 1
url: /cs/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

Porovnává typy ukazatelů implementující rozhraní [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Parametry šablony

| Parameter | Description |
| --- | --- |
| Q | Typ k porovnání. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Hodnota levého operandu. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Hodnota pravého operandu. |

### Návratová hodnota

Vrací true, pokud je **a** považováno za menší než **b**, jinak false.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

Porovnává typy ukazatelů neimplementující rozhraní [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Parametry šablony

| Parameter | Description |
| --- | --- |
| Q | Typ k porovnání. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Hodnota levého operandu. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Hodnota pravého operandu. |

### Návratová hodnota

Vrací true, pokud je **a** považováno za menší než **b**, jinak false.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IComparable](../../../system/icomparable/)
* Struktura [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struktura [ComparerType< SharedPtr< T > >](../)
* Jmenný prostor [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)