---
title: ComparerType< SharedPtr< T > >
second_title: Αναφορά API Aspose.Slides για C++
description: Συγκρίνει στοιχεία χρησιμοποιώντας τη σημασιολογία 'less'.
type: docs
weight: 157
url: /el/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct

Συγκρίνει στοιχεία χρησιμοποιώντας τη σημασιολογία 'less'.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος των στοιχείων που συγκρίνονται. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Συγκρίνει τύπους δείκτη που υλοποιούν τη διεπαφή [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Συγκρίνει τύπους δείκτη που δεν υλοποιούν τη διεπαφή [IComparable](../../system/icomparable/). |

## Δείτε επίσης

* Χώρος ονομάτων [System::Collections::Generic::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)