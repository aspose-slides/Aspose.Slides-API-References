---
title: SupportsType()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, поддерживает ли резольвер другие типы, помимо Stream.
type: docs
weight: 66
url: /ru/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) method


Определяет, поддерживает ли резольвер другие типы, помимо Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Абсолютный URI для проверки. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Type, который нужно вернуть. |

### Return Value

**true** если Type поддерживается; в противном случае **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)