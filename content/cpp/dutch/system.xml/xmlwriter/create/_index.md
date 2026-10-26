---
title: Create()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuwe XmlWriter instantie aan met de opgegeven bestandsnaam.
type: docs
weight: 469
url: /nl/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) methode


Maakt een nieuwe [XmlWriter](../)-instantie aan met de opgegeven bestandsnaam.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Het bestand waarnaar u wilt schrijven. De [XmlWriter](../) maakt een bestand op het opgegeven pad aan en schrijft er in XML 1.0-tekstsyntaxis naar. De **outputFileName** moet een pad op het bestandssysteem zijn. |

### Retourwaarde

Een [XmlWriter](../)-object.

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) methode


Maakt een nieuwe [XmlWriter](../)-instantie aan met de bestandsnaam en het [XmlWriterSettings](../../xmlwritersettings/)-object.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Het bestand waarnaar u wilt schrijven. De [XmlWriter](../) maakt een bestand op het opgegeven pad aan en schrijft er in XML 1.0-tekstsyntaxis naar. De **outputFileName** moet een pad op het bestandssysteem zijn. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Het [XmlWriterSettings](../../xmlwritersettings/)-object dat wordt gebruikt om de nieuwe [XmlWriter](../)-instantie te configureren. Als dit **nullptr** is, wordt een [XmlWriterSettings](../../xmlwritersettings/) met standaardinstellingen gebruikt. Als de [XmlWriter](../) wordt gebruikt met de XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) methode, moet u de XslCompiledTransform::get_OutputSettings-waarde gebruiken om een [XmlWriterSettings](../../xmlwritersettings/)-object met de juiste instellingen te verkrijgen. Dit zorgt ervoor dat het aangemaakte [XmlWriter](../)-object de juiste uitvoerinstellingen heeft. |

### Retourwaarde

Een [XmlWriter](../)-object.

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) methode


Maakt een nieuwe [XmlWriter](../)-instantie aan met de opgegeven stream.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream waarnaar u wilt schrijven. De [XmlWriter](../) schrijft XML 1.0-tekstsyntaxis en voegt deze toe aan de opgegeven stream. |

### Retourwaarde

Een [XmlWriter](../)-object.

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) methode


Maakt een nieuwe [XmlWriter](../)-instantie aan met de stream en het [XmlWriterSettings](../../xmlwritersettings/)-object.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream waarnaar u wilt schrijven. De [XmlWriter](../) schrijft XML 1.0-tekstsyntaxis en voegt deze toe aan de opgegeven stream. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Het [XmlWriterSettings](../../xmlwritersettings/)-object dat wordt gebruikt om de nieuwe [XmlWriter](../)-instantie te configureren. Als dit **nullptr** is, wordt een [XmlWriterSettings](../../xmlwritersettings/) met standaardinstellingen gebruikt. Als de [XmlWriter](../) wordt gebruikt met de XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) methode, moet u de XslCompiledTransform::get_OutputSettings-waarde gebruiken om een [XmlWriterSettings](../../xmlwritersettings/)-object met de juiste instellingen te verkrijgen. Dit zorgt ervoor dat het aangemaakte [XmlWriter](../)-object de juiste uitvoerinstellingen heeft. |

### Retourwaarde

Een [XmlWriter](../)-object.

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) methode


Maakt een nieuwe [XmlWriter](../)-instantie aan met de opgegeven TextWriter.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | De TextWriter waarnaar u wilt schrijven. De [XmlWriter](../) schrijft XML 1.0-tekstsyntaxis en voegt deze toe aan de opgegeven TextWriter. |

### Retourwaarde

Een [XmlWriter](../)-object.

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) methode


