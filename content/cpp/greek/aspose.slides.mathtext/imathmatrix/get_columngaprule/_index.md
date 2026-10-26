---
title: get_ColumnGapRule()
second_title: Αναφορά API του Aspose.Slides για C++
description: "Ο τύπος της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Οι μονάδες οριζόντιας απόστασης μπορούν να είναι ems ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0)"
type: docs
weight: 105
url: /el/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() μέθοδος


Ο τύπος της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Οι μονάδες οριζόντιας απόστασης μπορούν να είναι ems ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Δείτε επίσης

* Απαρίθμηση [MathSpacingRules](../../mathspacingrules/)
* Κλάση [IMathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)