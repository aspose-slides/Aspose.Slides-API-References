---
title: set_Prefix()
second_title: Aspose.Slides for C++ API Reference
description: Sets the namespace prefix of this node.
type: docs
weight: 53
url: /system.xml/xmlelement/set_prefix/
---
## XmlElement::set_Prefix(String) method


Sets the namespace prefix of this node.

```cpp
void System::Xml::XmlElement::set_Prefix(String value) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [String](../../../system/string/) | The value to set. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentException | This node is read-only. |
| XmlException | The specified prefix contains an invalid character. The specified prefix is malformed. The namespaceURI of this node is **nullptr**. The specified prefix is "xml" and the namespaceURI of this node is different from [http://www.w3.org/XML/1998/namespace](http://www.w3.org/XML/1998/namespace). |


## See Also

* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)