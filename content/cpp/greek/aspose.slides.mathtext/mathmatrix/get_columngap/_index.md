---
title: get_ColumnGap()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Η τιμή της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα; Αν το ColumnGapRule έχει οριστεί σε 3 (\"Exactly\"), τότε η μονάδα ερμηνεύεται ως twips (1/20ο ενός σημείου) Αν το ColumnGapRule έχει οριστεί σε 4 (\"Multiple\"), τότε η μονάδα ερμηνεύεται ως αριθμός 0.5 em βημάτων. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0"
type: docs
weight: 131
url: /el/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() μέθοδος

Η τιμή της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Αν το ColumnGapRule έχει οριστεί σε 3 ("Exactly"), τότε η μονάδα ερμηνεύεται ως twips (1/20ο ενός σημείου). Αν το ColumnGapRule έχει οριστεί σε 4 ("Multiple"), τότε η μονάδα ερμηνεύεται ως αριθμός 0.5 em βήματα. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Δείτε επίσης

* Κλάση [MathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)