Maakt een nieuwe [XmlWriter](../)-instantie aan met de TextWriter en de [XmlWriterSettings](../../xmlwritersettings/)-objecten.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | De TextWriter waarnaar u wilt schrijven. De [XmlWriter](../) schrijft XML 1.0-tekstsyntaxis en voegt deze toe aan de opgegeven TextWriter. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Het [XmlWriterSettings](../../xmlwritersettings/)-object dat wordt gebruikt om de nieuwe [XmlWriter](../)-instantie te configureren. Als dit **nullptr** is, wordt een [XmlWriterSettings](../../xmlwritersettings/) met standaardinstellingen gebruikt. Als de [XmlWriter](../) wordt gebruikt met de XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) methode, moet u de XslCompiledTransform::get_OutputSettings-waarde gebruiken om een [XmlWriterSettings](../../xmlwritersettings/)-object met de juiste instellingen te verkrijgen. Dit zorgt ervoor dat het aangemaakte [XmlWriter](../)-object de juiste uitvoerinstellingen heeft. |

### Retourwaarde

Een [XmlWriter](../)-object.

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) methode


Maakt een nieuwe [XmlWriter](../)-instantie aan met de opgegeven [Text::StringBuilder](../../../system.text/stringbuilder/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | De [Text::StringBuilder](../../../system.text/stringbuilder/) waarnaar geschreven moet worden. Inhoud die door de [XmlWriter](../) wordt geschreven, wordt toegevoegd aan de [Text::StringBuilder](../../../system.text/stringbuilder/). |

### Retourwaarde

Een [XmlWriter](../)-object.

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) methode


Maakt een nieuwe [XmlWriter](../)-instantie aan met de [Text::StringBuilder](../../../system.text/stringbuilder/)- en [XmlWriterSettings](../../xmlwritersettings/)-objecten.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | De [Text::StringBuilder](../../../system.text/stringbuilder/) waarnaar geschreven moet worden. Inhoud die door de [XmlWriter](../) wordt geschreven, wordt toegevoegd aan de [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Het [XmlWriterSettings](../../xmlwritersettings/)-object dat wordt gebruikt om de nieuwe [XmlWriter](../)-instantie te configureren. Als dit **nullptr** is, wordt een [XmlWriterSettings](../../xmlwritersettings/) met standaardinstellingen gebruikt. Als de [XmlWriter](../) wordt gebruikt met de XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) methode, moet u de XslCompiledTransform::get_OutputSettings-waarde gebruiken om een [XmlWriterSettings](../../xmlwritersettings/)-object met de juiste instellingen te verkrijgen. Dit zorgt ervoor dat het aangemaakte [XmlWriter](../)-object de juiste uitvoerinstellingen heeft. |

### Retourwaarde

Een [XmlWriter](../)-object.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) methode


Maakt een nieuwe [XmlWriter](../)-instantie aan met het opgegeven [XmlWriter](../)-object.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | Het [XmlWriter](../)-object dat u wilt gebruiken als onderliggende writer. |

### Retourwaarde

Een [XmlWriter](../)-object dat omhuld is rond het opgegeven [XmlWriter](../)-object.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) methode


Maakt een nieuwe [XmlWriter](../)-instantie aan met de opgegeven [XmlWriter](../)- en [XmlWriterSettings](../../xmlwritersettings/)-objecten.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | Het [XmlWriter](../)-object dat u wilt gebruiken als onderliggende writer. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Het [XmlWriterSettings](../../xmlwritersettings/)-object dat wordt gebruikt om de nieuwe [XmlWriter](../)-instantie te configureren. Als dit **nullptr** is, wordt een [XmlWriterSettings](../../xmlwritersettings/) met standaardinstellingen gebruikt. Als de [XmlWriter](../) wordt gebruikt met de XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) methode, moet u de XslCompiledTransform::get_OutputSettings-waarde gebruiken om een [XmlWriterSettings](../../xmlwritersettings/)-object met de juiste instellingen te verkrijgen. Dit zorgt ervoor dat het aangemaakte [XmlWriter](../)-object de juiste uitvoerinstellingen heeft. |

### Retourwaarde

Een [XmlWriter](../)-object dat omhuld is rond het opgegeven [XmlWriter](../)-object.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)