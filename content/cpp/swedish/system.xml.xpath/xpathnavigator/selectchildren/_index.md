---
title: SelectChildren()
second_title: Aspose.Slides för C++ API-referens
description: Väljer alla barnnoder till den aktuella noden som har den matchande XPathNodeType.
type: docs
weight: 833
url: /sv/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) metod

Väljer alla barnnoder till den aktuella noden som har den matchande XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType för barnnoderna. |

### Returvärde

En [XPathNodeIterator](../../xpathnodeiterator/) som innehåller de valda noderna.

## XPathNavigator::SelectChildren(String, String) metod

Väljer alla barnnoder till den aktuella noden som har det lokala namnet och namespace-URI som anges.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det lokala namnet på barnnoderna. |
| namespaceURI | [String](../../../system/string/) | Namespace-URI för barnnoderna. |

### Returvärde

En [XPathNodeIterator](../../xpathnodeiterator/) som innehåller de valda noderna.

## Se även

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XPathNodeIterator](../../xpathnodeiterator/)
* Klass [XPathNavigator](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)