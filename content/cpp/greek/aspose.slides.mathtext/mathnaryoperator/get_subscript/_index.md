---
title: get_Subscript()
second_title: Aspose.Slides για την τεκμηρίωση API C++
description: Προσδιορίζει ένα επιχείρημα υποδείκτη που, για παράδειγμα, στην περίπτωση ενός ακέραιου, θέτει το κατώτερο όριο
type: docs
weight: 14
url: /el/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() μέθοδος


Προσδιορίζει ένα επιχείρημα υποδείκτη που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, θέτει το κατώτερο όριο

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)