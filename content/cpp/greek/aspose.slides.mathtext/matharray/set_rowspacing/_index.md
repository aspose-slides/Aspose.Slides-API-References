---
title: set_RowSpacing()
second_title: Αναφορά API Aspose.Slides για C++
description: "Διάστημα μεταξύ γραμμών ενός πίνακα. Χρησιμοποιείται μόνο όταν το RowSpacingRule είναι ορισμένο στην τιμή 3 Exactly, στην οποία περίπτωση η μονάδα μέτρησης είναι σημεία ή Multiple, στην οποία περίπτωση η μονάδα μέτρησης είναι μισές γραμμές. Προεπιλογή: 0"
type: docs
weight: 131
url: /el/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) μέθοδος

Διάστημα μεταξύ γραμμών ενός πίνακα. Χρησιμοποιείται μόνο όταν το RowSpacingRule έχει οριστεί στην τιμή 3 Exactly, στην οποία περίπτωση η μονάδα μέτρησης είναι σημεία ή Multiple, στην οποία περίπτωση η μονάδα μέτρησης είναι μισές γραμμές. Προεπιλογή: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
```

## Παρατηρήσεις

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