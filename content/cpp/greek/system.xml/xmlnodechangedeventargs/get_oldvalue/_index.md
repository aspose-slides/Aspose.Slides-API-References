---
title: get_OldValue()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει την αρχική τιμή του κόμβου.
type: docs
weight: 53
url: /el/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() μέθοδος


Επιστρέφει την αρχική τιμή του κόμβου.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### Τιμή Επιστροφής

Η αρχική τιμή του κόμβου. Αυτή η μέθοδος επιστρέφει **nullptr** εάν ο κόμβος δεν είναι ούτε χαρακτηριστικό ούτε κόμβος κειμένου, ή εάν ο κόμβος εισάγεται. Εάν κληθεί σε ένα συμβάν **XmlDocument::NodeChanging**, το **get_OldValue** επιστρέφει την τρέχουσα τιμή του κόμβου που θα αντικατασταθεί εάν η αλλαγή επιτύχει. Εάν κληθεί σε ένα συμβάν **XmlDocument::NodeChanged**, το **get_OldValue** επιστρέφει την τιμή του κόμβου προ της αλλαγής.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlNodeChangedEventArgs](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)