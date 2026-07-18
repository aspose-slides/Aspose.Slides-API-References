---
title: SetSuperscript()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί εκθέτη
type: docs
weight: 92
url: /el/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) μέθοδος


Δημιουργεί εκθέτη

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Εκθέτης (άνω δείκτη στα δεξιά) |

### Τιμή Επιστροφής

Νέο στοιχείο μαθηματικού τύπου [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) μέθοδος


Δημιουργεί εκθέτη

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Εκθέτης (άνω δείκτη στα δεξιά) |

### Τιμή Επιστροφής

Νέο στοιχείο μαθηματικού τύπου [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Κλάση [IMathElement](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)