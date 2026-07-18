---
title: Nary()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί έναν τελεστή N-ary
type: docs
weight: 170
url: /el/aspose.slides.mathtext/imathelement/nary/
---
## IMathElement::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) μέθοδος

Δημιουργεί έναν τελεστή N-ary

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | Ο τύπος του τελεστή N-ary |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Το κατώτερο όριο |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Το ανώτερο όριο |

### Τιμή Επιστροφής

Νέο στιγμιότυπο τύπου [IMathNaryOperator](../../imathnaryoperator/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"i-1");
System::SharedPtr<IMathElement> lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
System::SharedPtr<IMathElement> upperLimit = System::MakeObject<MathematicalText>(u"\U0001d45b");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## IMathElement::Nary(MathNaryOperatorTypes, System::String, System::String) μέθοδος

Δημιουργεί έναν τελεστή N-ary

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | Ο τύπος του τελεστή N-ary |
| lowerLimit | [System::String](../../../system/string/) | Το κατώτερο όριο |
| upperLimit | [System::String](../../../system/string/) | Το ανώτερο όριο |

### Τιμή Επιστροφής

Νέο στιγμιότυπο τύπου [IMathNaryOperator](../../imathnaryoperator/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d45b");
```

## Δείτε επίσης

* Απαρίθμηση [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathNaryOperator](../../imathnaryoperator/)
* Κλάση [IMathElement](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)