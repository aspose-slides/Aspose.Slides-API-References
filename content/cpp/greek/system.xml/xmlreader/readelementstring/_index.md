---
title: ReadElementString()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Διαβάζει ένα στοιχείο μόνο με κείμενο. Ωστόσο, συνιστάται η χρήση της XmlReader::ReadElementContentAsString μέθοδος αντί αυτού, επειδή παρέχει έναν πιο απλό τρόπο για την εκτέλεση αυτής της λειτουργίας."
type: docs
weight: 859
url: /el/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() μέθοδος

Διαβάζει ένα στοιχείο μόνο με κείμενο. Ωστόσο, συνιστάται η χρήση της [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) μέθοδος αντί αυτού, επειδή παρέχει έναν πιο απλό τρόπο για την εκτέλεση αυτής της λειτουργίας.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### Τιμή Επιστροφής

Το κείμενο που περιέχεται στο στοιχείο που διαβάστηκε. Ένα κενό string αν το στοιχείο είναι κενό.

## XmlReader::ReadElementString(String) μέθοδος

Ελέγχει ότι η τιμή [XmlReader::get_Name](../get_name/) του ευρεθέντος στοιχείου ταιριάζει με τη δοθείσα συμβολοσειρά πριν από την ανάγνωση ενός στοιχείου μόνο με κείμενο. Ωστόσο, συνιστάται η χρήση της [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) μέθοδος αντί αυτού, επειδή παρέχει έναν πιο απλό τρόπο για την εκτέλεση αυτής της λειτουργίας.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το όνομα προς έλεγχο. |

### Τιμή Επιστροφής

Το κείμενο που περιέχεται στο στοιχείο που διαβάστηκε. Ένα κενό string αν το στοιχείο είναι κενό.

## XmlReader::ReadElementString(String, String) μέθοδος

Ελέγχει ότι οι τιμές [XmlReader::get_LocalName](../get_localname/) και [XmlReader::get_NamespaceURI](../get_namespaceuri/) του ευρεθέντος στοιχείου ταιριάζουν με τις δοθείσες συμβολοσειρές πριν από την ανάγνωση ενός στοιχείου μόνο με κείμενο. Ωστόσο, συνιστάται η χρήση της [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) μέθοδος αντί αυτού, επειδή παρέχει έναν πιο απλό τρόπο για την εκτέλεση αυτής της λειτουργίας.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Το τοπικό όνομα προς έλεγχο. |
| ns | [String](../../../system/string/) | Το URI του χώρου ονομάτων προς έλεγχο. |

### Τιμή Επιστροφής

Το κείμενο που περιέχεται στο στοιχείο που διαβάστηκε. Ένα κενό string αν το στοιχείο είναι κενό.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)