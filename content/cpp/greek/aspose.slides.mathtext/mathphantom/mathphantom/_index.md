---
title: MathPhantom()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathPhantom χρησιμοποιώντας το καθορισμένο βασικό μαθηματικό στοιχείο.
type: docs
weight: 144
url: /el/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) κατασκευαστής

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [MathPhantom](../) χρησιμοποιώντας το καθορισμένο βασικό μαθηματικό στοιχείο.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το βασικό [IMathElement](../../imathelement/) του οποίου η ορατότητα και η διάταξη θα ελεγχθούν από το phantom. Αυτό το στοιχείο ορίζει το περιεχόμενο που μπορεί να κρυφτεί ή να εμφανιστεί, ενώ εξακολουθεί να επηρεάζει την γεωμετρική ευθυγράμμιση των περιβάλλουσων μαθηματικών. |

## Παρατηρήσεις

Το στοιχείο phantom χρησιμοποιείται για να διατηρήσει ή να καταστέλλει τον οπτικό χώρο της βασικής του έκφρασης χωρίς απαραίτητα να το εμφανίζει. Συμπίπτει με το στοιχείο OMML **<m:phant>**.

Παράδειγμα:
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathPhantom](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)