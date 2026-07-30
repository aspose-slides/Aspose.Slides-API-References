---
title: ComparerType< SharedPtr< T > >
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává prvky pomocí semantiky 'less'.
type: docs
weight: 157
url: /cs/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct

Porovnává prvky pomocí semantiky 'less'.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ porovnávaných prvků. |
## Metody

| Metoda | Popis |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Porovnává typy ukazatelů implementující rozhraní [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Porovnává typy ukazatelů neimplementující rozhraní [IComparable](../../system/icomparable/). |

## Viz také

* Jmenný prostor [System::Collections::Generic::Details](../)
* Knihovna [Aspose.Slides](../../)