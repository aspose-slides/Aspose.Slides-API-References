---
title: CollectionsToMsg()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Σειριοποιεί δύο συλλογές για αναπαράσταση μηνύματος.
type: docs
weight: 53
url: /el/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) μέθοδος

Σειριοποιεί δύο συλλογές για αναπαράσταση μηνύματος.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Αναμενόμενος τύπος στοιχείου συλλογής. |
| T2 | Πραγματικός τύπος στοιχείου συλλογής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | Μια προσαρμοσμένη συμβολοσειρά που εισάγεται πριν την αναμενόμενη τιμή στο τελικό μήνυμα |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Αναμενόμενη συλλογή. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Πραγματική συλλογή. |

### Τιμή Επιστροφής

Φιλικό προς το χρήστη μήνυμα για το περιεχόμενο των συλλογών.

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [IEnumerable](../../../system.collections.generic/ienumerable/)
* Δομή [CollectionAssertHelper](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)