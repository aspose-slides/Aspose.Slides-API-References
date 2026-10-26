---
title: ToBorderBox()
second_title: Aspose.Slides για C++ Αναφορά API
description: Τοποθετεί αυτό το στοιχείο σε ένα border-box
type: docs
weight: 261
url: /el/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() μέθοδος


Τοποθετεί αυτό το στοιχείο σε ένα border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```


### Τιμή Επιστροφής

border-box με αυτό το στοιχείο τοποθετημένο μέσα
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) μέθοδος


Τοποθετεί αυτό το στοιχείο σε ένα border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hideTop | **bool** | Απόκρυψη άνω άκρου |
| hideBottom | **bool** | Απόκρυψη κάτω άκρου |
| hideLeft | **bool** | Απόκρυψη αριστερού άκρου |
| hideRight | **bool** | Απόκρυψη δεξιού άκρου |
| strikethroughHorizontal | **bool** | Border Box Strikethrough Horizontal |
| strikethroughVertical | **bool** | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | **bool** | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | **bool** | Border Box Strikethrough Top-Left to Bottom-Right |

### Τιμή Επιστροφής

border-box με αυτό το στοιχείο τοποθετημένο μέσα
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathBorderBox](../../imathborderbox/)
* Κλάση [IMathElement](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)