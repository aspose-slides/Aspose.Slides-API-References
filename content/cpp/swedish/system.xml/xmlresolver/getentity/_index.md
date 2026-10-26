---
title: GetEntity()
second_title: Aspose.Slides för C++ API-referens
description: När den överskuggas i en härledd klass mappar den en URI till ett objekt som innehåller den faktiska resursen.
type: docs
weight: 14
url: /sv/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method

När den åsidosätts i en härledd klass mappar den en URI till ett objekt som innehåller den faktiska resursen.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI:n som returnerades från anropet [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | För närvarande används den inte. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Typen av objekt att returnera. Den nuvarande versionen returnerar endast Stream-objekt. |

### Returvärde

Ett strömmobjekt eller **nullptr** om en annan typ än ström anges.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [Uri](../../../system/uri/)
* Klass [String](../../../system/string/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [XmlResolver](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)