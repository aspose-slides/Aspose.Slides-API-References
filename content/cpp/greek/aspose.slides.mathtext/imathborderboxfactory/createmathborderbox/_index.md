---
title: CreateMathBorderBox()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργήστε ένα πλαίσιο περιγράμματος μαθηματικού εφαρμόζοντας το στο στοιχείο
type: docs
weight: 1
url: /el/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) μέθοδος

Δημιουργήστε ένα πλαίσιο περιγράμματος μαθηματικού εφαρμόζοντας το στοιχείο

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | στοιχείο μαθηματικού στο οποίο θα εφαρμοστεί το πλαίσιο περιγράμματος |

### Τιμή Επιστροφής

νέο στοιχείο πλαισίου περιγράμματος

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) μέθοδος

Δημιουργήστε ένα πλαίσιο περιγράμματος μαθηματικού εφαρμόζοντας το στοιχείο

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | στοιχείο μαθηματικού στο οποίο θα εφαρμοστεί το πλαίσιο περιγράμματος |
| hideTop | **bool** | Απόκρυψη άνω άκρου |
| hideBottom | **bool** | Απόκρυψη κάτω άκρου |
| hideLeft | **bool** | Απόκρυψη αριστερού άκρου |
| hideRight | **bool** | Απόκρυψη δεξιού άκρου |
| strikethroughHorizontal | **bool** | Οριζόντια διαγραφή πλαισίου περιγράμματος |
| strikethroughVertical | **bool** | Κάθετη διαγραφή πλαισίου περιγράμματος |
| strikethroughBottomLeftToTopRight | **bool** | Διαγραφή πλαισίου περιγράμματος από κάτω-αριστερά προς πάνω-δεξιά |
| strikethroughTopLeftToBottomRight | **bool** | Διαγραφή πλαισίου περιγράμματος από πάνω-αριστερά προς κάτω-δεξιά |

### Τιμή Επιστροφής

νέο στοιχείο πλαισίου περιγράμματος

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [IMathElement](../../imathelement/)
* Class [IMathBorderBoxFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)