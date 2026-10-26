---
title: get_Superscript()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει ένα όρισμα υπερ-δείκτη που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, ορίζει το άνω όριο
type: docs
weight: 27
url: /el/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() μέθοδος

Καθορίζει ένα υπερ-δείκτη όρισμα που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, θέτει το ανώτερο όριο

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
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
* Κλάση [IMathNaryOperator](../)
* Ονομαχώρος [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)