---
title: SupportsType()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Umožňuje resolveru vracet typy jiné než Stream.
type: docs
weight: 40
url: /cs/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) metoda

Umožňuje resolveru vracet typy jiné než Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Typ, který má být vrácen. |

### Návratová hodnota

**true** pokud **type** je podporován; jinak **false**.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)