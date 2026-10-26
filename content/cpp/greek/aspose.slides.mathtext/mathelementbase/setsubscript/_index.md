---
title: SetSubscript()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί δείκτη
type: docs
weight: 66
url: /el/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) μέθοδος


Δημιουργεί δείκτη

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Δείκτης (χαμηλότερη θέση στα δεξιά) |

### Τιμή επιστροφής

Νέο στοιχείο μαθηματικών τύπου [IMathSubscriptElement](../../imathsubscriptelement/)
## Σχόλια



Παράδειγμα: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) μέθοδος


Δημιουργεί δείκτη

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Δείκτης (χαμηλότερη θέση στα δεξιά) |

### Τιμή επιστροφής

Νέο στοιχείο μαθηματικών τύπου [IMathSubscriptElement](../../imathsubscriptelement/)
## Σχόλια



Παράδειγμα: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathSubscriptElement](../../imathsubscriptelement/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathElementBase](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)