---
title: get_ParentShape()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει το γονικό σχήμα ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή IShape Μόνο ανάγνωση IShape.
type: docs
weight: 66
url: /el/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() μέθοδος

Επιστρέφει το γονικό σχήμα ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή [IShape](../../ishape/) Μόνο ανάγνωση [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## Σημειώσεις

Το ακόλουθο παράδειγμα κώδικα δείχνει 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IShape](../../ishape/)
* Κλάση [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)