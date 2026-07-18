---
title: CreateDocumentType()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει ένα νέο αντικείμενο XmlDocumentType.
type: docs
weight: 313
url: /el/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) method

Επιστρέφει ένα νέο αντικείμενο [XmlDocumentType](../../xmldocumenttype/).

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Όνομα του τύπου εγγράφου. |
| publicId | const [String](../../../system/string/)\& | Ο δημόσιος ταυτοποιητής του τύπου εγγράφου ή **nullptr**. Μπορείτε να καθορίσετε έναν δημόσιο URI καθώς και έναν αναγνωριστικό συστήματος για τον προσδιορισμό της θέσης του εξωτερικού υποσυνόλου DTD. |
| systemId | const [String](../../../system/string/)\& | Ο αναγνωριστικός αριθμός συστήματος του τύπου εγγράφου ή **nullptr**. Καθορίζει το URL της τοποθεσίας του αρχείου για το εξωτερικό υποσύνολο DTD. |
| internalSubset | const [String](../../../system/string/)\& | Το εσωτερικό υποσύνολο DTD του τύπου εγγράφου ή **nullptr**. |

### Τιμή Επιστροφής

Το νέο [XmlDocumentType](../../xmldocumenttype/).

## Δείτε επίσης

* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlDocumentType](../../xmldocumenttype/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlDocument](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)