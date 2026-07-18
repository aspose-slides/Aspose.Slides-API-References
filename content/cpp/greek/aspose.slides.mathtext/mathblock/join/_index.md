---
title: Join()
second_title: Aspose.Slides για C++ Αναφορά API
description: Συνδέει ένα μαθηματικό στοιχείο με αυτό το μαθηματικό μπλοκ
type: docs
weight: 183
url: /el/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) μέθοδος


Συνδέει ένα μαθηματικό στοιχείο με αυτό το μαθηματικό μπλοκ

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το στοιχείο που θα συνδεθεί |

### Τιμή επιστροφής

Την τρέχουσα παρουσία του [IMathBlock](../../imathblock/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) μέθοδος


Συνδέει ένα μαθηματικό κείμενο με αυτό το μαθηματικό μπλοκ

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Μαθηματικό κείμενο που θα συνδεθεί |

### Τιμή επιστροφής

Ένα νέο [IMathBlock](../../imathblock/) που περιέχει αυτήν την παρουσία και το καθορισμένο όρισμα
## Παρατηρήσεις



Παράδειγμα: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Δείτε επίσης

* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathBlock](../../imathblock/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathBlock](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)