---
title: WriteStartElement()
second_title: Αναφορά API του Aspose.Slides για C++
description: Όταν επαναπροσδιορίζεται σε μια παράγωγη κλάση, γράφει την καθορισμένη ετικέτα έναρξης και τη συσχετίζει με το δοσμένο χώρο ονομάτων.
type: docs
weight: 92
url: /el/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) μέθοδος

Όταν επαναπροσδιορίζεται σε μια παράγωγη κλάση, γράφει την καθορισμένη ετικέτα έναρξης και τη συσχετίζει με το δοσμένο χώρο ονομάτων.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Το τοπικό όνομα του στοιχείου. |
| ns | const [String](../../../system/string/)\& | Το URI του χώρου ονομάτων για συσχέτιση με το στοιχείο. Εάν αυτός ο χώρος ονομάτων βρίσκεται ήδη στο πεδίο ισχύος και έχει ένα συσχετισμένο πρόθεμα, ο συγγραφέας γράφει αυτόματα και αυτό το πρόθεμα επίσης. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) μέθοδος

Όταν επαναπροσδιορίζεται σε μια παράγωγη κλάση, γράφει την καθορισμένη ετικέτα έναρξης και τη συσχετίζει με το δοσμένο χώρο ονομάτων και πρόθεμα.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Το πρόθεμα του χώρου ονομάτων του στοιχείου. |
| localName | const [String](../../../system/string/)\& | Το τοπικό όνομα του στοιχείου. |
| ns | const [String](../../../system/string/)\& | Το URI του χώρου ονομάτων για συσχέτιση με το στοιχείο. |

## XmlWriter::WriteStartElement(const String\&) μέθοδος

Όταν επαναπροσδιορίζεται σε μια παράγωγη κλάση, γράφει μια ετικέτα έναρξης με το καθορισμένο τοπικό όνομα.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Το τοπικό όνομα του στοιχείου. |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlWriter](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)