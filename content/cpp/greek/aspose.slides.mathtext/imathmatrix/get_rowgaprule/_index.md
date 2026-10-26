---
title: get_RowGapRule()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Ο τύπος κάθετης απόστασης μεταξύ γραμμών ενός πίνακα· Οι μονάδες κάθετης απόστασης μπορούν να είναι γραμμές ή σημεία (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0)"
type: docs
weight: 157
url: /el/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() μέθοδος

Ο τύπος κάθετης απόστασης μεταξύ γραμμών ενός πίνακα· Οι μονάδες κάθετης απόστασης μπορούν να είναι γραμμές ή σημεία (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Δείτε επίσης

* Απαρίθμηση [MathSpacingRules](../../mathspacingrules/)
* Κλάση [IMathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)