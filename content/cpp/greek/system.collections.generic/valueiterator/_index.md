---
title: ValueIterator
second_title: Αναφορά API Aspose.Slides για C++
description: Επαναλήπτης λεξικού που παρέχει πρόσβαση σε τιμές.
type: docs
weight: 625
url: /el/system.collections.generic/valueiterator/
---
## ValueIterator κλάση

[Dictionary](../dictionary/) επαναλήπτης που παρέχει πρόσβαση σε τιμές.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Dict | [Dictionary](../dictionary/) κλάση. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | Δημιουργεί αντίγραφο του τρέχοντος επαναλήπτη. |
| void [DecrementIterator](./decrementiterator/)() override | Μετακινεί τον επαναλήπτη ένα βήμα προς τα πίσω. |
| void [IncrementIterator](./incrementiterator/)() override | Μετακινεί τον επαναλήπτη ένα βήμα προς τα εμπρός. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Μετακινεί τον επαναλήπτη κατά τον καθορισμένο αριθμό βημάτων. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Κατασκευαστής. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Κατασκευαστής. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | Κατασκευαστής μεταφοράς. |
| virtual  [~ValueIterator](./~valueiterator/)() | Καταστροφέας. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)