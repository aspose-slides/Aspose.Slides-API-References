---
title: get_RowSpacing()
second_title: Aspose.Slides για την Αναφορά API C++
description: "Διάστημα μεταξύ των γραμμών ενός πίνακα. Χρησιμοποιείται μόνο όταν το RowSpacingRule ορίζεται σε 3, ακριβώς σε αυτήν την περίπτωση η μονάδα μέτρησης είναι σημεία ή Multiple, στην οποία περίπτωση η μονάδα μέτρησης είναι μισές γραμμές. Προεπιλογή: 0"
type: docs
weight: 118
url: /el/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() μέθοδος

Διάστημα μεταξύ των γραμμών ενός πίνακα. Χρησιμοποιείται μόνο όταν το RowSpacingRule ορίζεται σε 3, ακριβώς σε αυτήν την περίπτωση η μονάδα μέτρησης είναι σημεία, ή Multiple, όπου η μονάδα μέτρησης είναι μισές γραμμές. Προεπιλογή: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
```

## Σχόλια

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