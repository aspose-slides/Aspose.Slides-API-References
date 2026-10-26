---
title: set_RowGap()
second_title: Αναφορά API Aspose.Slides για C++
description: "Η τιμή του κάθετου διαστήματος μεταξύ γραμμών ενός πίνακα· Αν το RowGapRule οριστεί σε 3 (\"Exactly\"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου) Αν το RowGapRule οριστεί σε 4 (\"Multiple\"), τότε η μονάδα ερμηνεύεται ως ημιγραμμές. Προεπιλογή: 0"
type: docs
weight: 196
url: /el/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) μέθοδος

Η τιμή του κάθετου διαστήματος μεταξύ γραμμών ενός πίνακα· Αν το RowGapRule οριστεί σε 3 ("Exactly"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου) Αν το RowGapRule οριστεί σε 4 ("Multiple"), τότε η μονάδα ερμηνεύεται ως ημιγραμμές. Προεπιλογή: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
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