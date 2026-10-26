---
title: set_Differential()
second_title: Αναφορά API του Aspose.Slides για C++
description: "Διαφορικό Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ., \\uD835\\uDC51\\uD835\\uDC65 σε έναν ολοκληρωτή), και λαμβάνει το κατάλληλο οριζόντιο διάστημα για το μαθηματικό διαφορικό. Προεπιλογή: false"
type: docs
weight: 79
url: /el/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) μέθοδος

Differential Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ., \\uD835\\uDC51\\uD835\\uDC65 σε έναν ολοκληρωτή), και λαμβάνει το κατάλληλο οριζόντιο διάστημα για το μαθηματικό διαφορικό. Προεπιλογή: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
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

* Κλάση [MathBox](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)