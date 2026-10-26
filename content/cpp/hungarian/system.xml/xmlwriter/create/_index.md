---
title: Create()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza az új XmlWriter példányt a megadott fájlnév alapján.
type: docs
weight: 469
url: /hu/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) method

Létrehoz egy új [XmlWriter](../) példányt a megadott fájlnév felhasználásával.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | A fájl, ahová írni szeretne. A [XmlWriter](../) a megadott útvonalon fájlt hoz létre, és XML 1.0 szövegszintaxisban ír bele. A **outputFileName** fájlrendszeri útvonal kell legyen. |

### Visszatérési érték

Egy [XmlWriter](../) objektum.

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) method

Létrehoz egy új [XmlWriter](../) példányt a fájlnév és a [XmlWriterSettings](../../xmlwritersettings/) objektum használatával.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | A fájl, ahová írni szeretne. A [XmlWriter](../) a megadott útvonalon fájlt hoz létre, és XML 1.0 szövegszintaxisban ír bele. A **outputFileName** fájlrendszeri útvonal kell legyen. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | A [XmlWriterSettings](../../xmlwritersettings/) objektum a új [XmlWriter](../) példány konfigurálására szolgál. Ha ez **nullptr**, egy alapértelmezett beállításokkal rendelkező [XmlWriterSettings](../../xmlwritersettings/) kerül használatra. Ha a [XmlWriter](../) a XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) metódussal van használva, akkor a XslCompiledTransform::get_OutputSettings értékkel kell egy [XmlWriterSettings](../../xmlwritersettings/) objektumot beszerezni a helyes beállításokkal. Ez biztosítja, hogy a létrehozott [XmlWriter](../) objektumnak a megfelelő kimeneti beállításai legyenek. |

### Visszatérési érték

Egy [XmlWriter](../) objektum.

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) method

Létrehoz egy új [XmlWriter](../) példányt a megadott adatfolyam használatával.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Az adatfolyam, ahová írni szeretne. A [XmlWriter](../) XML 1.0 szövegszintaxist ír, és hozzáfűzi a megadott adatfolyamhoz. |

### Visszatérési érték

Egy [XmlWriter](../) objektum.

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) method

Létrehoz egy új [XmlWriter](../) példányt az adatfolyam és a [XmlWriterSettings](../../xmlwritersettings/) objektum használatával.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Az adatfolyam, ahová írni szeretne. A [XmlWriter](../) XML 1.0 szövegszintaxist ír, és hozzáfűzi a megadott adatfolyamhoz. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | A [XmlWriterSettings](../../xmlwritersettings/) objektum a új [XmlWriter](../) példány konfigurálására szolgál. Ha ez **nullptr**, egy alapértelmezett beállításokkal rendelkező [XmlWriterSettings](../../xmlwritersettings/) kerül használatra. Ha a [XmlWriter](../) a XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) metódussal van használva, akkor a XslCompiledTransform::get_OutputSettings értékkel kell egy [XmlWriterSettings](../../xmlwritersettings/) objektumot beszerezni a helyes beállításokkal. Ez biztosítja, hogy a létrehozott [XmlWriter](../) objektumnak a megfelelő kimeneti beállításai legyenek. |

### Visszatérési érték

Egy [XmlWriter](../) objektum.

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) method

Létrehoz egy új [XmlWriter](../) példányt a megadott TextWriter használatával.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | A TextWriter, ahová írni szeretne. A [XmlWriter](../) XML 1.0 szövegszintaxist ír, és hozzáfűzi a megadott TextWriterhez. |

### Visszatérési érték

Egy [XmlWriter](../) objektum.

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) method

