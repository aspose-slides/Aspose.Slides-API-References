---
title: SelectAncestors()
second_title: Aspose.Slides för C++ API-referens
description: Väljer alla föräldranoder till den aktuella noden som har en matchande XPathNodeType.
type: docs
weight: 846
url: /sv/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) metod

Väljer alla föräldranoder till den aktuella noden som har en matchande XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType för föräldranoderna. |
| matchSelf | **bool** | För att inkludera kontextnod i urvalet, **true**; annars, **false**. |

### Returvärde

Ett [XPathNodeIterator](../../xpathnodeiterator/) som innehåller de valda noderna. De returnerade noderna är i omvänd dokumentordning.

## XPathNavigator::SelectAncestors(String, String, bool) metod

Väljer alla föräldranoder till den aktuella noden som har det angivna lokala namnet och namespace-URI.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det lokala namnet på föräldranoderna. |
| namespaceURI | [String](../../../system/string/) | Namespace-URI för föräldranoderna. |
| matchSelf | **bool** | För att inkludera kontextnod i urvalet, **true**; annars, **false**. |

### Returvärde

Ett [XPathNodeIterator](../../xpathnodeiterator/) som innehåller de valda noderna. De returnerade noderna är i omvänd dokumentordning.

## Se även

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XPathNodeIterator](../../xpathnodeiterator/)
* Klass [XPathNavigator](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)