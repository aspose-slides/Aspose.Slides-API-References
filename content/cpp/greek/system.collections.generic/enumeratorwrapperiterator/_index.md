---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides για C++ API Αναφορά
description: Επανάληψη που περιβάλλει τον προ-δημιουργημένο αμετρητή και ανακατευθύνει όλες τις κλήσεις σε αυτόν.
type: docs
weight: 196
url: /el/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator κλάση

Επανάληψη που περιβάλλει τον προ-δημιουργημένο αμετρητή και ανακατευθύνει όλες τις κλήσεις σε αυτόν.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Element | Τύπος στοιχείου. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Κλωνοποιεί τον τρέχοντα επαναλήπτη. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | Μετακινεί τον επαναλήπτη ένα βήμα προς τα εμπρός. Πρέπει να ενημερώσει τα m_is_end και m_pointer. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Ελέγχει αν δύο επαναλήπτες δείχνουν στο ίδιο στοιχείο. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Καταστροφέας. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)