---
title: SupportsType()
second_title: Aspose.Slides for C++ API Reference
description: Enables the resolver to return types other than Stream.
type: docs
weight: 40
url: /cpp/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType([SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>, const [TypeInfo](../../../system/typeinfo/)\&) method


Enables the resolver to return types other than Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | The type to return. |

### Return Value

**true** if the **type** is supported; otherwise, **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
