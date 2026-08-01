---
title: ComparerType< SharedPtr< T > >
second_title: Aspose.Slides voor C++ API-referentie
description: Vergelijkt elementen met behulp van 'less'-semantiek.
type: docs
weight: 157
url: /nl/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct

Vergelijkt elementen met behulp van 'less'-semantiek.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van de te vergelijken elementen. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Vergelijkt pointertypen die de [IComparable](../../system/icomparable/) interface implementeren. |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Vergelijkt pointertypen die de [IComparable](../../system/icomparable/) interface niet implementeren. |

## Zie ook

* Naamruimte [System::Collections::Generic::Details](../)
* Bibliotheek [Aspose.Slides](../../)