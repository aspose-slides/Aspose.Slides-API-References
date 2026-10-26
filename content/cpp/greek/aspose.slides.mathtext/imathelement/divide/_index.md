---
title: Divide()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή
type: docs
weight: 27
url: /el/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) μέθοδος

Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Παρονομαστής |

### Τιμή επιστροφής

νέο κλάσμα
## Σχόλια



Παράδειγμα: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) μέθοδος

Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Παρονομαστής |

### Τιμή επιστροφής

νέο κλάσμα
## Σχόλια



Παράδειγμα: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) μέθοδος

Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Παρονομαστής |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Τύπος κλάσματος: Bar, NoBar, Skewed, Linear |

### Τιμή επιστροφής

νέο κλάσμα
## Σχόλια



Παράδειγμα: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) μέθοδος

Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Παρονομαστής |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Τύπος κλάσματος: Bar, NoBar, Skewed, Linear |

### Τιμή επιστροφής

νέο κλάσμα
## Σχόλια



Παράδειγμα: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Δείτε επίσης

* Απαρίθμηση [MathFractionTypes](../../mathfractiontypes/)
* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathFraction](../../imathfraction/)
* Κλάση [IMathElement](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονόματος [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)