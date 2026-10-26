---
title: set_RowGapRule()
second_title: Aspose.Slides για την αναφορά API C++
description: "Ο τύπος κάθετης απόστασης μεταξύ των γραμμών ενός πίνακα· Οι μονάδες κάθετης απόστασης μπορούν να είναι γραμμές ή σημεία (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0)"
type: docs
weight: 170
url: /el/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) μέθοδος

Ο τύπος κάθετης απόστασης μεταξύ των γραμμών ενός πίνακα· Οι μονάδες κάθετης απόστασης μπορεί να είναι γραμμές ή σημεία (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Δείτε επίσης

* Enum [MathSpacingRules](../../mathspacingrules/)
* Κλάση [IMathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)