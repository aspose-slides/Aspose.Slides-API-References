---
title: InsertComment()
second_title: Αναφορά API του Aspose.Slides για C++
description: Εισάγετε νέο σχόλιο σε μια συλλογή στον καθορισμένο δείκτη.
type: docs
weight: 40
url: /el/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) μέθοδος


Εισαγάγετε νέο σχόλιο σε μια συλλογή στον καθορισμένο δείκτη.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Index of the element in a collection at which comment should be inserted. |
| text | [System::String](../../../system/string/) | Plain text of a new comment. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) in a presentation where to add a new comment. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position on a slide where to add a new comment. |
| creationTime | [System::DateTime](../../../system/datetime/) | Time of a comment creation. |

### Τιμή επιστροφής

Το εισαχθέν σχόλιο.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IComment](../../icomment/)
* Κλάση [String](../../../system/string/)
* Κλάση [ISlide](../../islide/)
* Κλάση [PointF](../../../system.drawing/pointf/)
* Κλάση [DateTime](../../../system/datetime/)
* Κλάση [ICommentCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)