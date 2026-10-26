---
title: operator()()
second_title: Aspose.Slides για C++ Αναφορά API
description: Συγκρίνει τύπους δεικτών που υλοποιούν τη διεπαφή IComparable.
type: docs
weight: 1
url: /el/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

Συγκρίνει τύπους δεικτών που υλοποιούν τη διεπαφή [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Q | Type to compare. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | LHS value. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | RHS value. |

### Τιμή Επιστροφής

Αληθές εάν το **a** θεωρείται μικρότερο από το **b**, ψευδές διαφορετικά.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

Συγκρίνει τύπους δεικτών που δεν υλοποιούν τη διεπαφή [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Q | Type to compare. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | LHS value. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | RHS value. |

### Τιμή Επιστροφής

Αληθές εάν το **a** θεωρείται μικρότερο από το **b**, ψευδές διαφορετικά.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struct [ComparerType< SharedPtr< T > >](../)
* Namespace [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)