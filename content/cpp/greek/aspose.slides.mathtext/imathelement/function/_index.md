---
title: Function()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το αντικείμενο ως όνομα συνάρτησης
type: docs
weight: 53
url: /el/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) μέθοδος

Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το αντικείμενο ως όνομα συνάρτησης

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Ένα όρισμα της συνάρτησης |

### Τιμή επιστροφής

Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../imathfunction/)
## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) μέθοδος

Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το αντικείμενο ως όνομα συνάρτησης

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Ένα όρισμα της συνάρτησης |

### Τιμή επιστροφής

Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../imathfunction/)
## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathFunction](../../imathfunction/)
* Κλάση [IMathElement](../)
* Κλάση [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)