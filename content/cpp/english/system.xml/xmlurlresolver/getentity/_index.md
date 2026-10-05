---
title: GetEntity()
second_title: Aspose.Slides for C++ API Reference
description: Maps a URI to an object that contains the actual resource.
type: docs
weight: 53
url: /system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo&) method


Maps a URI to an object that contains the actual resource.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The URI returned from [XmlResolver::ResolveUri(SharedPtr\<Uri\>, String)](../../xmlresolver/resolveuri/) call. |
| role | [String](../../../system/string/) | Currently not used. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)& | The type of object to return. The current implementation only returns Stream objects. |

### Return Value

A stream object or **nullptr** if a type other than stream is specified.

### Exceptions

| Exception | Description |
| --- | --- |
| XmlException | **ofObjectToReturn** is neither **nullptr** nor a **Stream** type. |
| UriFormatException | The specified URI is not an absolute URI. |
| ArgumentNullException | **absoluteUri** is **nullptr**. |
| Exception | There is a runtime error (for example, an interrupted server connection). |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlUrlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)