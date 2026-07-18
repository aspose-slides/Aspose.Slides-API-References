---
title: CheckDiffForAny()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ελέγχει ότι οποιοδήποτε στοιχείο της συλλογής τηρεί την προδιαγραφή.
type: docs
weight: 27
url: /el/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) μέθοδος

Ελέγχει ότι οποιοδήποτε στοιχείο της συλλογής πληροί την προδιαγραφή.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Προδιαγραφή για έλεγχο. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Τιμές για έλεγχο. |

### Τιμή επιστροφής

True αν η δοκιμή είναι επιτυχής για κάποιο στοιχείο, false αν όλα περάσουν.

## Δείτε επίσης

* typedef [SharedPtr](../../sharedptr/)
* Κλάση [ICollection](../../../system.collections.generic/icollection/)
* Δομή [CollectionAssertHelper](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)