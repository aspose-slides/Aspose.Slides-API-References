---
title: SelectSingleNode()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιλέγει το πρώτο XmlNode που ταιριάζει με την έκφραση XPath.
type: docs
weight: 352
url: /el/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) μέθοδος

Επιλέγει το πρώτο [XmlNode](../) που ταιριάζει με την [XPath](../../../system.xml.xpath/) έκφραση.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Η [XPath](../../../system.xml.xpath/) έκφραση. |

### Τιμή Επιστροφής

Το πρώτο [XmlNode](../) που ταιριάζει με το [XPath](../../../system.xml.xpath/) ερώτημα ή **nullptr** εάν δεν βρεθεί κανένας αντιστοιχούμενος κόμβος.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) μέθοδος

Επιλέγει το πρώτο [XmlNode](../) που ταιριάζει με την [XPath](../../../system.xml.xpath/) έκφραση. Οποιοδήποτε πρόθεμα που βρέθηκε στην [XPath](../../../system.xml.xpath/) έκφραση λύνεται χρησιμοποιώντας το παρεχόμενο [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Η [XPath](../../../system.xml.xpath/) έκφραση. |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Ένα [XmlNamespaceManager](../../xmlnamespacemanager/) για τη χρήση στην επίλυση ονομάτων χώρου για προθέματα στην [XPath](../../../system.xml.xpath/) έκφραση. |

### Τιμή Επιστροφής

Το πρώτο [XmlNode](../) που ταιριάζει με το [XPath](../../../system.xml.xpath/) ερώτημα ή **nullptr** εάν δεν βρεθεί κανένας αντιστοιχούμενος κόμβος.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNode](../)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlNamespaceManager](../../xmlnamespacemanager/)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)