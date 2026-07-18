---
title: Function()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δέχεται μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα της συνάρτησης
type: docs
weight: 40
url: /el/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) μέθοδος


Δέχεται μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα της συνάρτησης

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Ένα όρισμα της συνάρτησης |

### Τιμή επιστροφής

Νέο στοιχείο μαθηματικού τύπου [IMathFunction](../../imathfunction/)

## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) μέθοδος


Δέχεται μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα της συνάρτησης

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Ένα όρισμα της συνάρτησης |

### Τιμή επιστροφής

Νέο στοιχείο μαθηματικού τύπου [IMathFunction](../../imathfunction/)

## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Δείτε επίσης

* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathFunction](../../imathfunction/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathElementBase](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)