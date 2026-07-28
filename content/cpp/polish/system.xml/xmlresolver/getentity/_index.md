---
title: GetEntity()
second_title: Aspose.Slides dla C++ Referencja API
description: Gdy jest przesłonięta w klasie pochodnej, mapuje URI na obiekt zawierający rzeczywisty zasób.
type: docs
weight: 14
url: /pl/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metoda

Gdy jest przesłonięta w klasie pochodnej, mapuje URI na obiekt zawierający rzeczywisty zasób.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI zwrócone z wywołania [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | Obecnie nie używane. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Typ obiektu do zwrócenia. Aktualna wersja zwraca tylko obiekty Stream. |

## Wartość zwracana

Obiekt stream lub **nullptr**, jeśli określono typ inny niż stream.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [Uri](../../../system/uri/)
* Klasa [String](../../../system/string/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [XmlResolver](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)