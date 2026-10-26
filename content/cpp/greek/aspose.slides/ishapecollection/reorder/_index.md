---
title: Reorder()
second_title: Αναφορά API του Aspose.Slides για C++
description: Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων.
type: docs
weight: 300
url: /el/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) μέθοδος

Μετακινεί το συγκεκριμένο σχήμα σε νέα θέση μέσα στη συλλογή σχημάτων.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης στόχος μηδενικής βάσης όπου θα τοποθετηθεί το σχήμα. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Το [IShape](../../ishape/) που θα μετακινηθεί μέσα στη συλλογή. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) μέθοδος

Μετακινεί τα συγκεκριμένα σχήματα μέσα στη συλλογή σχημάτων, τοποθετώντας τα ξεκινώντας από τον δεδομένο δείκτη.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης στόχος μηδενικής βάσης όπου θα τοποθετηθεί το πρώτο συγκεκριμένο σχήμα· τα επόμενα σχήματα ακολουθούν με τη σειρά που παρέχονται. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Μία ή περισσότερες εμφανίσεις του [IShape](../../ishape/) για μετακίνηση μέσα στη συλλογή. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [IShape](../../ishape/)
* Κλάση [IShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)