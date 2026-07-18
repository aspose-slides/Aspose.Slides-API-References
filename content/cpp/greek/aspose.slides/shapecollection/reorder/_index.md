---
title: Reorder()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετακινεί το καθορισμένο σχήμα σε νέα θέση μέσα στη συλλογή σχημάτων.
type: docs
weight: 339
url: /el/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) μέθοδος

Μετακινεί το καθορισμένο σχήμα σε νέα θέση μέσα στη συλλογή σχημάτων.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης-στόχος μηδενικής βάσης όπου θα τοποθετηθεί το σχήμα. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Το [IShape](../../ishape/) που θα μετακινηθεί στη συλλογή. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) μέθοδος

Μετακινεί τα καθορισμένα σχήματα μέσα στη συλλογή σχημάτων, τοποθετώντας τα αρχίζοντας από τον δοσμένο δείκτη.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης-στόχος μηδενικής βάσης όπου θα τοποθετηθεί το πρώτο καθορισμένο σχήμα· τα επόμενα σχήματα ακολουθούν με τη σειρά που δόθηκαν. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Ένα ή περισσότερα [IShape](../../ishape/) στιγμιότυπα προς μετακίνηση στη συλλογή. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [IShape](../../ishape/)
* Κλάση [ShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)