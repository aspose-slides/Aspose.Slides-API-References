---
title: set_Differential()
second_title: Αναφορά API Aspose.Slides για C++
description: "Διαφορικό. Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ., \\uD835\\uDC51\\uD835\\uDC65 σε ολοκληρωτέο), και λαμβάνει το κατάλληλο οριζόντιο διάστημα για το μαθηματικό διαφορικό. Προεπιλογή: false"
type: docs
weight: 79
url: /el/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) μέθοδος

Διαφορικό. Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ., \\uD835\\uDC51\\uD835\\uDC65 σε ολοκληρωτέο), και λαμβάνει το κατάλληλο οριζόντιο διάστημα για το μαθηματικό διαφορικό. Προεπιλογή: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Δείτε επίσης

* Κλάση [IMathBox](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)