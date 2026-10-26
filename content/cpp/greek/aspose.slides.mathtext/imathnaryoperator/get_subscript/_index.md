---
title: get_Subscript()
second_title: Aspose.Slides για το C++ API Αναφορά
description: Καθορίζει ένα όρισμα δείκτη που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, ορίζει το κατώτερο όριο
type: docs
weight: 14
url: /el/aspose.slides.mathtext/imathnaryoperator/get_subscript/
---
## IMathNaryOperator::get_Subscript() μέθοδος


Καθορίζει ένα επιχείρημα δεικτοδότησης που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, ορίζει το κατώτερο όριο

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Subscript()=0
```

## Σημειώσεις


Παράδειγμα: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathNaryOperator](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)