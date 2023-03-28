---
title: RemoveParam()
second_title: Aspose.Slides for C++ API Reference
description: Removes the parameter from the XsltArgumentList.
type: docs
weight: 66
url: /cpp/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&) method


Removes the parameter from the [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | The name of the parameter to remove. [XsltArgumentList](../) does not check to ensure the name passed is a valid local name; however, the name cannot be **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | The namespace URI of the parameter to remove. |

### Return Value

The parameter object or **nullptr** if one was not found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)
