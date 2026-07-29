---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en byte-array i XmlPreloadedResolver-lagret och mappar den till en URI. Om lagret redan innehåller en mappning för samma URI, åsidosätts den befintliga mappningen.
type: docs
weight: 79
url: /sv/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) metod

Lägger till en byte-array i [XmlPreloadedResolver](../)-lagret och mappar den till en URI. Om lagret redan innehåller en mappning för samma URI, åsidosätts den befintliga mappningen.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI:n för den data som läggs till i [XmlPreloadedResolver](../)-lagret. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | En byte-array med den data som motsvarar den angivna URI:n. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Lägger till en byte-array i [XmlPreloadedResolver](../)-lagret och mappar den till en URI. Om lagret redan innehåller en mappning för samma URI, åsidosätts den befintliga mappningen.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI:n för den data som läggs till i [XmlPreloadedResolver](../)-lagret. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | En byte-array med den data som motsvarar den angivna URI:n. |
| offset | **int32_t** | Offset i den angivna byte-arrayen där datan börjar. |
| count | **int32_t** | Antalet byte som ska läsas från byte-arrayen, med början vid det angivna offsetet. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) metod

Lägger till en Stream i [XmlPreloadedResolver](../)-lagret och mappar den till en URI. Om lagret redan innehåller en mappning för samma URI, åsidosätts den befintliga mappningen.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI:n för den data som läggs till i [XmlPreloadedResolver](../)-lagret. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | En Stream med den data som motsvarar den angivna URI:n. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) metod

Lägger till en sträng med förladdade data i [XmlPreloadedResolver](../)-lagret och mappar den till en URI. Om lagret redan innehåller en mappning för samma URI, åsidosätts den befintliga mappningen.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI:n för den data som läggs till i [XmlPreloadedResolver](../)-lagret. |
| value | const [String](../../../system/string/)\& | En [String](../../../system/string/) med den data som motsvarar den angivna URI:n. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)