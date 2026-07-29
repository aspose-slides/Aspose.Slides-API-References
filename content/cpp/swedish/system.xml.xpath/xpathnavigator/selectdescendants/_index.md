---
title: SelectDescendants()
second_title: Aspose.Slides för C++ API-referens
description: Väljer alla underordnade noder till den aktuella noden som har en matchande XPathNodeType.
type: docs
weight: 859
url: /sv/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) method


Väljer alla underordnade noder till den aktuella noden som har en matchande XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType för de underordnade noderna. |
| matchSelf | **bool** | **true** för att inkludera kontextnoden i urvalet; annars **false**. |

### Returvärde

Ett [XPathNodeIterator](../../xpathnodeiterator/) som innehåller de valda noderna.

## XPathNavigator::SelectDescendants(String, String, bool) method


Väljer alla underordnade noder till den aktuella noden med det angivna lokala namnet och namespace-URI:n.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det lokala namnet på de underordnade noderna. |
| namespaceURI | [String](../../../system/string/) | Namespace-URI:n för de underordnade noderna. |
| matchSelf | **bool** | **true** för att inkludera kontextnoden i urvalet; annars **false**. |

### Returvärde

Ett [XPathNodeIterator](../../xpathnodeiterator/) som innehåller de valda noderna.

## Se även

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)