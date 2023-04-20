---
title: ResolveUri()
second_title: Aspose.Slides for C++ API Reference
description: Resolves the absolute URI from the base and relative URIs by calling ResolveUri on the underlying XmlResolver.
type: docs
weight: 40
url: /cpp/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) method


Resolves the absolute URI from the base and relative URIs by calling **ResolveUri** on the underlying [XmlResolver](../../xmlresolver/).

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The base URI used to resolve the relative URI. |
| relativeUri | [String](../../../system/string/) | The URI to resolve. The URI can be absolute or relative. If absolute, this value effectively replaces the **baseUri** value. If relative, it combines with the **baseUri** to make an absolute URI. |

### Return Value

The absolute URI or **nullptr** if the relative URI cannot be resolved (returned by calling **ResolveUri** on the underlying [XmlResolver](../../xmlresolver/)).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)