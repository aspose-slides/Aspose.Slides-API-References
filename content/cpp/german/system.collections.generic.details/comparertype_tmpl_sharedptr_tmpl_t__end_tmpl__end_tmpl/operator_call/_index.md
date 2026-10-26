---
title: operator()()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht Zeigertypen, die das IComparable-Interface implementieren.
type: docs
weight: 1
url: /de/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const Methode

Vergleicht Zeigertypen, die das [IComparable](../../../system/icomparable/)-Interface implementieren.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Q | Typ zum Vergleichen. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | LHS-Wert. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | RHS-Wert. |

### Rückgabewert

Wahr, wenn **a** als kleiner als **b** betrachtet wird, sonst falsch.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const Methode

Vergleicht Zeigertypen, die das [IComparable](../../../system/icomparable/)-Interface nicht implementieren.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Q | Typ zum Vergleichen. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | LHS-Wert. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | RHS-Wert. |

### Rückgabewert

Wahr, wenn **a** als kleiner als **b** betrachtet wird, sonst falsch.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struct [ComparerType< SharedPtr< T > >](../)
* Namensraum [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)