---
title: get_Differential()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Διαφορική Όταν είναι true, το κουτί λειτουργεί ως διαφορική (π.χ., \\uD835\\uDC51\\uD835\\uDC65 σε ένα ολοκληρωτέο), και λαμβάνει το κατάλληλο οριζόντιο διάστημα για τη μαθηματική διαφορική. Προεπιλογή: false"
type: docs
weight: 66
url: /el/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() μέθοδος


Differential Όταν είναι true, το κουτί λειτουργεί ως διαφορική (π.χ., \\uD835\\uDC51\\uDC65 σε ένα ολοκληρωτέο), και λαμβάνει το κατάλληλο οριζόντιο διάστημα για τη μαθηματική διαφορική. Προεπιλογή: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
```

## Σχόλια


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