Létrehoz egy új [XmlWriter](../) példányt a TextWriter és a [XmlWriterSettings](../../xmlwritersettings/) objektumok használatával.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | A TextWriter, ahová írni szeretne. A [XmlWriter](../) XML 1.0 szövegszintaxist ír, és hozzáfűzi a megadott TextWriterhez. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | A [XmlWriterSettings](../../xmlwritersettings/) objektum a új [XmlWriter](../) példány konfigurálására szolgál. Ha ez **nullptr**, egy alapértelmezett beállításokkal rendelkező [XmlWriterSettings](../../xmlwritersettings/) kerül használatra. Ha a [XmlWriter](../) a XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) metódussal van használva, akkor a XslCompiledTransform::get_OutputSettings értékkel kell egy [XmlWriterSettings](../../xmlwritersettings/) objektumot beszerezni a helyes beállításokkal. Ez biztosítja, hogy a létrehozott [XmlWriter](../) objektumnak a megfelelő kimeneti beállításai legyenek. |

### Visszatérési érték

Egy [XmlWriter](../) objektum.

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) method

Létrehoz egy új [XmlWriter](../) példányt a megadott [Text::StringBuilder](../../../system.text/stringbuilder/) használatával.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | A [Text::StringBuilder](../../../system.text/stringbuilder/) ahová írni szeretne. A [XmlWriter](../) által írt tartalom hozzáadódik a [Text::StringBuilder](../../../system.text/stringbuilder/)-hez. |

### Visszatérési érték

Egy [XmlWriter](../) objektum.

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) method

Létrehoz egy új [XmlWriter](../) példányt a [Text::StringBuilder](../../../system.text/stringbuilder/) és [XmlWriterSettings](../../xmlwritersettings/) objektumok használatával.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | A [Text::StringBuilder](../../../system.text/stringbuilder/) ahová írni szeretne. A [XmlWriter](../) által írt tartalom hozzáfűződik a [Text::StringBuilder](../../../system.text/stringbuilder/)-hez. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | A [XmlWriterSettings](../../xmlwritersettings/) objektum a új [XmlWriter](../) példány konfigurálására szolgál. Ha ez **nullptr**, egy alapértelmezett beállításokkal rendelkező [XmlWriterSettings](../../xmlwritersettings/) kerül használatra. Ha a [XmlWriter](../) a XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) metódussal van használva, akkor a XslCompiledTransform::get_OutputSettings értékkel kell egy [XmlWriterSettings](../../xmlwritersettings/) objektumot beszerezni a helyes beállításokkal. Ez biztosítja, hogy a létrehozott [XmlWriter](../) objektumnak a megfelelő kimeneti beállításai legyenek. |

### Visszatérési érték

Egy [XmlWriter](../) objektum.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) method

Létrehoz egy új [XmlWriter](../) példányt a megadott [XmlWriter](../) objektum használatával.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | A [XmlWriter](../) objektum, amelyet az alapszintű íróként szeretne használni. |

### Visszatérési érték

Egy [XmlWriter](../) objektum, amely a megadott [XmlWriter](../) objektum köré van csomagolva.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) method

Létrehoz egy új [XmlWriter](../) példányt a megadott [XmlWriter](../) és [XmlWriterSettings](../../xmlwritersettings/) objektumok használatával.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | A [XmlWriter](../) objektum, amelyet az alapszintű íróként szeretne használni. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | A [XmlWriterSettings](../../xmlwritersettings/) objektum a új [XmlWriter](../) példány konfigurálására szolgál. Ha ez **nullptr**, egy alapértelmezett beállításokkal rendelkező [XmlWriterSettings](../../xmlwritersettings/) kerül használatra. Ha a [XmlWriter](../) a XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) metódussal van használva, akkor a XslCompiledTransform::get_OutputSettings értékkel kell egy [XmlWriterSettings](../../xmlwritersettings/) objektumot beszerezni a helyes beállításokkal. Ez biztosítja, hogy a létrehozott [XmlWriter](../) objektumnak a megfelelő kimeneti beállításai legyenek. |

### Visszatérési érték

Egy [XmlWriter](../) objektum, amely a megadott [XmlWriter](../) objektum köré van csomagolva.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlWriter](../)
* Osztály [String](../../../system/string/)
* Osztály [XmlWriterSettings](../../xmlwritersettings/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [TextWriter](../../../system.io/textwriter/)
* Osztály [StringBuilder](../../../system.text/stringbuilder/)
* Névtere [System::Xml](../../)
* Library [Aspose.Slides](../../../)