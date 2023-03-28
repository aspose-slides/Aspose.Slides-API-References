---
title: ResolveUri()
second_title: Aspose.Slides for C++ API Reference
description: Resolves the absolute URI from the base and relative URIs.
type: docs
weight: 40
url: /cpp/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri([SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>, [String](../../../system/string/)) method


Resolves the absolute URI from the base and relative URIs.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The base URI used to resolve the relative URI. |
| relativeUri | [String](../../../system/string/) | The URI to resolve. The URI can be absolute or relative. If absolute, this value effectively replaces the **baseUri** value. If relative, it combines with the **baseUri** to make an absolute URI. |

### Return Value

The [Uri](../../../system/uri/) representing the absolute URI or **nullptr** if the relative URI cannot be resolved.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)
