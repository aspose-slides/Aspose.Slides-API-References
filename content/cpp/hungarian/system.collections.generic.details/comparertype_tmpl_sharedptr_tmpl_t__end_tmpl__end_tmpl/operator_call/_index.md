---
title: operator()()
second_title: Aspose.Slides C++ API referencia
description: Összehasonlítja a pointer típusokat, amelyek implementálják az IComparable interfészt.
type: docs
weight: 1
url: /hu/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const metódus


Összehasonlítja a pointer típusokat, amelyek implementálják a [IComparable](../../../system/icomparable/) interfészt.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Q | Összehasonlítandó típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Bal oldal értéke. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Jobb oldal értéke. |

### Visszatérési érték

Igaz, ha **a**-t kisebbnek tekintik, mint **b**, különben hamis.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const metódus


Összehasonlítja a pointer típusokat, amelyek nem implementálják a [IComparable](../../../system/icomparable/) interfészt.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Q | Összehasonlítandó típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Bal oldal értéke. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Jobb oldal értéke. |

### Visszatérési érték

Igaz, ha **a**-t kisebbnek tekintik, mint **b**, különben hamis.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IComparable](../../../system/icomparable/)
* Struktúra [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struktúra [ComparerType< SharedPtr< T > >](../)
* Névtér [System::Collections::Generic::Details](../../)
* Könyvtár [Aspose.Slides](../../../)