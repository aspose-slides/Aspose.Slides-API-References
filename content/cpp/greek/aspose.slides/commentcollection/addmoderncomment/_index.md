---
title: AddModernComment()
second_title: Aspose.Slides για C++ Αναφορά API
description: Προσθέτει νέο μοντέρνο σχόλιο στο τέλος μιας συλλογής.
type: docs
weight: 66
url: /el/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) μέθοδος

Προσθέστε νέο μοντέρνο σχόλιο στο τέλος μιας συλλογής.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Απλό κείμενο ενός νέου μοντέρνου σχολίου. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) σε μια παρουσίαση όπου θα προστεθεί νέο μοντέρνο σχόλιο. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) σε μια διαφάνεια στην οποία συνδέεται ένα νέο μοντέρνο σχόλιο. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Θέση σε μια διαφάνεια όπου θα προστεθεί νέο μοντέρνο σχόλιο. |
| creationTime | [System::DateTime](../../../system/datetime/) | Χρόνος δημιουργίας ενός μοντέρνου σχολίου. |

### Τιμή επιστροφής

Προστέθηκε μοντέρνο σχόλιο.

## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

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