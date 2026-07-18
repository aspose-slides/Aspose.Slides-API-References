---
title: set_RowSpacing()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Απόσταση μεταξύ γραμμών ενός πίνακα Χρησιμοποιείται μόνο όταν το RowSpacingRule είναι ορισμένο σε 3 Ακριβώς σε αυτήν την περίπτωση η μονάδα μέτρησης είναι points ή Multiple στην οποία η μονάδα μέτρησης είναι μισές γραμμές. Προεπιλογή: 0"
type: docs
weight: 131
url: /el/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) μέθοδος

Απόσταση μεταξύ γραμμών ενός πίνακα Χρησιμοποιείται μόνο όταν το RowSpacingRule έχει οριστεί στο 3 Ακριβώς σε αυτήν την περίπτωση η μονάδα μέτρησης είναι points ή Multiple στην οποία η μονάδα μέτρησης είναι μισές γραμμές. Προεπιλογή: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Δείτε επίσης

* Κλάση [IMathArray](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)