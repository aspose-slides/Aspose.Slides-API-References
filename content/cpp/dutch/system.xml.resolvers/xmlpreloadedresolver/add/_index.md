---
title: Add()
second_title: Aspose.Slides voor C++ API Referentie
description: Voegt een byte-array toe aan de XmlPreloadedResolver-opslag en koppelt deze aan een URI. Als de opslag al een koppeling bevat voor dezelfde URI, wordt de bestaande koppeling overschreven.
type: docs
weight: 79
url: /nl/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) methode

Voegt een byte-array toe aan de [XmlPreloadedResolver](../) opslag en koppelt deze aan een URI. Als de opslag al een koppeling bevat voor dezelfde URI, wordt de bestaande koppeling overschreven.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | De URI van de gegevens die aan de [XmlPreloadedResolver](../) opslag wordt toegevoegd. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Een byte-array met de gegevens die overeenkomen met de opgegeven URI. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode

Voegt een byte-array toe aan de [XmlPreloadedResolver](../) opslag en koppelt deze aan een URI. Als de opslag al een koppeling bevat voor dezelfde URI, wordt de bestaande koppeling overschreven.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | De URI van de gegevens die aan de [XmlPreloadedResolver](../) opslag wordt toegevoegd. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Een byte-array met de gegevens die overeenkomen met de opgegeven URI. |
| offset | **int32_t** | Het offset in de opgegeven byte-array waar de gegevens beginnen. |
| count | **int32_t** | Het aantal bytes dat uit de byte-array moet worden gelezen, beginnend bij het opgegeven offset. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) methode

Voegt een Stream toe aan de [XmlPreloadedResolver](../) opslag en koppelt deze aan een URI. Als de opslag al een koppeling bevat voor dezelfde URI, wordt de bestaande koppeling overschreven.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | De URI van de gegevens die aan de [XmlPreloadedResolver](../) opslag wordt toegevoegd. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Een Stream met de gegevens die overeenkomen met de opgegeven URI. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) methode

Voegt een string met vooraf geladen gegevens toe aan de [XmlPreloadedResolver](../) opslag en koppelt deze aan een URI. Als de opslag al een koppeling bevat voor dezelfde URI, wordt de bestaande koppeling overschreven.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | De URI van de gegevens die aan de [XmlPreloadedResolver](../) opslag wordt toegevoegd. |
| value | const [String](../../../system/string/)\& | Een [String](../../../system/string/) met de gegevens die overeenkomen met de opgegeven URI. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [XmlPreloadedResolver](../)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)