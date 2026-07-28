---
title: SupportsType()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa, czy resolver obsługuje inne typy niż tylko Stream.
type: docs
weight: 66
url: /pl/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) method

Określa, czy resolver obsługuje inne typy niż tylko Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Absolutny URI do sprawdzenia. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Typ do zwrócenia. |

### Wartość zwracana

**true** jeśli Typ jest obsługiwany; w przeciwnym razie **false**.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Uri](../../../system/uri/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [XmlPreloadedResolver](../)
* Przestrzeń nazw [System::Xml::Resolvers](../../)
* Biblioteka [Aspose.Slides](../../../)