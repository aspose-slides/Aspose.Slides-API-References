---
title: GetEntity()
second_title: Aspose.Slides for C++ API Reference
description: Maps a URI to an object that contains the actual resource.
type: docs
weight: 53
url: /cpp/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method


Maps a URI to an object that contains the actual resource.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The URI returned from [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/) call. |
| role | [String](../../../system/string/) | Currently not used. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | The type of object to return. The [XmlPreloadedResolver](../) supports Stream objects and TextReader objects for URIs that were added as [String](../../../system/string/). If the requested type is not supported by the resolver, an exception will be thrown. Use the XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) method to determine whether a certain **Type** is supported by this resolver. |

### Return Value

A Stream or TextReader object that corresponds to the actual source.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)