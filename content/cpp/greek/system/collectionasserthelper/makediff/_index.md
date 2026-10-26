---
title: MakeDiff()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Υπολογίζει το 'diff' μεταξύ δύο συλλογών. Για κάθε στοιχείο κάθε συλλογής ως κλειδί, η προκύπτουσα τιμή θα είναι θετική εάν το στοιχείο εμφανίζεται περισσότερες φορές στη \"expected\" συλλογή, αρνητική εάν εμφανίζεται περισσότερες φορές στη \"actual\" συλλογή, και μηδέν εάν εμφανίζεται ίσες φορές σε κάθε συλλογή.
type: docs
weight: 1
url: /el/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) μέθοδος


Υπολογίζει το «diff» μεταξύ δύο συλλογών. Για κάθε στοιχείο κάθε συλλογής ως κλειδί, η προκύπτουσα τιμή θα είναι θετική εάν το στοιχείο εμφανίζεται περισσότερες φορές στη συλλογή «expected», αρνητική εάν εμφανίζεται περισσότερες φορές στη συλλογή «actual», και μηδέν εάν εμφανίζεται ίσες φορές σε κάθε συλλογή.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T1 | Τύπος στοιχείου της αναμενόμενης συλλογής. |
| T2 | Τύπος στοιχείου της πραγματικής συλλογής. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Αναμενόμενη συλλογή. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Πραγματική συλλογή. |

### Τιμή Επιστροφής

Χάρτης των αποτελεσμάτων σύγκρισης ανά τιμή σύμφωνα με τους παραπάνω κανόνες.

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Class [Dictionary](../../../system.collections.generic/dictionary/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)