---
title: GetSlideComments()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Επιστρέφει όλα τα σχόλια διαφάνειας που προστέθηκαν από συγκεκριμένο συγγραφέα.
type: docs
weight: 209
url: /el/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) μέθοδος

Επιστρέφει όλα τα σχόλια διαφάνειας που προστέθηκαν από συγκεκριμένο συγγραφέα.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Συγγραφέας των σχολίων που θα βρεθούν ή null για να επιστραφούν όλα τα σχόλια. |

### Τιμή Επιστροφής

Πίνακας των [Comment](../../comment/).

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IComment](../../icomment/)
* Κλάση [ICommentAuthor](../../icommentauthor/)
* Κλάση [Slide](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)