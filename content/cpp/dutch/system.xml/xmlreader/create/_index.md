---
title: Create()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw XmlReader object aan met de opgegeven URI.
type: docs
weight: 1015
url: /nl/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) methode


Maakt een nieuw [XmlReader](../)-object met de opgegeven URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | De URI voor het bestand dat de XML-gegevens bevat. De [XmlUrlResolver](../../xmlurlresolver/)-klasse wordt gebruikt om het pad naar een canonieke gegevensrepresentatie te converteren. |

### Retourwaarde

Een object dat wordt gebruikt om de XML-gegevens in de stream te lezen.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) methode


Maakt een nieuw [XmlReader](../)-object aan met de opgegeven URI en instellingen.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | De URI voor het bestand dat de XML-gegevens bevat. Het [XmlResolver](../../xmlresolver/)-object op het [XmlReaderSettings](../../xmlreadersettings/)-object wordt gebruikt om het pad naar een canonieke gegevensrepresentatie te converteren. Als de waarde van XmlReaderSettings::get_XmlResolver **nullptr** is, wordt een nieuw [XmlUrlResolver](../../xmlurlresolver/)-object gebruikt. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | De instellingen voor de nieuwe [XmlReader](../)-instantie. Deze waarde kan **nullptr** zijn. |

### Retourwaarde

Een object dat wordt gebruikt om de XML-gegevens in de stream te lezen.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) methode


Maakt een nieuw [XmlReader](../)-object aan met de opgegeven URI, instellingen en contextinformatie voor het parseren.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | De URI voor het bestand dat de XML-gegevens bevat. Het [XmlResolver](../../xmlresolver/)-object op het [XmlReaderSettings](../../xmlreadersettings/)-object wordt gebruikt om het pad naar een canonieke gegevensrepresentatie te converteren. Als de waarde van XmlReaderSettings::get_XmlResolver **nullptr** is, wordt een nieuw [XmlUrlResolver](../../xmlurlresolver/)-object gebruikt. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | De instellingen voor de nieuwe [XmlReader](../)-instantie. Deze waarde kan **nullptr** zijn. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | De contextinformatie die nodig is om het XML-fragment te parseren. De contextinformatie kan de [XmlNameTable](../../xmlnametable/) bevatten die moet worden gebruikt, codering, namespace-bereik, de huidige **xml:lang**- en **xml:space**-scope, basis-URI en documenttype-definitie. Deze waarde kan **nullptr** zijn. |

### Retourwaarde

Een object dat wordt gebruikt om de XML-gegevens in de stream te lezen.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) methode


Maakt een nieuw [XmlReader](../)-object aan met de opgegeven stream en standaardinstellingen.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream die de XML-gegevens bevat. De [XmlReader](../) scant de eerste bytes van de stream op een byte-order-markering of ander teken van codering. Zodra de codering is vastgesteld, wordt deze gebruikt om de stream verder te lezen, en wordt de verwerking voortgezet door de invoer te parseren als een stroom van (Unicode)-tekens. |

### Retourwaarde

Een object dat wordt gebruikt om de XML-gegevens in de stream te lezen.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) methode


Maakt een nieuw [XmlReader](../)-object aan met de opgegeven stream en instellingen.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream die de XML-gegevens bevat. De [XmlReader](../) scant de eerste bytes van de stream op een byte-order-markering of ander teken van codering. Zodra de codering is vastgesteld, wordt deze gebruikt om de stream verder te lezen, en wordt de verwerking voortgezet door de invoer te parseren als een stroom van (Unicode)-tekens. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | De instellingen voor de nieuwe [XmlReader](../)-instantie. Deze waarde kan **nullptr** zijn. |

### Retourwaarde

Een object dat wordt gebruikt om de XML-gegevens in de stream te lezen.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) methode


Maakt een nieuw [XmlReader](../)-object aan met de opgegeven stream, basis-URI en instellingen.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream die de XML-gegevens bevat. De [XmlReader](../) scant de eerste bytes van de stream op een byte-order-markering of ander teken van codering. Zodra de codering is vastgesteld, wordt deze gebruikt om de stream verder te lezen, en wordt de verwerking voortgezet door de invoer te parseren als een stroom van (Unicode)-tekens. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | De instellingen voor de nieuwe [XmlReader](../)-instantie. Deze waarde kan **nullptr** zijn. |
| baseUri | const [String](../../../system/string/)\& | De basis-URI voor de entiteit of het document dat wordt gelezen. Deze waarde kan **nullptr** zijn. **[Security](../../../system.security/) Opmerking** De basis-URI wordt gebruikt om de relatieve URI van het XML-document op te lossen. Gebruik geen basis-URI van een niet-vertrouwde bron. |

### Retourwaarde

Een object dat wordt gebruikt om de XML-gegevens in de stream te lezen.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) methode


