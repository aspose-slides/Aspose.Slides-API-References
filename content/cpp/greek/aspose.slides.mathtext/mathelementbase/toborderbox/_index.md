---
title: ToBorderBox()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Τοποθετεί αυτό το στοιχείο σε ένα πλαίσιο-περίγραμμα
type: docs
weight: 248
url: /el/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() μέθοδος


Τοποθετεί αυτό το στοιχείο σε ένα πλαίσιο-περίγραμμα

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```


### Τιμή επιστροφής

Πλαίσιο-περίγραμμα με αυτό το στοιχείο τοποθετημένο μέσα
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) μέθοδος


Τοποθετεί αυτό το στοιχείο σε ένα πλαίσιο-περίγραμμα

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hideTop | **bool** | Απόκρυψη άνω άκρου |
| hideBottom | **bool** | Απόκρυψη κάτω άκρου |
| hideLeft | **bool** | Απόκρυψη αριστερού άκρου |
| hideRight | **bool** | Απόκρυψη δεξιού άκρου |
| strikethroughHorizontal | **bool** | Διαγραμμένη οριζόντια γραμμή στο πλαίσιο-περίγραμμα |
| strikethroughVertical | **bool** | Διαγραμμένη κάθετη γραμμή στο πλαίσιο-περίγραμμα |
| strikethroughBottomLeftToTopRight | **bool** | Διαγραμμένη γραμμή από κάτω-αριστερά προς πάνω-δεξιά στο πλαίσιο-περίγραμμα |
| strikethroughTopLeftToBottomRight | **bool** | Διαγραμμένη γραμμή από πάνω-αριστερά προς κάτω-δεξιά στο πλαίσιο-περίγραμμα |

### Τιμή επιστροφής

Πλαίσιο-περίγραμμα με αυτό το στοιχείο τοποθετημένο μέσα
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathBorderBox](../../imathborderbox/)
* Κλάση [MathElementBase](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)