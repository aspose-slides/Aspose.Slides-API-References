---
title: ComparerType< SharedPtr< T > >
second_title: Aspose.Slides för C++ API-referens
description: Jämför element med 'less'-semantik.
type: docs
weight: 157
url: /sv/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct


Jämför element med 'less'-semantik.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av jämförda element. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Jämför pekartyper som implementerar [IComparable](../../system/icomparable/) gränssnittet. |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Jämför pekartyper som inte implementerar [IComparable](../../system/icomparable/) gränssnittet. |

## Se även

* Namnrymd [System::Collections::Generic::Details](../)
* Bibliotek [Aspose.Slides](../../)