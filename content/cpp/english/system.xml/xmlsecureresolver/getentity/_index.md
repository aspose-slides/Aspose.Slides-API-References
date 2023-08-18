---
title: GetEntity()
second_title: Aspose.Slides for C++ API Reference
description: Maps a URI to an object that contains the actual resource.
type: docs
weight: 27
url: /system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method


Maps a URI to an object that contains the actual resource.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The URI that is returned from [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) call. |
| role | [String](../../../system/string/) | Currently not used. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | The type of object to return. The current version only returns Stream objects. |

### Return Value

The stream returned by calling **GetEntity** on the underlying [XmlResolver](../../xmlresolver/). If a type other than Stream is specified, the method returns **nullptr**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)