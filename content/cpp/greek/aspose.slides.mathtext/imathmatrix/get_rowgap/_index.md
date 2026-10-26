---
title: get_RowGap()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Η τιμή της κατακόρυφης απόστασης μεταξύ των γραμμών ενός πίνακα; Αν το RowGapRule είναι ορισμένο σε 3 (\"Exactly\"), τότε η μονάδα ερμηνεύεται ως twips (1/20 ενός σημείου) Αν το RowGapRule είναι ορισμένο σε 4 (\"Multiple\"), τότε η μονάδα ερμηνεύεται ως μισές γραμμές. Προεπιλογή: 0"
type: docs
weight: 183
url: /el/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() μέθοδος

Η τιμή της κατακόρυφης απόστασης μεταξύ των γραμμών ενός πίνακα· Αν το RowGapRule είναι ορισμένο σε 3 ("Exactly"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου) Αν το RowGapRule είναι ορισμένο σε 4 ("Multiple"), τότε η μονάδα ερμηνεύεται ως μισές γραμμές. Προεπιλογή: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Δείτε επίσης

* Κλάση [IMathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)