---
title: InsertComment()
second_title: Αναφορά API Aspose.Slides για C++
description: Εισάγει νέο σχόλιο σε μια συλλογή στον καθορισμένο δείκτη.
type: docs
weight: 79
url: /el/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method


Εισάγει νέο σχόλιο σε μια συλλογή στον καθορισμένο δείκτη.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Δείκτης του στοιχείου σε μια συλλογή όπου πρέπει να εισαχθεί το σχόλιο. |
| text | [System::String](../../../system/string/) | Απλό κείμενο νέου σχολίου. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) σε μια παρουσίαση όπου θα προστεθεί ένα νέο σχόλιο. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο σχόλιο. |
| creationTime | [System::DateTime](../../../system/datetime/) | Ώρα δημιουργίας σχολίου. |

### Τιμή Επιστροφής

Inserted comment.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)