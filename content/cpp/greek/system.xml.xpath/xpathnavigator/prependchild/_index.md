---
title: PrependChild()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει ένα αντικείμενο XmlWriter που χρησιμοποιείται για τη δημιουργία ενός νέου παιδικού κόμβου στην αρχή της λίστας των παιδικών κόμβων του τρέχοντος κόμβου.
type: docs
weight: 872
url: /el/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() μέθοδος


Επιστρέφει ένα αντικείμενο [XmlWriter](../../../system.xml/xmlwriter/) που χρησιμοποιείται για τη δημιουργία ενός νέου παιδικού κόμβου στην αρχή της λίστας των παιδικών κόμβων του τρέχοντος κόμβου.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```


### Τιμή επιστροφής

Ένα αντικείμενο [XmlWriter](../../../system.xml/xmlwriter/) που χρησιμοποιείται για τη δημιουργία ενός νέου παιδικού κόμβου στην αρχή της λίστας των παιδικών κόμβων του τρέχοντος κόμβου.

## XPathNavigator::PrependChild(String) μέθοδος


Δημιουργεί ένα νέο παιδικό κόμβο στην αρχή της λίστας των παιδικών κόμβων του τρέχοντος κόμβου χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά XML.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | Η συμβολοσειρά δεδομένων XML για το νέο παιδικό κόμβο. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) μέθοδος


Δημιουργεί ένα νέο παιδικό κόμβο στην αρχή της λίστας των παιδικών κόμβων του τρέχοντος κόμβου χρησιμοποιώντας το περιεχόμενο XML του αντικειμένου [XmlReader](../../../system.xml/xmlreader/) που καθορίζεται.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Ένα αντικείμενο [XmlReader](../../../system.xml/xmlreader/) τοποθετημένο στα δεδομένα XML για το νέο παιδικό κόμβο. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) μέθοδος


Δημιουργεί ένα νέο παιδικό κόμβο στην αρχή της λίστας των παιδικών κόμβων του τρέχοντος κόμβου χρησιμοποιώντας τους κόμβους του αντικειμένου [XPathNavigator](../) που καθορίζεται.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Ένα αντικείμενο [XPathNavigator](../) τοποθετημένο στον κόμβο που θα προστεθεί ως νέο παιδικό κόμβο. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlWriter](../../../system.xml/xmlwriter/)
* Κλάση [XPathNavigator](../)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlReader](../../../system.xml/xmlreader/)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)