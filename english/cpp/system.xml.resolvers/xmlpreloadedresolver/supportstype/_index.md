---
title: SupportsType()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether the resolver supports other Types than just Stream.
type: docs
weight: 66
url: /cpp/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType([SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>, const [TypeInfo](../../../system/typeinfo/)\&) method


Determines whether the resolver supports other Types than just Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The absolute URI to check. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | The Type to return. |

### Return Value

**true** if the Type is supported; otherwise, **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)
