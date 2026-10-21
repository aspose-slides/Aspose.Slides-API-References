---
title: ReplaceSelf()
second_title: Aspose.Slides for C++ API Reference
description: Replaces the current node with the content of the string specified.
type: docs
weight: 950
url: /system.xml.xpath/xpathnavigator/replaceself/
---
## XPathNavigator::ReplaceSelf(String) method


Replaces the current node with the content of the string specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::ReplaceSelf(String newNode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newNode | [String](../../../system/string/) | The XML data string for the new node. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The XML string parameter is **nullptr**. |
| InvalidOperationException | The [XPathNavigator](../) is not positioned on an element, text, processing instruction, or comment node. |
| NotSupportedException | The [XPathNavigator](../) does not support editing. |
| XmlException | The XML string parameter is not well-formed. |


## XPathNavigator::ReplaceSelf(SharedPtr\<XmlReader\>) method


Replaces the current node with the contents of the [XmlReader](../../../system.xml/xmlreader/) object specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::ReplaceSelf(SharedPtr<XmlReader> newNode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newNode | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | An [XmlReader](../../../system.xml/xmlreader/) object positioned on the XML data for the new node. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentException | The [XmlReader](../../../system.xml/xmlreader/) object is in an error state or closed. |
| ArgumentNullException | The [XmlReader](../../../system.xml/xmlreader/) object parameter is **nullptr**. |
| InvalidOperationException | The [XPathNavigator](../) is not positioned on an element, text, processing instruction, or comment node. |
| NotSupportedException | The [XPathNavigator](../) does not support editing. |
| XmlException | The XML contents of the [XmlReader](../../../system.xml/xmlreader/) object parameter is not well-formed. |


## XPathNavigator::ReplaceSelf(SharedPtr\<XPathNavigator\>) method


Replaces the current node with the contents of the [XPathNavigator](../) object specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::ReplaceSelf(SharedPtr<XPathNavigator> newNode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newNode | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | An [XPathNavigator](../) object positioned on the new node. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The [XPathNavigator](../) object parameter is **nullptr**. |
| InvalidOperationException | The [XPathNavigator](../) is not positioned on an element, text, processing instruction, or comment node. |
| NotSupportedException | The [XPathNavigator](../) does not support editing. |
| XmlException | The XML contents of the [XPathNavigator](../) object parameter is not well-formed. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)