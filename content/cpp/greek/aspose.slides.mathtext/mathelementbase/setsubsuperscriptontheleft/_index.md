---
title: SetSubSuperscriptOnTheLeft()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί δείκτη και εκθέτη στα αριστερά
type: docs
weight: 105
url: /el/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) μέθοδος

Δημιουργεί δείκτη και εκθέτη στα αριστερά

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Δείκτης (χαμηλότερος δείκτης στα αριστερά) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Εκθέτης (ανώτερος δείκτης στα αριστερά) |

### Τιμή Επιστροφής

Νέο στοιχείο μαθηματικών τύπου [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) μέθοδος

Δημιουργεί δείκτη και εκθέτη στα αριστερά

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Δείκτης (χαμηλότερος δείκτης στα αριστερά) |
| superscript | [System::String](../../../system/string/) | Εκθέτης (ανώτερος δείκτης στα αριστερά) |

### Τιμή Επιστροφής

Νέο στοιχείο μαθηματικών τύπου [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathElementBase](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)