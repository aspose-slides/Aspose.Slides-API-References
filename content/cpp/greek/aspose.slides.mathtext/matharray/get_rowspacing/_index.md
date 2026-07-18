---
title: get_RowSpacing()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Απόσταση μεταξύ γραμμών ενός πίνακα Χρησιμοποιείται μόνο όταν το RowSpacingRule είναι ορισμένο σε 3 Exact στην περίπτωση αυτή η μονάδα μέτρησης είναι σημεία ή Multiple στην περίπτωση αυτή η μονάδα μέτρησης είναι μισές γραμμές. Default: 0"
type: docs
weight: 118
url: /el/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() μέθοδος

Απόσταση μεταξύ γραμμών ενός πίνακα Χρησιμοποιείται μόνο όταν το RowSpacingRule είναι ορισμένο σε 3 Exact στην περίπτωση αυτή η μονάδα μέτρησης είναι σημεία ή Multiple στην περίπτωση αυτή η μονάδα μέτρησης είναι μισές γραμμές. Προεπιλογή: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## Σχόλια

Παράδειγμα:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Δείτε επίσης

* Κλάση [MathArray](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)