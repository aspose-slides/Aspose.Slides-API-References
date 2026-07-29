---
title: GetEntity()
second_title: Aspose.Slides för C++ API-referens
description: Mappar en URI till ett objekt som innehåller den faktiska resursen.
type: docs
weight: 27
url: /sv/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metod

Mappar en URI till ett objekt som innehåller den faktiska resursen.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI:n som returneras från [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/)-anropet. |
| role | [String](../../../system/string/) | För närvarande används den inte. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Typen av objekt som ska returneras. Den aktuella versionen returnerar endast Stream-objekt. |

### Returvärde

Strömmen som returneras genom att anropa **GetEntity** på den underliggande [XmlResolver](../../xmlresolver/). Om en annan typ än Stream anges returnerar metoden **nullptr**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [Uri](../../../system/uri/)
* Klass [String](../../../system/string/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [XmlSecureResolver](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)