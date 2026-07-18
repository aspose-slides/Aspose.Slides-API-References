---
title: get_NewValue()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει τη νέα τιμή του κόμβου.
type: docs
weight: 66
url: /el/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() μέθοδος

Επιστρέφει τη νέα τιμή του κόμβου.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```

### Τιμή Επιστροφής

Η νέα τιμή του κόμβου. Αυτή η μέθοδος επιστρέφει **nullptr** εάν ο κόμβος δεν είναι ούτε γνώρισμα ούτε κόμβος κειμένου, ή εάν ο κόμβος αφαιρείται. Εάν κληθεί σε ένα συμβάν **XmlDocument::NodeChanging**, η **get_NewValue** επιστρέφει την τιμή του κόμβου εάν η αλλαγή είναι επιτυχής. Εάν κληθεί σε ένα συμβάν **XmlDocument::NodeChanged**, η **get_NewValue** επιστρέφει την τρέχουσα τιμή του κόμβου.

## Δείτε Επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlNodeChangedEventArgs](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)