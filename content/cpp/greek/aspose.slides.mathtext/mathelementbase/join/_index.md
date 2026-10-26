---
title: Join()
second_title: Αναφορά API Aspose.Slides για C++
description: Συγχωνεύει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ
type: docs
weight: 1
url: /el/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) μέθοδος


Συγχωνεύει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το στοιχείο που θα συγχωνευθεί |

### Τιμή Επιστροφής

Ένα νέο [IMathBlock](../../imathblock/) που περιέχει αυτό το αντικείμενο και το συγκεκριμένο όρισμα
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) μέθοδος


Συγχωνεύει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Το μαθηματικό κείμενο που θα συγχωνευθεί |

### Τιμή Επιστροφής

Ένα νέο [IMathBlock](../../imathblock/) που περιέχει αυτό το αντικείμενο και το συγκεκριμένο όρισμα
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathBlock](../../imathblock/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathElementBase](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)