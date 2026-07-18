---
title: set_RowGap()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Η τιμή του κατακόρυφου διαστήματος μεταξύ των γραμμών ενός πίνακα· Αν το RowGapRule έχει οριστεί σε 3 (\"Exactly\"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου) Αν το RowGapRule έχει οριστεί σε 4 (\"Multiple\"), τότε η μονάδα ερμηνεύεται ως half-lines. Προεπιλογή: 0"
type: docs
weight: 196
url: /el/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) μέθοδος


Η τιμή του κατακόρυφου διαστήματος μεταξύ των γραμμών ενός πίνακα; Αν το RowGapRule έχει οριστεί σε 3 ("Exactly"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του ενός σημείου) Αν το RowGapRule έχει οριστεί σε 4 ("Multiple"), τότε η μονάδα ερμηνεύεται ως half-lines. Default: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
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