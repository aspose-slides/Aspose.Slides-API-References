---
title: ComparerType< SharedPtr< T > >
second_title: Aspose.Slides dla C++ – odniesienie API
description: Porównuje elementy używając semantyki 'less'.
type: docs
weight: 157
url: /pl/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct

Porównuje elementy używając semantyki 'less'.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ porównywanych elementów. |
## Metody

| Metoda | Opis |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Porównuje typy wskaźników implementujące interfejs [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Porównuje typy wskaźników nieimplementujące interfejs [IComparable](../../system/icomparable/). |

## Zobacz także

* Przestrzeń nazw [System::Collections::Generic::Details](../)
* Biblioteka [Aspose.Slides](../../)