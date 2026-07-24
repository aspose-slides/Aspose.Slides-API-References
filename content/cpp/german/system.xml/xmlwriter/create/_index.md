---
title: Create()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue XmlWriter-Instanz unter Verwendung des angegebenen Dateinamens.
type: docs
weight: 469
url: /de/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) Methode

Erstellt eine neue [XmlWriter](../) Instanz unter Verwendung des angegebenen Dateinamens.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```

### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Die Datei, in die Sie schreiben möchten. Der [XmlWriter](../) erstellt eine Datei am angegebenen Pfad und schreibt sie in XML-1.0-Textsyntax. **outputFileName** muss ein Dateisystempfad sein. |

### Rückgabewert

Ein [XmlWriter](../) Objekt.

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) Methode

Erstellt eine neue [XmlWriter](../) Instanz unter Verwendung des Dateinamens und des [XmlWriterSettings](../../xmlwritersettings/) Objekts.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```

### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Die Datei, in die Sie schreiben möchten. Der [XmlWriter](../) erstellt eine Datei am angegebenen Pfad und schreibt sie in XML-1.0-Textsyntax. **outputFileName** muss ein Dateisystempfad sein. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Das [XmlWriterSettings](../../xmlwritersettings/) Objekt, das verwendet wird, um die neue [XmlWriter](../) Instanz zu konfigurieren. Wenn dies **nullptr** ist, wird ein [XmlWriterSettings](../../xmlwritersettings/) mit Standardeinstellungen verwendet. Wenn [XmlWriter](../) mit der Methode XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) verwendet wird, sollten Sie den Wert XslCompiledTransform::get_OutputSettings verwenden, um ein [XmlWriterSettings](../../xmlwritersettings/) Objekt mit den korrekten Einstellungen zu erhalten. Dies stellt sicher, dass das erstellte [XmlWriter](../) Objekt die richtigen Ausgabeeinstellungen hat. |

### Rückgabewert

Ein [XmlWriter](../) Objekt.

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) Methode

Erstellt eine neue [XmlWriter](../) Instanz unter Verwendung des angegebenen Streams.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```

### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, in den Sie schreiben möchten. [XmlWriter](../) schreibt XML-1.0-Textsyntax und fügt sie dem angegebenen Stream hinzu. |

### Rückgabewert

Ein [XmlWriter](../) Objekt.

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) Methode

Erstellt eine neue [XmlWriter](../) Instanz unter Verwendung des Streams und des [XmlWriterSettings](../../xmlwritersettings/) Objekts.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```

### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, in den Sie schreiben möchten. [XmlWriter](../) schreibt XML-1.0-Textsyntax und fügt sie dem angegebenen Stream hinzu. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Das [XmlWriterSettings](../../xmlwritersettings/) Objekt, das verwendet wird, um die neue [XmlWriter](../) Instanz zu konfigurieren. Wenn dies **nullptr** ist, wird ein [XmlWriterSettings](../../xmlwritersettings/) mit Standardeinstellungen verwendet. Wenn [XmlWriter](../) mit der Methode XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) verwendet wird, sollten Sie den Wert XslCompiledTransform::get_OutputSettings verwenden, um ein [XmlWriterSettings](../../xmlwritersettings/) Objekt mit den korrekten Einstellungen zu erhalten. Dies stellt sicher, dass das erstellte [XmlWriter](../) Objekt die richtigen Ausgabeeinstellungen hat. |

### Rückgabewert

Ein [XmlWriter](../) Objekt.

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) Methode

