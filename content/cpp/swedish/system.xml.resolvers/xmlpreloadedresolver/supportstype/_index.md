---
title: SupportsType()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om resolvern stöder andra Types än bara Stream.
type: docs
weight: 66
url: /sv/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) method


Avgör om resolvern stöder andra Types än bara Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Den absoluta URI:n att kontrollera. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Den Type att returnera. |

### Returvärde

**true** om Type är stödd; annars **false**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Uri](../../../system/uri/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [XmlPreloadedResolver](../)
* Namnrymd [System::Xml::Resolvers](../../)
* Bibliotek [Aspose.Slides](../../../)