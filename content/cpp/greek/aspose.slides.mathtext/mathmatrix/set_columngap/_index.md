---
title: set_ColumnGap()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Η τιμή της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Εάν το ColumnGapRule οριστεί σε 3 (\"Ακριβώς\"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου) Εάν το ColumnGapRule οριστεί σε 4 (\"Πολλαπλό\"), τότε η μονάδα ερμηνεύεται ως αριθμός αυξήσεων 0.5 em. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0"
type: docs
weight: 144
url: /el/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) method


Η τιμή της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Εάν το ColumnGapRule οριστεί σε 3 (\"Ακριβώς\"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου) Εάν το ColumnGapRule οριστεί σε 4 (\"Πολλαπλό\"), τότε η μονάδα ερμηνεύεται ως αριθμός αυξήσεων 0,5 em. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
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