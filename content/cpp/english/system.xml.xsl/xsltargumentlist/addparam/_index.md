---
title: AddParam()
second_title: Aspose.Slides for C++ API Reference
description: Adds a parameter to the XsltArgumentList and associates it with the namespace qualified name.
type: docs
weight: 40
url: /system.xml.xsl/xsltargumentlist/addparam/
---
## XsltArgumentList::AddParam(const String\&, const String\&, const SharedPtr\<Object\>\&) method


Adds a parameter to the [XsltArgumentList](../) and associates it with the namespace qualified name.

```cpp
void System::Xml::Xsl::XsltArgumentList::AddParam(const String &name, const String &namespaceUri, const SharedPtr<Object> &parameter)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | The name to associate with the parameter. |
| namespaceUri | const [String](../../../system/string/)\& | The namespace URI to associate with the parameter. To use the default namespace, specify an empty string. |
| parameter | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | The parameter value or object to add to the list. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)