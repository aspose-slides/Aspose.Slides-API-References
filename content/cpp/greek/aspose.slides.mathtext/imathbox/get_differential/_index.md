---
title: get_Differential()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Διαφορικό. Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ., \\uD835\\uDC51\\uD835\\uDC65 σε ένα ολοκληρωτέο), και λαμβάνει την κατάλληλη οριζόντια απόσταση για το μαθηματικό διαφορικό. Προεπιλογή: false"
type: docs
weight: 66
url: /el/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() μέθοδος


Διαφορικό. Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ., \\uD835\\uDC51\\uD835\\uDC65 σε ένα ολοκληρωτέο), και λαμβάνει την κατάλληλη οριζόντια απόσταση για το μαθηματικό διαφορικό. Προεπιλογή: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
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