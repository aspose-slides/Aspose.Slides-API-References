---
title: GetEntity()
second_title: Aspose.Slides för C++ API-referens
description: Mappar en URI till ett objekt som innehåller den faktiska resursen.
type: docs
weight: 53
url: /sv/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metod


Mappar en URI till ett objekt som innehåller den faktiska resursen.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI:n som returnerats från [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/)-anropet. |
| role | [String](../../../system/string/) | För närvarande används den inte. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Typen av objekt som ska returneras. Den aktuella implementationen returnerar endast Stream-objekt. |

### Returvärde

Ett stream-objekt eller **nullptr** om en annan typ än stream specificeras.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [Uri](../../../system/uri/)
* Klass [String](../../../system/string/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [XmlUrlResolver](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)