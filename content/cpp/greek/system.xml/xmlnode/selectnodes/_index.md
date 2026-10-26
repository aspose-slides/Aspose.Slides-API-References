---
title: SelectNodes()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιλέγει μια λίστα κόμβων που ταιριάζουν με την έκφραση XPath.
type: docs
weight: 365
url: /el/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) μέθοδος

Επιλέγει μια λίστα κόμβων που ταιριάζουν με την έκφραση [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Η έκφραση [XPath](../../../system.xml.xpath/). |

### Τιμή Επιστροφής

Ένα [XmlNodeList](../../xmlnodelist/) που περιέχει μια συλλογή κόμβων που ταιριάζουν με το ερώτημα [XPath](../../../system.xml.xpath/).

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) μέθοδος

Επιλέγει μια λίστα κόμβων που ταιριάζουν με την έκφραση [XPath](../../../system.xml.xpath/). Οποιοδήποτε πρόθεμα που βρίσκεται στην έκφραση [XPath](../../../system.xml.xpath/) επιλύεται χρησιμοποιώντας το παρεχόμενο [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Η έκφραση [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Ένα [XmlNamespaceManager](../../xmlnamespacemanager/) για χρήση στην επίλυση ονομάτων χώρων για πρόθεμα στην έκφραση [XPath](../../../system.xml.xpath/). |

### Τιμή Επιστροφής

Ένα [XmlNodeList](../../xmlnodelist/) που περιέχει μια συλλογή κόμβων που ταιριάζουν με το ερώτημα [XPath](../../../system.xml.xpath/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlNodeList](../../xmlnodelist/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlNode](../)
* Κλάση [XmlNamespaceManager](../../xmlnamespacemanager/)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)