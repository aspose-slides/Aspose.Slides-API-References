---
title: CheckDiffForAll()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ελέγχει ότι όλα τα στοιχεία της συλλογής τηρούν τη συνθήκη.
type: docs
weight: 14
url: /el/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) μέθοδος


Ελέγχει ότι όλα τα στοιχεία της συλλογής τηρούν την πρόταση.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Η συνθήκη προς έλεγχο. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Τιμές προς έλεγχο. |

### Τιμή Επιστροφής

Ψευδής αν ο έλεγχος αποτύχει για κάποιο στοιχείο, αληθής αν όλα περάσουν.

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [ICollection](../../../system.collections.generic/icollection/)
* Δομή [CollectionAssertHelper](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)