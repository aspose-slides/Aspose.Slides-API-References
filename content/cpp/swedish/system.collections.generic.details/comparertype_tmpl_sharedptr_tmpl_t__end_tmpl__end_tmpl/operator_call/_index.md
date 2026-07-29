---
title: operator()()
second_title: Aspose.Slides för C++ API-referens
description: Jämför pekartyper som implementerar IComparable-gränssnittet.
type: docs
weight: 1
url: /sv/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const metod

Jämför pekartyper som implementerar [IComparable](../../../system/icomparable/) gränssnitt.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Q | Typ att jämföra. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Värde på vänster sida. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Värde på högra sidan. |

### Returvärde

Sant om **a** anses vara mindre än **b**, falskt annars.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const metod

Jämför pekartyper som inte implementerar [IComparable](../../../system/icomparable/) gränssnitt.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Q | Typ att jämföra. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Värde på vänster sida. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Värde på högra sidan. |

### Returvärde

Sant om **a** anses vara mindre än **b**, falskt annars.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struct [ComparerType< SharedPtr< T > >](../)
* Namnrymd [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)