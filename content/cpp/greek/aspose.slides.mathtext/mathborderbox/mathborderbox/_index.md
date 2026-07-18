---
title: MathBorderBox()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί στοιχείο MathBorderBox με ορθογώνιο πλαίσιο
type: docs
weight: 222
url: /el/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) constructor

Δημιουργεί [MathBorderBox](../) στοιχείο με ορθογώνιο πλαίσιο

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το βασικό στοιχείο στο οποίο εφαρμόζεται το πλαίσιο περιγράμματος. Μπορεί να είναι null. |

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) constructor

Δημιουργεί [MathBorderBox](../) στοιχείο

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το βασικό στοιχείο στο οποίο εφαρμόζεται το πλαίσιο περιγράμματος |
| hideTop | **bool** | Απόκρυψη επάνω άκρου |
| hideBottom | **bool** | Απόκρυψη κάτω άκρου |
| hideLeft | **bool** | Απόκρυψη αριστερής άκρου |
| hideRight | **bool** | Απόκρυψη δεξιάς άκρου |
| strikethroughHorizontal | **bool** | Οριζόντια διαγραφή |
| strikethroughVertical | **bool** | Κάθετη διαγραφή |
| strikethroughBottomLeftToTopRight | **bool** | Διαγραφή Κάτω-αριστερά προς Πάνω-δεξιά |
| strikethroughTopLeftToBottomRight | **bool** | Διαγραφή Πάνω-αριστερά προς Κάτω-δεξιά |

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathBorderBox](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)