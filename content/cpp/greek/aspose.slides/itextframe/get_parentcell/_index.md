---
title: get_ParentCell()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει το γονικό κελί ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή ICell. Μόνο για ανάγνωση ICell.
type: docs
weight: 79
url: /el/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() μέθοδος


Επιστρέφει το γονικό κελί ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή [ICell](../../icell/). Μόνο για ανάγνωση [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## Παρατηρήσεις


Το παρακάτω δείγμα κώδικα εμφανίζει 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ICell](../../icell/)
* Κλάση [ITextFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)