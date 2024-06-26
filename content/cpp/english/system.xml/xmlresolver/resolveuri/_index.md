---
title: ResolveUri()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, resolves the absolute URI from the base and relative URIs.
type: docs
weight: 27
url: /system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) method


When overridden in a derived class, resolves the absolute URI from the base and relative URIs.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The base URI used to resolve the relative URI. |
| relativeUri | [String](../../../system/string/) | The URI to resolve. The URI can be absolute or relative. If absolute, this value effectively replaces the **baseUri** value. If relative, it combines with the **baseUri** to make an absolute URI. |

### Return Value

The absolute URI or **nullptr** if the relative URI cannot be resolved.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)