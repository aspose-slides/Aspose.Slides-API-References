---
title: get_RowGap()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Η τιμή του κάθετου διαστήματος μεταξύ των γραμμών ενός πίνακα· Αν το RowGapRule οριστεί στην τιμή 3 (\"Exactly\"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου) Αν το RowGapRule οριστεί στην τιμή 4 (\"Multiple\"), τότε η μονάδα ερμηνεύεται ως μισές γραμμές. Προεπιλογή: 0"
type: docs
weight: 183
url: /el/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() μέθοδος

Η τιμή του κάθετου διαστήματος μεταξύ των γραμμών ενός πίνακα· Αν το RowGapRule οριστεί στην τιμή 3 ("Exactly"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου) Αν το RowGapRule οριστεί στην τιμή 4 ("Multiple"), τότε η μονάδα ερμηνεύεται ως μισές γραμμές. Προεπιλογή: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Δείτε επίσης

* Κλάση [MathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)