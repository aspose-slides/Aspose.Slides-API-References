---
title: set_ColumnGap()
second_title: Αναφορά API του Aspose.Slides για C++ 
description: "Η τιμή του οριζόντιου διαστήματος μεταξύ των στηλών ενός πίνακα; Εάν το ColumnGapRule είναι ορισμένο σε 3 (\"Exactly\"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου) Εάν το ColumnGapRule είναι ορισμένο σε 4 (\"Multiple\"), τότε η μονάδα ερμηνεύεται ως αριθμός 0.5 em αυξήσεων. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0"
type: docs
weight: 144
url: /el/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) μέθοδος

Η τιμή του οριζόντιου διαστήματος μεταξύ των στηλών ενός πίνακα· Αν το ColumnGapRule είναι ορισμένο σε 3 (\"Exactly\"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου) Αν το ColumnGapRule είναι ορισμένο σε 4 (\"Multiple\"), τότε η μονάδα ερμηνεύεται ως αριθμός 0.5 em αυξήσεων. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
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