Erstellt eine neue [XmlWriter](../) Instanz unter Verwendung des angegebenen TextWriter.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```

### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Der TextWriter, in den Sie schreiben möchten. [XmlWriter](../) schreibt XML-1.0-Textsyntax und fügt sie dem angegebenen TextWriter hinzu. |

### Rückgabewert

Ein [XmlWriter](../) Objekt.

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) Methode

Erstellt eine neue [XmlWriter](../) Instanz unter Verwendung des TextWriters und der [XmlWriterSettings](../../xmlwritersettings/) Objekte.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Der TextWriter, in den Sie schreiben möchten. [XmlWriter](../) schreibt XML-1.0-Textsyntax und fügt sie dem angegebenen TextWriter hinzu. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Das [XmlWriterSettings](../../xmlwritersettings/) Objekt, das verwendet wird, um die neue [XmlWriter](../) Instanz zu konfigurieren. Wenn dies **nullptr** ist, wird ein [XmlWriterSettings](../../xmlwritersettings/) mit Standardeinstellungen verwendet. Wenn [XmlWriter](../) mit der Methode XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) verwendet wird, sollten Sie den Wert XslCompiledTransform::get_OutputSettings verwenden, um ein [XmlWriterSettings](../../xmlwritersettings/) Objekt mit den korrekten Einstellungen zu erhalten. Dies stellt sicher, dass das erstellte [XmlWriter](../) Objekt die richtigen Ausgabeeinstellungen hat. |

### Rückgabewert

Ein [XmlWriter](../) Objekt.

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) Methode

Erstellt eine neue [XmlWriter](../) Instanz unter Verwendung des angegebenen [Text::StringBuilder](../../../system.text/stringbuilder/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```

### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Der [Text::StringBuilder](../../../system.text/stringbuilder/), in den geschrieben wird. Der vom [XmlWriter](../) geschriebene Inhalt wird an den [Text::StringBuilder](../../../system.text/stringbuilder/) angehängt. |

### Rückgabewert

Ein [XmlWriter](../) Objekt.

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) Methode

Erstellt eine neue [XmlWriter](../) Instanz unter Verwendung der [Text::StringBuilder](../../../system.text/stringbuilder/) und [XmlWriterSettings](../../xmlwritersettings/) Objekte.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```

### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Der [Text::StringBuilder](../../../system.text/stringbuilder/), in den geschrieben wird. Der vom [XmlWriter](../) geschriebene Inhalt wird an den [Text::StringBuilder](../../../system.text/stringbuilder/) angehängt. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Das [XmlWriterSettings](../../xmlwritersettings/) Objekt, das verwendet wird, um die neue [XmlWriter](../) Instanz zu konfigurieren. Wenn dies **nullptr** ist, wird ein [XmlWriterSettings](../../xmlwritersettings/) mit Standardeinstellungen verwendet. Wenn [XmlWriter](../) mit der Methode XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) verwendet wird, sollten Sie den Wert XslCompiledTransform::get_OutputSettings verwenden, um ein [XmlWriterSettings](../../xmlwritersettings/) Objekt mit den korrekten Einstellungen zu erhalten. Dies stellt sicher, dass das erstellte [XmlWriter](../) Objekt die richtigen Ausgabeeinstellungen hat. |

### Rückgabewert

Ein [XmlWriter](../) Objekt.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) Methode

Erstellt eine neue [XmlWriter](../) Instanz unter Verwendung des angegebenen [XmlWriter](../) Objekts.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```

### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | Das [XmlWriter](../) Objekt, das Sie als zugrunde liegenden Writer verwenden möchten. |

### Rückgabewert

Ein [XmlWriter](../) Objekt, das das angegebene [XmlWriter](../) Objekt umschließt.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) Methode

Erstellt eine neue [XmlWriter](../) Instanz unter Verwendung des angegebenen [XmlWriter](../) und [XmlWriterSettings](../../xmlwritersettings/) Objekts.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | Das [XmlWriter](../) Objekt, das Sie als zugrunde liegenden Writer verwenden möchten. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Das [XmlWriterSettings](../../xmlwritersettings/) Objekt, das verwendet wird, um die neue [XmlWriter](../) Instanz zu konfigurieren. Wenn dies **nullptr** ist, wird ein [XmlWriterSettings](../../xmlwritersettings/) mit Standardeinstellungen verwendet. Wenn [XmlWriter](../) mit der Methode XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) verwendet wird, sollten Sie den Wert XslCompiledTransform::get_OutputSettings verwenden, um ein [XmlWriterSettings](../../xmlwritersettings/) Objekt mit den korrekten Einstellungen zu erhalten. Dies stellt sicher, dass das erstellte [XmlWriter](../) Objekt die richtigen Ausgabeeinstellungen hat. |

### Rückgabewert

Ein [XmlWriter](../) Objekt, das das angegebene [XmlWriter](../) Objekt umschließt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlWriter](../)
* Klasse [String](../../../system/string/)
* Klasse [XmlWriterSettings](../../xmlwritersettings/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [TextWriter](../../../system.io/textwriter/)
* Klasse [StringBuilder](../../../system.text/stringbuilder/)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)