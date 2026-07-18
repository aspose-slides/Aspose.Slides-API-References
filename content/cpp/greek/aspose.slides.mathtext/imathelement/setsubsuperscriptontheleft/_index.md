---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί υποδείκτη και υπερδείκτη στα αριστερά
type: docs
weight: 118
url: /el/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) μέθοδος

Δημιουργεί υποδείκτη και υπερδείκτη στα αριστερά

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Υποδείκτης (κατώτερος δείκτης στα αριστερά) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Υπερδείκτης (ανώτερος δείκτης στα αριστερά) |

### Τιμή επιστροφής

Νέο μαθηματικό στοιχείο τύπου [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) μέθοδος

Δημιουργεί υποδείκτη και υπερδείκτη στα αριστερά

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Υποδείκτης (κατώτερος δείκτης στα αριστερά) |
| superscript | [System::String](../../../system/string/) | Υπερδείκτης (ανώτερος δείκτης στα αριστερά) |

### Τιμή επιστροφής

Νέο μαθηματικό στοιχείο τύπου [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Δείτε επίσης

* typedef [SharedPtr](../../../system/sharedptr/)
* κλάση [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* κλάση [IMathElement](../)
* κλάση [String](../../../system/string/)
* χώρος ονομάτων [Aspose::Slides::MathText](../../)
* βιβλιοθήκη [Aspose.Slides](../../../)