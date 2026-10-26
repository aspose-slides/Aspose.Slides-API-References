---
title: KeyIterator
second_title: Aspose.Slides για C++ Αναφορά API
description: Iterator λεξικού που παρέχει πρόσβαση σε κλειδιά.
type: docs
weight: 365
url: /el/system.collections.generic/keyiterator/
---
## KeyIterator κλάση


[Dictionary](../dictionary/) iterator που παρέχει πρόσβαση κλειδιού.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| Dict | [Dictionary](../dictionary/) κλάση. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | Δημιουργεί αντίγραφο του τρέχοντος iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Μετακινεί τον iterator ένα βήμα προς τα πίσω. |
| void [IncrementIterator](./incrementiterator/)() override | Μετακινεί τον iterator ένα βήμα προς τα εμπρός. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Κατασκευαστής. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Κατασκευαστής. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | Κατασκευαστής μετακίνησης. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Μετακινεί τον iterator κατά τον καθορισμένο αριθμό βημάτων. |
| virtual  [~KeyIterator](./~keyiterator/)() | Καταστροφέας. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)