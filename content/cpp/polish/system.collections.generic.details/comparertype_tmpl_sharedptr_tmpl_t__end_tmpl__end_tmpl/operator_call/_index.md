---
title: operator()()
second_title: Referencja API Aspose.Slides dla C++
description: Porównuje typy wskaźników implementujące interfejs IComparable.
type: docs
weight: 1
url: /pl/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

Porównuje typy wskaźników implementujące interfejs [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Q | Typ do porównania. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Wartość lewej strony. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Wartość prawej strony. |

### Wartość zwracana

Prawda, jeśli **a** jest uznawane za mniejsze niż **b**, w przeciwnym razie fałsz.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

Porównuje typy wskaźników nieimplementujące interfejsu [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Q | Typ do porównania. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Wartość lewej strony. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Wartość prawej strony. |

### Wartość zwracana

Prawda, jeśli **a** jest uznawane za mniejsze niż **b**, w przeciwnym razie fałsz.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IComparable](../../../system/icomparable/)
* Struktura [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struktura [ComparerType< SharedPtr< T > >](../)
* Przestrzeń nazw [System::Collections::Generic::Details](../../)
* Biblioteka [Aspose.Slides](../../../)