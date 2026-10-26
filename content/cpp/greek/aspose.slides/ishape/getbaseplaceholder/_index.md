---
title: GetBasePlaceholder()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει ένα βασικό σχήμα κράτησης θέσης (σχήμα από τη διάταξη και/ή τη κύρια διαφάνεια από την οποία κληρονομείται το τρέχον σχήμα).
type: docs
weight: 573
url: /el/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() method

Επιστρέφει ένα βασικό σχήμα κράτησης θέσης (σχήμα από τη διάταξη και/ή τη κύρια διαφάνεια από την οποία κληρονομείται το τρέχον σχήμα).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## Παρατηρήσεις

Επιστρέφεται null εάν το τρέχον σχήμα δεν κληρονομείται.

```cpp
// Λήψη όλων των (master/layout/slide) κινούμενων εφέ του σχήματος κράτησης θέσης
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IShape](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)