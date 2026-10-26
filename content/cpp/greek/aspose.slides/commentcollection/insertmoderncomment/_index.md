---
title: InsertModernComment()
second_title: Αναφορά API του Aspose.Slides για C++
description: Εισάγει νέο μοντέρνο σχόλιο σε μια συλλογή στη συγκεκριμένη θέση.
type: docs
weight: 92
url: /el/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method


Εισάγει νέο μοντέρνο σχόλιο σε μια συλλογή στη συγκεκριμένη θέση.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Δείκτης του στοιχείου σε μια συλλογή στην οποία πρέπει να εισαχθεί το μοντέρνο σχόλιο. |
| text | [System::String](../../../system/string/) | Απλό κείμενο ενός νέου μοντέρνου σχολίου. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) σε μια παρουσίαση όπου θα προστεθεί ένα νέο μοντέρνο σχόλιο. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) σε μια διαφάνεια στην οποία συνδέεται ένα νέο μοντέρνο σχόλιο. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο μοντέρνο σχόλιο. |
| creationTime | [System::DateTime](../../../system/datetime/) | Χρόνος δημιουργίας ενός μοντέρνου σχολίου. |

### Τιμή Επιστροφής

Το εισαχθέν μοντέρνο σχόλιο.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IModernComment](../../imoderncomment/)
* Κλάση [String](../../../system/string/)
* Κλάση [ISlide](../../islide/)
* Κλάση [IShape](../../ishape/)
* Κλάση [PointF](../../../system.drawing/pointf/)
* Κλάση [DateTime](../../../system/datetime/)
* Κλάση [CommentCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)