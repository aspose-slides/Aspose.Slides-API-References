---
title: Radical()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο επιχείρημα.
type: docs
weight: 131
url: /el/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) μέθοδος

Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο επιχείρημα.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Παράμετρος του Radical |

### Τιμή Επιστροφής

Νέα παρουσία τύπου [IMathRadical](../../imathradical/)

## Σχόλια



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) μέθοδος

Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο επιχείρημα.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Παράμετρος του Radical |

### Τιμή Επιστροφής

Νέα παρουσία τύπου [IMathRadical](../../imathradical/)

## Σχόλια



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Δείτε επίσης

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathRadical](../../imathradical/)
* Κλάση [IMathElement](../)
* Κλάση [String](../../../system/string/)
* Περιοχή ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)