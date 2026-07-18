---
title: CreateXmlDeclaration()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Δημιουργεί έναν κόμβο XmlDeclaration με τις καθορισμένες τιμές.
type: docs
weight: 378
url: /el/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) μέθοδος

Δημιουργεί έναν [XmlDeclaration](../../xmldeclaration/) κόμβο με τις καθορισμένες τιμές.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | Η έκδοση πρέπει να είναι "1.0". |
| encoding | const [String](../../../system/string/)\& | Η τιμή του χαρακτηριστικού κωδικοποίησης. Αυτή είναι η κωδικοποίηση που χρησιμοποιείται όταν αποθηκεύετε το [XmlDocument](../) σε αρχείο ή ροή· επομένως, πρέπει να οριστεί σε μια συμβολοσειρά που υποστηρίζεται από την κλάση [Text::Encoding](../../../system.text/encoding/), διαφορετικά "XmlDocument::Save(String)" αποτυγχάνει. Εάν αυτό είναι **nullptr** ή [String::Empty](../../../system/string/empty/), η μέθοδος [XmlDocument::Save](../save/) δεν γράφει χαρακτηριστικό κωδικοποίησης στη δήλωση XML και επομένως χρησιμοποιείται η προεπιλεγμένη κωδικοποίηση, UTF-8. |
| standalone | const [String](../../../system/string/)\& | Η τιμή πρέπει να είναι είτε "yes" είτε "no". Εάν αυτό είναι **nullptr** ή [String::Empty](../../../system/string/empty/), η μέθοδος [XmlDocument::Save](../save/) δεν γράφει χαρακτηριστικό standalone στη δήλωση XML. |

### Τιμή Επιστροφής

Ο νέος [XmlDeclaration](../../xmldeclaration/) κόμβος.

## Παρατηρήσεις

Σημείωση: Εάν το [XmlDocument](../) αποθηκευτεί είτε σε TextWriter είτε σε [XmlTextWriter](../../xmltextwriter/), αυτή η τιμή κωδικοποίησης αγνοείται. Αντ' αυτού, χρησιμοποιείται η κωδικοποίηση του TextWriter ή του [XmlTextWriter](../../xmltextwriter/). Αυτό διασφαλίζει ότι το XML που γράφεται μπορεί να αναγνωσθεί ξανά χρησιμοποιώντας τη σωστή κωδικοποίηση.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlDeclaration](../../xmldeclaration/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlDocument](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)