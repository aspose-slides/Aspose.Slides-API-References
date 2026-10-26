---
title: InsertAfter()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει ένα αντικείμενο XmlWriter που χρησιμοποιείται για τη δημιουργία ενός νέου αδελφικού κόμβου μετά τον τρέχοντα επιλεγμένο κόμβο.
type: docs
weight: 898
url: /el/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() μέθοδος


Επιστρέφει ένα αντικείμενο [XmlWriter](../../../system.xml/xmlwriter/) που χρησιμοποιείται για τη δημιουργία ενός νέου αδελφικού κόμβου μετά τον τρέχοντα επιλεγμένο κόμβο.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```


### Τιμή Επιστροφής

Ένα αντικείμενο [XmlWriter](../../../system.xml/xmlwriter/) που χρησιμοποιείται για τη δημιουργία ενός νέου αδελφικού κόμβου μετά τον τρέχοντα επιλεγμένο κόμβο.

## XPathNavigator::InsertAfter(String) μέθοδος


Δημιουργεί ένα νέο αδελφικό κόμβο μετά τον τρέχοντα επιλεγμένο κόμβο χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά XML.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | Η συμβολοσειρά δεδομένων XML για το νέο αδελφικό κόμβο. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) μέθοδος


Δημιουργεί ένα νέο αδελφικό κόμβο μετά τον τρέχοντα επιλεγμένο κόμβο χρησιμοποιώντας τα περιεχόμενα XML του συγκεκριμένου αντικειμένου [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Ένα αντικείμενο [XmlReader](../../../system.xml/xmlreader/) τοποθετημένο στα δεδομένα XML για το νέο αδελφικό κόμβο. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) μέθοδος


Δημιουργεί ένα νέο αδελφικό κόμβο μετά τον τρέχοντα επιλεγμένο κόμβο χρησιμοποιώντας τους κόμβους του συγκεκριμένου αντικειμένου [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Ένα αντικείμενο [XPathNavigator](../) τοποθετημένο στον κόμβο που θα προστεθεί ως νέο αδελφικό κόμβο. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlWriter](../../../system.xml/xmlwriter/)
* Κλάση [XPathNavigator](../)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlReader](../../../system.xml/xmlreader/)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)