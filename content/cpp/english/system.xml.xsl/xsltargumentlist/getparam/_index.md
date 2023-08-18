---
title: GetParam()
second_title: Aspose.Slides for C++ API Reference
description: Returns the parameter associated with the namespace qualified name.
type: docs
weight: 14
url: /system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) method


Returns the parameter associated with the namespace qualified name.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | The name of the parameter. [XsltArgumentList](../) does not check to ensure the name passed is a valid local name; however, the name cannot be **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | The namespace URI associated with the parameter. |

### Return Value

The parameter object or **nullptr** if one was not found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)