Maakt een nieuw [XmlReader](../)-object aan met de opgegeven stream, instellingen en contextinformatie voor het parseren.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream die de XML-gegevens bevat. De [XmlReader](../) scant de eerste bytes van de stream op een byte-order-markering of ander teken van codering. Zodra de codering is vastgesteld, wordt deze gebruikt om de stream verder te lezen, en wordt de verwerking voortgezet door de invoer te parseren als een stroom van (Unicode)-tekens. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | De instellingen voor de nieuwe [XmlReader](../)-instantie. Deze waarde kan **nullptr** zijn. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | De contextinformatie die nodig is om het XML-fragment te parseren. De contextinformatie kan de [XmlNameTable](../../xmlnametable/) bevatten die moet worden gebruikt, codering, namespace-bereik, de huidige **xml:lang**- en **xml:space**-scope, basis-URI en documenttype-definitie. Deze waarde kan **nullptr** zijn. |

### Retourwaarde

Een object dat wordt gebruikt om de XML-gegevens in de stream te lezen.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) methode


Maakt een nieuw [XmlReader](../)-object aan met de opgegeven tekstlezer.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | De tekstlezer waaruit de XML-gegevens worden gelezen. Een tekstlezer levert een stroom van Unicode-tekens, waardoor de in de XML-declaratie opgegeven codering niet door de XML-lezer wordt gebruikt om de gegevensstroom te decoderen. |

### Retourwaarde

Een object dat wordt gebruikt om de XML-gegevens in de stream te lezen.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) methode


Maakt een nieuw [XmlReader](../)-object aan met de opgegeven tekstlezer en instellingen.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | De tekstlezer waaruit de XML-gegevens worden gelezen. Een tekstlezer levert een stroom van Unicode-tekens, waardoor de in de XML-declaratie opgegeven codering niet door de XML-lezer wordt gebruikt om de gegevensstroom te decoderen. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | De instellingen voor de nieuwe [XmlReader](../). Deze waarde kan **nullptr** zijn. |

### Retourwaarde

Een object dat wordt gebruikt om de XML-gegevens in de stream te lezen.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) methode


Maakt een nieuw [XmlReader](../)-object aan met de opgegeven tekstlezer, instellingen en basis-URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | De tekstlezer waaruit de XML-gegevens worden gelezen. Een tekstlezer levert een stroom van Unicode-tekens, waardoor de in de XML-declaratie opgegeven codering niet door de [XmlReader](../) wordt gebruikt om de gegevensstroom te decoderen. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | De instellingen voor de nieuwe [XmlReader](../)-instantie. Deze waarde kan **nullptr** zijn. |
| baseUri | const [String](../../../system/string/)\& | De basis-URI voor de entiteit of het document dat wordt gelezen. Deze waarde kan **nullptr** zijn. **[Security](../../../system.security/) Opmerking** De basis-URI wordt gebruikt om de relatieve URI van het XML-document op te lossen. Gebruik geen basis-URI van een niet-vertrouwde bron. |

### Retourwaarde

Een object dat wordt gebruikt om de XML-gegevens in de stream te lezen.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) methode


Maakt een nieuw [XmlReader](../)-object aan met de opgegeven tekstlezer, instellingen en contextinformatie voor het parseren.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | De tekstlezer waaruit de XML-gegevens worden gelezen. Een tekstlezer levert een stroom van Unicode-tekens, waardoor de in de XML-declaratie opgegeven codering niet door de XML-lezer wordt gebruikt om de gegevensstroom te decoderen. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | De instellingen voor de nieuwe [XmlReader](../)-instantie. Deze waarde kan **nullptr** zijn. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | De contextinformatie die nodig is om het XML-fragment te parseren. De contextinformatie kan de [XmlNameTable](../../xmlnametable/) bevatten die moet worden gebruikt, codering, namespace-bereik, de huidige **xml:lang**- en **xml:space**-scope, basis-URI en documenttype-definitie. Deze waarde kan **nullptr** zijn. |

### Retourwaarde

Een object dat wordt gebruikt om de XML-gegevens in de stream te lezen.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) methode


Maakt een nieuw [XmlReader](../)-object aan met de opgegeven XML-lezer en instellingen.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | Het object dat u wilt gebruiken als onderliggende XML-lezer. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | De instellingen voor de nieuwe [XmlReader](../)-instantie. Het conformiteitsniveau van het [XmlReaderSettings](../../xmlreadersettings/)-object moet ofwel overeenkomen met het conformiteitsniveau van de onderliggende lezer, of moet worden ingesteld op [ConformanceLevel::Auto](../../conformancelevel/). |

### Retourwaarde

Een object dat is gewikkeld rond het opgegeven [XmlReader](../)-object.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlReader](../)
* Klasse [String](../../../system/string/)
* Klasse [XmlReaderSettings](../../xmlreadersettings/)
* Klasse [XmlParserContext](../../xmlparsercontext/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [TextReader](../../../system.io/textreader/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)