---
title: CollectionAssertHelper
second_title: Aspose.Slides για C++ API Αναφορά
description: Heler API για λειτουργίες σχετικές με συλλογές.
type: docs
weight: 1522
url: /el/system/collectionasserthelper/
---
## CollectionAssertHelper struct


Heler API για λειτουργίες σχετικές με συλλογές.

```cpp
class CollectionAssertHelper
```

## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Ελέγχει ότι όλα τα στοιχεία της συλλογής ικανοποιούν την προϋπόθεση. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Ελέγχει ότι οποιοδήποτε στοιχείο της συλλογής ικανοποιεί την προϋπόθεση. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Σειριοποιεί δύο συλλογές για αναπαράσταση μηνύματος. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | Μετατρέπει τη συλλογή σε συμβολοσειρά ενώνοντας τις αναπαραστάσεις συμβολοσειρών των στοιχείων. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Υπολογίζει το 'diff' μεταξύ δύο συλλογών. Για κάθε στοιχείο κάθε συλλογής ως κλειδί, η προκύπτουσα τιμή θα είναι θετική αν το στοιχείο εμφανίζεται περισσότερες φορές στη συλλογή "expected", αρνητική αν εμφανίζεται περισσότερες φορές στη συλλογή "actual", και μηδέν αν εμφανίζεται ίσες φορές σε κάθε συλλογή. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | Διαμορφώνει τη συμβολοσειρά για χρήση ως κείμενο μηνύματος. |
## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)