---
title: get_Superscript()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει ένα όρισμα υπερδείκτη που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, ορίζει το άνω όριο
type: docs
weight: 27
url: /el/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() μέθοδος


Καθορίζει ένα υπερδείκτη όρισμα που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, ορίζει το άνω όριο

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathNaryOperator](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)