---
title: WriteNode()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, copies everything from the reader to the writer and moves the reader to the start of the next sibling.
type: docs
weight: 430
url: /cpp/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode([SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>, **bool**) method


When overridden in a derived class, copies everything from the reader to the writer and moves the reader to the start of the next sibling.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | The [XmlReader](../../xmlreader/) to read from. |
| defattr | **bool** | **true** to copy the default attributes from the [XmlReader](../../xmlreader/); otherwise, **false**. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlWriter::WriteNode([SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>, **bool**) method


Copies everything from the XPathNavigator object to the writer. The position of the XPathNavigator remains unchanged.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | The XPathNavigator to copy from. |
| defattr | **bool** | **true** to copy the default attributes; otherwise, **false**. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
