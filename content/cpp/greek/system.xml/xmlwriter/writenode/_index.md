---
title: WriteNode()
second_title: Aspose.Slides για C++ Αναφορά API
description: Όταν παρακαμφθεί σε κλάση που κληρονομεί, αντιγράφει όλα από τον αναγνώστη στον γράφο και μετακινεί τον αναγνώστη στην αρχή του επόμενου αδελφού.
type: docs
weight: 430
url: /el/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) μέθοδος

Όταν παρακαμφθεί σε κλάση που κληρονομεί, αντιγράφει όλα από τον αναγνώστη στον γράφο και μετακινεί τον αναγνώστη στην αρχή του επόμενου αδελφού.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Ο [XmlReader](../../xmlreader/) για ανάγνωση. |
| defattr | **bool** | **true** για αντιγραφή των προεπιλεγμένων ιδιοτήτων από το [XmlReader](../../xmlreader/)· διαφορετικά, **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) μέθοδος

Αντιγράφει όλα από το αντικείμενο XPathNavigator στον γράφο. Η θέση του XPathNavigator παραμένει αμετάβλητη.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Ο XPathNavigator για αντιγραφή. |
| defattr | **bool** | **true** για αντιγραφή των προεπιλεγμένων ιδιοτήτων· διαφορετικά, **false**. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlReader](../../xmlreader/)
* Κλάση [XmlWriter](../)
* Κλάση [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)