---
title: Create()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny XmlWriter-instans med det angivna filnamnet.
type: docs
weight: 469
url: /sv/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) metod


Skapar en ny [XmlWriter](../)-instans med den angivna filnamnet.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Filen som du vill skriva till. [XmlWriter](../) skapar en fil på den angivna sökvägen och skriver till den i XML 1.0-textsyntax. **outputFileName** måste vara en filsökväg. |

### Returvärde

Ett [XmlWriter](../)-objekt.

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) metod


Skapar en ny [XmlWriter](../)-instans med filnamnet och [XmlWriterSettings](../../xmlwritersettings/)-objektet.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Filen som du vill skriva till. [XmlWriter](../) skapar en fil på den angivna sökvägen och skriver till den i XML 1.0-textsyntax. **outputFileName** måste vara en filsökväg. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | [XmlWriterSettings](../../xmlwritersettings/)-objektet som används för att konfigurera den nya [XmlWriter](../)-instansen. Om detta är **nullptr** används ett [XmlWriterSettings](../../xmlwritersettings/) med standardinställningar. Om [XmlWriter](../) används med XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>)-metoden bör du använda XslCompiledTransform::get_OutputSettings-värdet för att erhålla ett [XmlWriterSettings](../../xmlwritersettings/)-objekt med rätt inställningar. Detta säkerställer att det skapade [XmlWriter](../)-objektet har rätt utdatainställningar. |

### Returvärde

Ett [XmlWriter](../)-objekt.

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) metod


Skapar en ny [XmlWriter](../)-instans med den angivna strömmen.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen som du vill skriva till. [XmlWriter](../) skriver XML 1.0-textsyntax och lägger till den i den angivna strömmen. |

### Returvärde

Ett [XmlWriter](../)-objekt.

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) metod


Skapar en ny [XmlWriter](../)-instans med strömmen och [XmlWriterSettings](../../xmlwritersettings/)-objektet.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen som du vill skriva till. [XmlWriter](../) skriver XML 1.0-textsyntax och lägger till den i den angivna strömmen. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | [XmlWriterSettings](../../xmlwritersettings/)-objektet som används för att konfigurera den nya [XmlWriter](../)-instansen. Om detta är **nullptr** används ett [XmlWriterSettings](../../xmlwritersettings/) med standardinställningar. Om [XmlWriter](../) används med XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>)-metoden bör du använda XslCompiledTransform::get_OutputSettings-värdet för att erhålla ett [XmlWriterSettings](../../xmlwritersettings/)-objekt med rätt inställningar. Detta säkerställer att det skapade [XmlWriter](../)-objektet har rätt utdatainställningar. |

### Returvärde

Ett [XmlWriter](../)-objekt.

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) metod


Skapar en ny [XmlWriter](../)-instans med den angivna TextWriter-en.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter-en som du vill skriva till. [XmlWriter](../) skriver XML 1.0-textsyntax och lägger till den i den angivna TextWriter-en. |

### Returvärde

Ett [XmlWriter](../)-objekt.

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) metod


Skapar en ny [XmlWriter](../)-instans med TextWriter-en och [XmlWriterSettings](../../xmlwritersettings/)-objekten.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter-en som du vill skriva till. [XmlWriter](../) skriver XML 1.0-textsyntax och lägger till den i den angivna TextWriter-en. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | [XmlWriterSettings](../../xmlwritersettings/)-objektet som används för att konfigurera den nya [XmlWriter](../)-instansen. Om detta är **nullptr** används ett [XmlWriterSettings](../../xmlwritersettings/) med standardinställningar. Om [XmlWriter](../) används med XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>)-metoden bör du använda XslCompiledTransform::get_OutputSettings-värdet för att erhålla ett [XmlWriterSettings](../../xmlwritersettings/)-objekt med rätt inställningar. Detta säkerställer att det skapade [XmlWriter](../)-objektet har rätt utdatainställningar. |

### Returvärde

Ett [XmlWriter](../)-objekt.

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) metod


Skapar en ny [XmlWriter](../)-instans med den angivna [Text::StringBuilder](../../../system.text/stringbuilder/)-en.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) som du vill skriva till. Innehållet som skrivs av [XmlWriter](../) läggs till i [Text::StringBuilder](../../../system.text/stringbuilder/). |

### Returvärde

Ett [XmlWriter](../)-objekt.

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) metod


Skapar en ny [XmlWriter](../)-instans med [Text::StringBuilder](../../../system.text/stringbuilder/)- och [XmlWriterSettings](../../xmlwritersettings/)-objekten.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) som du vill skriva till. Innehållet som skrivs av [XmlWriter](../) läggs till i [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | [XmlWriterSettings](../../xmlwritersettings/)-objektet som används för att konfigurera den nya [XmlWriter](../)-instansen. Om detta är **nullptr** används ett [XmlWriterSettings](../../xmlwritersettings/) med standardinställningar. Om [XmlWriter](../) används med XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>)-metoden bör du använda XslCompiledTransform::get_OutputSettings-värdet för att erhålla ett [XmlWriterSettings](../../xmlwritersettings/)-objekt med rätt inställningar. Detta säkerställer att det skapade [XmlWriter](../)-objektet har rätt utdatainställningar. |

### Returvärde

Ett [XmlWriter](../)-objekt.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) metod


Skapar en ny [XmlWriter](../)-instans med det angivna [XmlWriter](../)-objektet.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | [XmlWriter](../)-objektet som du vill använda som underliggande skribent. |

### Returvärde

Ett [XmlWriter](../)-objekt som omsluter det angivna [XmlWriter](../)-objektet.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) metod


Skapar en ny [XmlWriter](../)-instans med de angivna [XmlWriter](../)- och [XmlWriterSettings](../../xmlwritersettings/)-objekten.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | [XmlWriter](../)-objektet som du vill använda som underliggande skribent. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | [XmlWriterSettings](../../xmlwritersettings/)-objektet som används för att konfigurera den nya [XmlWriter](../)-instansen. Om detta är **nullptr** används ett [XmlWriterSettings](../../xmlwritersettings/) med standardinställningar. Om [XmlWriter](../) används med XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>)-metoden bör du använda XslCompiledTransform::get_OutputSettings-värdet för att erhålla ett [XmlWriterSettings](../../xmlwritersettings/)-objekt med rätt inställningar. Detta säkerställer att det skapade [XmlWriter](../)-objektet har rätt utdatainställningar. |

### Returvärde

Ett [XmlWriter](../)-objekt som omsluter det angivna [XmlWriter](../)-objektet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)