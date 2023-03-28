---
title: Supports()
second_title: Aspose.Slides for C++ API Reference
description: Tests if the DOM implementation implements a specific feature.
type: docs
weight: 482
url: /cpp/system.xml/xmlnode/supports/
---
## XmlNode::Supports([String](../../../system/string/), [String](../../../system/string/)) method


Tests if the DOM implementation implements a specific feature.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| feature | [String](../../../system/string/) | The package name of the feature to test. This name is not case-sensitive. |
| version | [String](../../../system/string/) | The version number of the package name to test. If the version is not specified (null), supporting any version of the feature causes the method to return true. |

### Return Value

**true** if the feature is implemented in the specified version; otherwise, **false**.
## Remarks



The following table describes the combinations that return **true**. 

| Feature | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## See Also

* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
