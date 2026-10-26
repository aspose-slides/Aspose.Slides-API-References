---
title: GetEntity()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Mapuje identyfikator URI na obiekt zawierający rzeczywisty zasób.
type: docs
weight: 27
url: /pl/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metoda


Mapuje identyfikator URI na obiekt zawierający rzeczywisty zasób.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Identyfikator URI zwracany przez wywołanie [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | Obecnie nie używany. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Typ zwracanego obiektu. Obecna wersja zwraca wyłącznie obiekty typu Stream. |

### Wartość zwracana

Strumień zwrócony po wywołaniu **GetEntity** na bazowym [XmlResolver](../../xmlresolver/). Jeśli podano typ inny niż Stream, metoda zwraca **nullptr**.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [Uri](../../../system/uri/)
* Klasa [String](../../../system/string/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [XmlSecureResolver](../)
* Przestrzeń nazw [System::Xml](../../)
* Library [Aspose.Slides](../../../)