---
title: WriteProcessingInstruction()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Όταν υπερκαλύπτεται σε μια παράγωγη κλάση, γράφει μια οδηγία επεξεργασίας με ένα κενό μεταξύ του ονόματος και του κειμένου ως εξής: <?name text?>."
type: docs
weight: 196
url: /el/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) μέθοδος


Όταν υπερκαλύπτεται σε μια παράγωγη κλάση, γράφει μια οδηγία επεξεργασίας με ένα κενό μεταξύ του ονόματος και του κειμένου ως εξής: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το όνομα της οδηγίας επεξεργασίας. |
| text | [String](../../../system/string/) | Το κείμενο που θα συμπεριληφθεί στην οδηγία επεξεργασίας. |
## Σχόλια



Αυτή η μέθοδος χρησιμοποιείται για τη δημιουργία μιας δήλωσης XML αφού το [XmlWriter::WriteStartDocument](../writestartdocument/) έχει ήδη κληθεί. 
## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlWriter](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)