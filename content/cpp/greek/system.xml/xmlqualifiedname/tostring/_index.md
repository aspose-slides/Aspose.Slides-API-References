---
title: ToString()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει την τιμή συμβολοσειράς του XmlQualifiedName.
type: docs
weight: 79
url: /el/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const μέθοδος


Επιστρέφει την τιμή συμβολοσειράς του [XmlQualifiedName](../).

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```


### Τιμή Επιστροφής

Η τιμή συμβολοσειράς του [XmlQualifiedName](../) σε μορφή **namespace:localname**. Εάν το αντικείμενο δεν έχει ορισμένο namespace, αυτή η μέθοδος επιστρέφει μόνο το τοπικό όνομα.

## XmlQualifiedName::ToString(const String\&, const String\&) μέθοδος


Επιστρέφει την τιμή συμβολοσειράς του [XmlQualifiedName](../).

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Το όνομα του αντικειμένου. |
| ns | const [String](../../../system/string/)\& | Το namespace του αντικειμένου. |

### Τιμή Επιστροφής

Η τιμή συμβολοσειράς του [XmlQualifiedName](../) σε μορφή **namespace:localname**. Εάν το αντικείμενο δεν έχει ορισμένο namespace, αυτή η μέθοδος επιστρέφει μόνο το τοπικό όνομα.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlQualifiedName](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)