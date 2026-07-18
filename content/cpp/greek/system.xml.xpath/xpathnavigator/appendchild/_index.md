---
title: AppendChild()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει ένα αντικείμενο XmlWriter που χρησιμοποιείται για τη δημιουργία ενός ή περισσότερων νέων κόμβων-παιδιών στο τέλος της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου.
type: docs
weight: 885
url: /el/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() μέθοδος

Επιστρέφει ένα αντικείμενο [XmlWriter](../../../system.xml/xmlwriter/) που χρησιμοποιείται για τη δημιουργία ενός ή περισσότερων νέων κόμβων-παιδιών στο τέλος της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### Τιμή επιστροφής

Ένα αντικείμενο [XmlWriter](../../../system.xml/xmlwriter/) που χρησιμοποιείται για τη δημιουργία νέων κόμβων-παιδιών στο τέλος της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου.

## XPathNavigator::AppendChild(String) μέθοδος

Δημιουργεί έναν νέο κόμβο-παιδί στο τέλος της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου χρησιμοποιώντας το καθορισμένο συμβολοσειρά XML.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | Η συμβολοσειρά XML για τον νέο κόμβο-παιδί. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) μέθοδος

Δημιουργεί έναν νέο κόμβο-παιδί στο τέλος της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου χρησιμοποιώντας το περιεχόμενο XML του καθορισμένου αντικειμένου [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Ένα αντικείμενο [XmlReader](../../../system.xml/xmlreader/) τοποθετημένο στα δεδομένα XML για τον νέο κόμβο-παιδί. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) μέθοδος

Δημιουργεί έναν νέο κόμβο-παιδί στο τέλος της λίστας των κόμβων-παιδιών του τρέχοντος κόμβου χρησιμοποιώντας τους κόμβους στο καθορισμένο [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Ένα αντικείμενο [XPathNavigator](../) τοποθετημένο στον κόμβο που θα προστεθεί ως νέος κόμβος-παιδί. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlWriter](../../../system.xml/xmlwriter/)
* Κλάση [XPathNavigator](../)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlReader](../../../system.xml/xmlreader/)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)