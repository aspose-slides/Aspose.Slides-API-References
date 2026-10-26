---
title: operator()()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergelijkt pointertypen die IComparable interface implementeren.
type: docs
weight: 1
url: /nl/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const methode

Vergelijkt pointertypen die [IComparable](../../../system/icomparable/) interface implementeren.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Q | Type om te vergelijken. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | LHS-waarde. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | RHS-waarde. |

### Retourwaarde

True als **a** als kleiner dan **b** wordt beschouwd, false anders.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const methode

Vergelijkt pointertypen die [IComparable](../../../system/icomparable/) interface niet implementeren.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Q | Type om te vergelijken. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | LHS-waarde. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | RHS-waarde. |

### Retourwaarde

True als **a** als kleiner dan **b** wordt beschouwd, false anders.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struct [ComparerType< SharedPtr< T > >](../)
* Naamruimte [System::Collections::Generic::Details](../../)
* Bibliotheek [Aspose.Slides](../../../)