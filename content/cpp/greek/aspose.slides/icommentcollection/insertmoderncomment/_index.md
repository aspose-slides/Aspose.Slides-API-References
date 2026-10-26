---
title: InsertModernComment()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εισάγετε νέο σύγχρονο σχόλιο σε μια συλλογή στον καθορισμένο δείκτη.
type: docs
weight: 53
url: /el/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) μέθοδος


Εισάγετε νέο σύγχρονο σχόλιο σε μια συλλογή στον καθορισμένο δείκτη.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Δείκτης του στοιχείου σε μια συλλογή στον οποίο πρέπει να εισαχθεί το σύγχρονο σχόλιο. |
| text | [System::String](../../../system/string/) | Απλό κείμενο ενός νέου σύγχρονου σχολίου. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) σε μια παρουσίαση όπου θα προστεθεί ένα νέο σύγχρονο σχόλιο. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) σε μια διαφάνεια στην οποία συσχετίζεται ένα νέο σύγχρονο σχόλιο. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο σύγχρονο σχόλιο. |
| creationTime | [System::DateTime](../../../system/datetime/) | Ώρα δημιουργίας ενός σύγχρονου σχολίου. |

### Τιμή επιστροφής

Το εισαχθέν σύγχρονο σχόλιο.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IModernComment](../../imoderncomment/)
* Κλάση [String](../../../system/string/)
* Κλάση [ISlide](../../islide/)
* Κλάση [IShape](../../ishape/)
* Κλάση [PointF](../../../system.drawing/pointf/)
* Κλάση [DateTime](../../../system/datetime/)
* Κλάση [ICommentCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)