---
title: GetEntity()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Mapuje identyfikator URI na obiekt zawierający rzeczywisty zasób.
type: docs
weight: 53
url: /pl/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method

Mapuje identyfikator URI na obiekt zawierający rzeczywisty zasób.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Identyfikator URI zwrócony z wywołania [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Obecnie nie używany. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Typ zwracanego obiektu. [XmlPreloadedResolver](../) obsługuje obiekty Stream oraz obiekty TextReader dla identyfikatorów URI, które zostały dodane jako [String](../../../system/string/). Jeśli żądany typ nie jest obsługiwany przez resolver, zostanie rzucony wyjątek. Użyj metody XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo), aby określić, czy określony **Type** jest obsługiwany przez ten resolver. |

### Wartość zwracana

Obiekt Stream lub TextReader odpowiadający rzeczywistemu źródłu.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [Uri](../../../system/uri/)
* Klasa [String](../../../system/string/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [XmlPreloadedResolver](../)
* Przestrzeń nazw [System::Xml::Resolvers](../../)
* Biblioteka [Aspose.Slides](../../../)