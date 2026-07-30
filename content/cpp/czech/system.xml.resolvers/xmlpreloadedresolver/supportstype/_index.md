---
title: SupportsType()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Určuje, zda resolver podporuje jiné typy než jen Stream.
type: docs
weight: 66
url: /cs/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) metoda

Určuje, zda resolver podporuje jiné typy než jen Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Absolutní URI ke kontrole. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Typ, který má být vrácen. |

### Návratová hodnota

**true** if the Type is supported; otherwise, **false**.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Uri](../../../system/uri/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [XmlPreloadedResolver](../)
* Jmenný prostor [System::Xml::Resolvers](../../)
* Knihovna [Aspose.Slides](../../../)