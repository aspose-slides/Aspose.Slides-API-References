---
title: GetEntity()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, maps a URI to an object that contains the actual resource.
type: docs
weight: 14
url: /cpp/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity([SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>, [String](../../../system/string/), const [TypeInfo](../../../system/typeinfo/)\&) method


When overridden in a derived class, maps a URI to an object that contains the actual resource.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The URI returned from [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) call. |
| role | [String](../../../system/string/) | Currently not used. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | The type of object to return. The current version only returns Stream objects. |

### Return Value

A stream object or **nullptr** if a type other than stream is specified.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
