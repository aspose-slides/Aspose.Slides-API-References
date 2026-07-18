---
title: DictionaryIterator
second_title: Aspose.Slides για την Αναφορά API του C++
description: Επανάληψη λεξικού που παρέχει τη σημειογραφία KeyValuePair.
type: docs
weight: 157
url: /el/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator κλάση

[Dictionary](../dictionary/) iterator που παρέχει [KeyValuePair](../keyvaluepair/) σημειογραφία.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Dict | [Dictionary](../dictionary/) κλάση. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | Δημιουργεί κλώνο του τρέχοντος iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Μετακινεί τον iterator ένα βήμα πίσω. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Κατασκευαστής. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Κατασκευαστής. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | Κατασκευαστής μεταφοράς. |
| void [IncrementIterator](./incrementiterator/)() override | Μετακινεί τον iterator ένα βήμα μπροστά. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Μετακινεί τον iterator κατά τον καθορισμένο αριθμό βημάτων. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | Καταστροφέας. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)