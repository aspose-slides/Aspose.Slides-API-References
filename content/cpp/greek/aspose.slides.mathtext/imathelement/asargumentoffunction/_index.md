---
title: AsArgumentOfFunction()
second_title: Αναφορά API Aspose.Slides για C++
description: Καλεί την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα
type: docs
weight: 66
url: /el/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) μέθοδος

Πραγματοποιεί την κλήση της καθορισμένης συνάρτησης χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Όνομα συνάρτησης |

### Τιμή Επιστροφής

Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../imathfunction/)

## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) μέθοδος

Πραγματοποιεί την κλήση της καθορισμένης συνάρτησης χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Όνομα συνάρτησης |

### Τιμή Επιστροφής

Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../imathfunction/)

## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) μέθοδος

Πραγματοποιεί την κλήση της καθορισμένης συνάρτησης χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Ένας από τους κοινούς τύπους συναρτήσεων ενός ορίσματος |

### Τιμή Επιστροφής

Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../imathfunction/)

## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) μέθοδος

Πραγματοποιεί την κλήση της καθορισμένης συνάρτησης χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα και το καθορισμένο πρόσθετο όρισμα

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Ένας από τους κοινούς τύπους συναρτήσεων δύο ορισμάτων: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Πρόσθετο όρισμα ανάλογα με τον τύπο της συνάρτησης |

### Τιμή Επιστροφής

Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../imathfunction/)

## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Επιστρέφει το λογάριθμο του 'x' στη βάση '5'
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) μέθοδος

Πραγματοποιεί την κλήση της καθορισμένης συνάρτησης χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα και το καθορισμένο πρόσθετο όρισμα

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Ένας από τους κοινούς τύπους συναρτήσεων δύο ορισμάτων: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Πρόσθετο όρισμα ανάλογα με τον τύπο της συνάρτησης |

### Τιμή Επιστροφής

Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../imathfunction/)

## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Επιστρέφει το λογάριθμο του 'x' στη βάση '5'
```

## Δείτε επίσης

* Απαρίθμηση [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Απαρίθμηση [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Τύπος Ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathFunction](../../imathfunction/)
* Κλάση [IMathElement](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)