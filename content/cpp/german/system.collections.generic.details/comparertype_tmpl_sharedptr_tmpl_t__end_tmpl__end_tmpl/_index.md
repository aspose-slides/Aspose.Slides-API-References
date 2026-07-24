---
title: ComparerType< SharedPtr< T > >
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht Elemente mithilfe der 'less'-Semantik.
type: docs
weight: 157
url: /de/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct

Vergleicht Elemente mithilfe der 'less'-Semantik.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ der zu vergleichenden Elemente. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Vergleicht Zeigertypen, die das Interface [IComparable](../../system/icomparable/) implementieren. |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Vergleicht Zeigertypen, die nicht das Interface [IComparable](../../system/icomparable/) implementieren. |

## Siehe auch

* Namensraum [System::Collections::Generic::Details](../)
* Bibliothek [Aspose.Slides](../../)