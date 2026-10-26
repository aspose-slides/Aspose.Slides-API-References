---
title: SetContext()
second_title: Aspose.Slides για C++ API Αναφορά
description: Όταν παρακαμφθεί σε μια κληρονομημένη κλάση, καθορίζει το αντικείμενο XmlNamespaceManager που θα χρησιμοποιηθεί για την επίλυση ονομάτων χώρων.
type: docs
weight: 53
url: /el/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) μέθοδος

Όταν παρακαμφθεί σε μια κληρονομημένη κλάση, καθορίζει το αντικείμενο [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) που θα χρησιμοποιηθεί για την επίλυση ονομάτων χώρων.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | Ένα αντικείμενο [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) που θα χρησιμοποιηθεί για την επίλυση ονομάτων χώρων. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) μέθοδος

Όταν παρακαμφθεί σε μια κληρονομημένη κλάση, καθορίζει το αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που θα χρησιμοποιηθεί για την επίλυση ονομάτων χώρων.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Ένα αντικείμενο που υλοποιεί τη διεπαφή [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που θα χρησιμοποιηθεί για την επίλυση ονομάτων χώρων. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Κλάση [XPathExpression](../)
* Κλάση [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)