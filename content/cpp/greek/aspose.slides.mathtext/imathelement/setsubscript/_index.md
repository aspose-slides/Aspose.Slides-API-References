---
title: SetSubscript()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δημιουργεί δείκτη
type: docs
weight: 79
url: /el/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) μέθοδος

Δημιουργεί δείκτη

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Δείκτης (κατώτερο δείκτη δεξιά) |

### Τιμή Επιστροφής

Νέο μαθηματικό στοιχείο του τύπου [IMathSubscriptElement](../../imathsubscriptelement/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) μέθοδος

Δημιουργεί δείκτη

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Δείκτης (κατώτερο δείκτη δεξιά) |

### Τιμή Επιστροφής

Νέο μαθηματικό στοιχείο του τύπου [IMathSubscriptElement](../../imathsubscriptelement/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathSubscriptElement](../../imathsubscriptelement/)
* Κλάση [IMathElement](../)
* Κλάση [String](../../../system/string/)
* ΧώροςΟνομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)