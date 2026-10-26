---
title: get_ColumnGap()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Η τιμή της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Αν το ColumnGapRule οριστεί σε 3 (\"Exactly\"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου) Αν το ColumnGapRule οριστεί σε 4 (\"Multiple\"), τότε η μονάδα ερμηνεύεται ως αριθμός αυξήσεων 0.5 em. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0"
type: docs
weight: 131
url: /el/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() μέθοδος

Η τιμή της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Αν το ColumnGapRule είναι ορισμένο σε 3 ("Exactly"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου) Αν το ColumnGapRule είναι ορισμένο σε 4 ("Multiple"), τότε η μονάδα ερμηνεύεται ως αριθμός των αυξήσεων 0.5 em. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Δείτε επίσης

* Κλάση [IMathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)