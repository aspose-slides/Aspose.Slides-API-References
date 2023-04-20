---
title: CreateAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Creates an attribute node on the current element node using the namespace prefix, local name and namespace URI specified with the value specified.
type: docs
weight: 1041
url: /cpp/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) method


Creates an attribute node on the current element node using the namespace prefix, local name and namespace URI specified with the value specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | The namespace prefix of the new attribute node (if any). |
| localName | [String](../../../system/string/) | The local name of the new attribute node which cannot [String::Empty](../../../system/string/empty/) or **nullptr**. |
| namespaceURI | [String](../../../system/string/) | The namespace URI for the new attribute node (if any). |
| value | [String](../../../system/string/) | The value of the new attribute node. If [String::Empty](../../../system/string/empty/) or **nullptr** are passed, an empty attribute node is created. |

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)