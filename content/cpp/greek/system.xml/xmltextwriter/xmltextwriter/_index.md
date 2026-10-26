---
title: XmlTextWriter()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Δημιουργεί μια παρουσία της κλάσης XmlTextWriter χρησιμοποιώντας τη συγκεκριμένη ροή και κωδικοποίηση.
type: docs
weight: 183
url: /el/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) κατασκευαστής

Δημιουργεί μια παρουσία της κλάσης [XmlTextWriter](../) χρησιμοποιώντας τη συγκεκριμένη ροή και κωδικοποίηση.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή στην οποία θέλετε να γράψετε. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Η κωδικοποίηση για δημιουργία. Εάν η κωδικοποίηση είναι **nullptr** γράφει τη ροή ως UTF-8 και παραλείπει το χαρακτηριστικό κωδικοποίησης από το **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) κατασκευαστής

Δημιουργεί μια παρουσία της κλάσης [XmlTextWriter](../) χρησιμοποιώντας το καθορισμένο αρχείο.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Το όνομα αρχείου για εγγραφή. Εάν το αρχείο υπάρχει, το περικόπτει και το αντικαθιστά με το νέο περιεχόμενο. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Η κωδικοποίηση για δημιουργία. Εάν η κωδικοποίηση είναι **nullptr** γράφει το αρχείο ως UTF-8 και παραλείπει το χαρακτηριστικό κωδικοποίησης από το **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) κατασκευαστής

Δημιουργεί μια παρουσία της κλάσης [XmlTextWriter](../) χρησιμοποιώντας το καθορισμένο TextWriter.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Ο TextWriter για εγγραφή. Θεωρείται ότι ο TextWriter είναι ήδη ρυθμισμένος στη σωστή κωδικοποίηση. |

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [Encoding](../../../system.text/encoding/)
* Κλάση [XmlTextWriter](../)
* Κλάση [String](../../../system/string/)
* Κλάση [TextWriter](../../../system.io/textwriter/)
* Χώρο ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)