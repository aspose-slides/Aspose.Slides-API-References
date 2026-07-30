---
title: Create()
second_title: Aspose.Slides pro C++ - reference API
description: Vytvoří novou instanci XmlWriter pomocí zadaného názvu souboru.
type: docs
weight: 469
url: /cs/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) metoda

Vytvoří novou instanci [XmlWriter](../) pomocí zadaného názvu souboru.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Soubor, do kterého chcete zapisovat. [XmlWriter](../) vytvoří soubor na zadané cestě a zapíše do něj text v syntaxi XML 1.0. **outputFileName** musí být cesta v souborovém systému. |

### Návratová hodnota

Objekt [XmlWriter](../).

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) metoda

Vytvoří novou instanci [XmlWriter](../) pomocí názvu souboru a objektu [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Soubor, do kterého chcete zapisovat. [XmlWriter](../) vytvoří soubor na zadané cestě a zapíše do něj text v syntaxi XML 1.0. **outputFileName** musí být cesta v souborovém systému. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Objekt [XmlWriterSettings](../../xmlwritersettings/) používaný k nastavení nové instance [XmlWriter](../). Pokud je tato hodnota **nullptr**, použije se [XmlWriterSettings](../../xmlwritersettings/) s výchozím nastavením. Pokud je [XmlWriter](../) používán s metodou XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) , měli byste použít hodnotu XslCompiledTransform::get_OutputSettings k získání objektu [XmlWriterSettings](../../xmlwritersettings/) se správným nastavením. To zajišťuje, že vytvořený objekt [XmlWriter](../) má správné výstupní nastavení. |

### Návratová hodnota

Objekt [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) metoda

Vytvoří novou instanci [XmlWriter](../) pomocí zadaného proudu.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Proud, do kterého chcete zapisovat. [XmlWriter](../) zapisuje text v syntaxi XML 1.0 a připojuje jej k zadanému proudu. |

### Návratová hodnota

Objekt [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) metoda

Vytvoří novou instanci [XmlWriter](../) pomocí proudu a objektu [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Proud, do kterého chcete zapisovat. [XmlWriter](../) zapisuje text v syntaxi XML 1.0 a připojuje jej k zadanému proudu. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Objekt [XmlWriterSettings](../../xmlwritersettings/) používaný k nastavení nové instance [XmlWriter](../). Pokud je tato hodnota **nullptr**, použije se [XmlWriterSettings](../../xmlwritersettings/) s výchozím nastavením. Pokud je [XmlWriter](../) používán s metodou XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) , měli byste použít hodnotu XslCompiledTransform::get_OutputSettings k získání objektu [XmlWriterSettings](../../xmlwritersettings/) se správným nastavením. To zajišťuje, že vytvořený objekt [XmlWriter](../) má správné výstupní nastavení. |

### Návratová hodnota

Objekt [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) metoda

Vytvoří novou instanci [XmlWriter](../) pomocí zadaného TextWriteru.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do kterého chcete zapisovat. [XmlWriter](../) zapisuje text v syntaxi XML 1.0 a připojuje jej k zadanému TextWriteru. |

### Návratová hodnota

Objekt [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) metoda

Vytvoří novou instanci [XmlWriter](../) pomocí TextWriteru a objektů [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do kterého chcete zapisovat. [XmlWriter](../) zapisuje text v syntaxi XML 1.0 a připojuje jej k zadanému TextWriteru. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Objekt [XmlWriterSettings](../../xmlwritersettings/) používaný k nastavení nové instance [XmlWriter](../). Pokud je tato hodnota **nullptr**, použije se [XmlWriterSettings](../../xmlwritersettings/) s výchozím nastavením. Pokud je [XmlWriter](../) používán s metodou XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) , měli byste použít hodnotu XslCompiledTransform::get_OutputSettings k získání objektu [XmlWriterSettings](../../xmlwritersettings/) se správným nastavením. To zajišťuje, že vytvořený objekt [XmlWriter](../) má správné výstupní nastavení. |

### Návratová hodnota

Objekt [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) metoda

Vytvoří novou instanci [XmlWriter](../) pomocí zadaného [Text::StringBuilder](../../../system.text/stringbuilder/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/), do kterého zapisovat. Obsah zapsaný [XmlWriter](../) je připojen k [Text::StringBuilder](../../../system.text/stringbuilder/). |

### Návratová hodnota

Objekt [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) metoda

Vytvoří novou instanci [XmlWriter](../) pomocí objektů [Text::StringBuilder](../../../system.text/stringbuilder/) a [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/), do kterého zapisovat. Obsah zapsaný [XmlWriter](../) je připojen k [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Objekt [XmlWriterSettings](../../xmlwritersettings/) používaný k nastavení nové instance [XmlWriter](../). Pokud je tato hodnota **nullptr**, použije se [XmlWriterSettings](../../xmlwritersettings/) s výchozím nastavením. Pokud je [XmlWriter](../) používán s metodou XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) , měli byste použít hodnotu XslCompiledTransform::get_OutputSettings k získání objektu [XmlWriterSettings](../../xmlwritersettings/) se správným nastavením. To zajišťuje, že vytvořený objekt [XmlWriter](../) má správné výstupní nastavení. |

### Návratová hodnota

Objekt [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) metoda

Vytvoří novou instanci [XmlWriter](../) pomocí zadaného objektu [XmlWriter](../).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | Objekt [XmlWriter](../), který chcete použít jako podkladový zapisovač. |

### Návratová hodnota

Objekt [XmlWriter](../), který je zabalený kolem zadaného objektu [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) metoda

Vytvoří novou instanci [XmlWriter](../) pomocí zadaných objektů [XmlWriter](../) a [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | Objekt [XmlWriter](../), který chcete použít jako podkladový zapisovač. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Objekt [XmlWriterSettings](../../xmlwritersettings/) používaný k nastavení nové instance [XmlWriter](../). Pokud je tato hodnota **nullptr**, použije se [XmlWriterSettings](../../xmlwritersettings/) s výchozím nastavením. Pokud je [XmlWriter](../) používán s metodou XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) , měli byste použít hodnotu XslCompiledTransform::get_OutputSettings k získání objektu [XmlWriterSettings](../../xmlwritersettings/) se správným nastavením. To zajišťuje, že vytvořený objekt [XmlWriter](../) má správné výstupní nastavení. |

### Návratová hodnota

Objekt [XmlWriter](../), který je zabalený kolem zadaného objektu [XmlWriter](../).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlWriter](../)
* Třída [String](../../../system/string/)
* Třída [XmlWriterSettings](../../xmlwritersettings/)
* Třída [Stream](../../../system.io/stream/)
* Třída [TextWriter](../../../system.io/textwriter/)
* Třída [StringBuilder](../../../system.text/stringbuilder/)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)