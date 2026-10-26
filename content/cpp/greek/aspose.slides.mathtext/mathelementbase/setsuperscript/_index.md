---
title: SetSuperscript()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί εκθέτη
type: docs
weight: 79
url: /el/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) μέθοδος


Δημιουργεί εκθέτη

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Εκθέτης (ανώτερος δείκτης στα δεξιά) |

### Τιμή επιστροφής

Νέο στοιχείο μαθηματικού τύπου [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Σχόλια



Παράδειγμα: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) μέθοδος


Δημιουργεί εκθέτη

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Εκθέτης (ανώτερος δείκτης στα δεξιά) |

### Τιμή επιστροφής

Νέο στοιχείο μαθηματικού τύπου [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Σχόλια



Παράδειγμα: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)