---
title: GetEntity()
second_title: Aspose.Slides dla C++ Referencja API
description: Mapuje URI do obiektu, który zawiera rzeczywisty zasób.
type: docs
weight: 53
url: /pl/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metoda

Mapuje URI do obiektu, który zawiera rzeczywisty zasób.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI zwrócone z wywołania [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Obecnie nie używane. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Typ obiektu do zwrócenia. Obecna implementacja zwraca tylko obiekty Stream. |

### Wartość zwracana

Obiekt stream lub **nullptr**, jeśli określono typ inny niż stream.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [Uri](../../../system/uri/)
* Klasa [String](../../../system/string/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [XmlUrlResolver](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)