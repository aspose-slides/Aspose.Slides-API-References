---
title: SupportsType()
second_title: Aspose.Slides för C++ API-referens
description: Aktiverar resolvern att returnera typer förutom Stream.
type: docs
weight: 40
url: /sv/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) metod

Aktiverar resolvern att returnera typer förutom Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI:n. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Typen att returnera. |

### Returvärde

**true** if the **type** is supported; otherwise, **false**.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Uri](../../../system/uri/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [XmlResolver](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)