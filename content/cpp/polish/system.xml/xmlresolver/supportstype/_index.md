---
title: SupportsType()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Umożliwia resolverowi zwracanie typów innych niż Stream.
type: docs
weight: 40
url: /pl/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) metoda


Umożliwia resolverowi zwracanie typów innych niż Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Adres URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Typ do zwrócenia. |

### Wartość zwracana

**true** jeśli **type** jest obsługiwany; w przeciwnym razie **false**.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Uri](../../../system/uri/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [XmlResolver](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)