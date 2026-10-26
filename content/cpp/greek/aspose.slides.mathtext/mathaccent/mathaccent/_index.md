---
title: MathAccent()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί μια μαθηματική προσαρμογή που εφαρμόζεται σε ένα συγκεκριμένο μαθηματικό στοιχείο με την προεπιλεγμένη τιμή χαρακτήρα προσαρμογής
type: docs
weight: 40
url: /el/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>) Κατασκευαστής

Δημιουργεί μια μαθηματική προσαρμογή που εφαρμόζεται σε ένα συγκεκριμένο μαθηματικό στοιχείο με την προεπιλεγμένη τιμή χαρακτήρα προσαρμογής

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ένα μαθηματικό στοιχείο για την εφαρμογή της προσαρμογής |

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>, char16_t) Κατασκευαστής

Δημιουργεί μια μαθηματική προσαρμογή που εφαρμόζεται σε ένα συγκεκριμένο μαθηματικό στοιχείο

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | μαθηματικό στοιχείο για την εφαρμογή της προσαρμογής |
| accentCharacter | char16_t | χαρακτήρας προσαρμογής |

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathAccent](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)