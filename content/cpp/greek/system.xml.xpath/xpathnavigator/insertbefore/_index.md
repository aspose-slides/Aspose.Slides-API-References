---
title: InsertBefore()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει ένα αντικείμενο XmlWriter που χρησιμοποιείται για τη δημιουργία ενός νέου αδελφικού κόμβου πριν από τον τρέχοντα επιλεγμένο κόμβο.
type: docs
weight: 911
url: /el/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() μέθοδος


Επιστρέφει ένα αντικείμενο [XmlWriter](../../../system.xml/xmlwriter/) που χρησιμοποιείται για τη δημιουργία ενός νέου αδελφικού κόμβου πριν από τον τρέχοντα επιλεγμένο κόμβο.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```


### Τιμή Επιστροφής

Ένα αντικείμενο [XmlWriter](../../../system.xml/xmlwriter/) που χρησιμοποιείται για τη δημιουργία ενός νέου αδελφικού κόμβου πριν από τον τρέχοντα επιλεγμένο κόμβο.

## XPathNavigator::InsertBefore(String) μέθοδος


Δημιουργεί έναν νέο αδελφικό κόμβο πριν από τον τρέχοντα επιλεγμένο κόμβο χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά XML.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | Η συμβολοσειρά δεδομένων XML για τον νέο αδελφικό κόμβο. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) μέθοδος


Δημιουργεί έναν νέο αδελφικό κόμβο πριν από τον τρέχοντα επιλεγμένο κόμβο χρησιμοποιώντας το περιεχόμενο XML του καθορισμένου αντικειμένου [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Ένα αντικείμενο [XmlReader](../../../system.xml/xmlreader/) τοποθετημένο στα δεδομένα XML για τον νέο αδελφικό κόμβο. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) μέθοδος


Δημιουργήσει έναν νέο αδελφικό κόμβο πριν από τον τρέχοντα επιλεγμένο κόμβο χρησιμοποιώντας τους κόμβους στο καθορισμένο [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Ένα αντικείμενο [XPathNavigator](../) τοποθετημένο στον κόμβο που θα προστεθεί ως ο νέος αδελφικός κόμβος. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlWriter](../../../system.xml/xmlwriter/)
* Κλάση [XPathNavigator](../)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlReader](../../../system.xml/xmlreader/)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)