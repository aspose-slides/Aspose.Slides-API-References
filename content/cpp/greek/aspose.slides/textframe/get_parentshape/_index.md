---
title: get_ParentShape()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει το γονικό σχήμα ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διασύνδεση IShape Μόνο για ανάγνωση IShape.
type: docs
weight: 92
url: /el/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() μέθοδος


Επιστρέφει το γονικό σχήμα ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διασύνδεση [IShape](../../ishape/) Μόνο για ανάγνωση [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## Παρατηρήσεις


Το παρακάτω δείγμα κώδικα εμφανίζει 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IShape](../../ishape/)
* Κλάση [TextFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)