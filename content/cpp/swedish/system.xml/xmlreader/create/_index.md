---
title: Create()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny XmlReader-instans med angiven URI.
type: docs
weight: 1015
url: /sv/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) metod


Skapar en ny [XmlReader](../) instans med angiven URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI:n för filen som innehåller XML-data. Klassen [XmlUrlResolver](../../xmlurlresolver/) används för att konvertera sökvägen till en kanonisk datrepresentation. |

### Returvärde

Ett objekt som används för att läsa XML-data i strömmen.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) metod


Skapar en ny [XmlReader](../) instans genom att använda den angivna URI:n och inställningarna.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI:n för filen som innehåller XML-data. Objektet [XmlResolver](../../xmlresolver/) på objektet [XmlReaderSettings](../../xmlreadersettings/) används för att konvertera sökvägen till en kanonisk datrepresentation. Om värdet för XmlReaderSettings::get_XmlResolver är **nullptr**, används ett nytt [XmlUrlResolver](../../xmlurlresolver/)-objekt. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Inställningarna för den nya [XmlReader](../)-instansen. Detta värde kan vara **nullptr**. |

### Returvärde

Ett objekt som används för att läsa XML-data i strömmen.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metod


Skapar en ny [XmlReader](../) instans genom att använda den angivna URI:n, inställningarna och kontextinformationen för parsning.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI:n för filen som innehåller XML-data. Objektet [XmlResolver](../../xmlresolver/) på objektet [XmlReaderSettings](../../xmlreadersettings/) används för att konvertera sökvägen till en kanonisk datrepresentation. Om värdet för XmlReaderSettings::get_XmlResolver är **nullptr**, används ett nytt [XmlUrlResolver](../../xmlurlresolver/)-objekt. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Inställningarna för den nya [XmlReader](../)-instansen. Detta värde kan vara **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Den kontextinformation som krävs för att parsra XML-fragmentet. Kontextinformationen kan inkludera [XmlNameTable](../../xmlnametable/) att använda, kodning, namnrymdsområde, den aktuella **xml:lang**- och **xml:space**-omfånget, bas-URI och dokumenttypsdefinition. Detta värde kan vara **nullptr**. |

### Returvärde

Ett objekt som används för att läsa XML-data i strömmen.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) metod


Skapar en ny [XmlReader](../) instans med den angivna strömmen och standardinställningar.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen som innehåller XML-data. [XmlReader](../) skannar de första bytena i strömmen för att leta efter en byte order mark eller annat tecken på kodning. När kodningen har bestämt används den för att fortsätta läsa strömmen, och bearbetningen fortsätter med att parsra indata som en ström av (Unicode-)tecken. |

### Returvärde

Ett objekt som används för att läsa XML-data i strömmen.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) metod


Skapar en ny [XmlReader](../) instans med den angivna strömmen och inställningarna.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen som innehåller XML-data. [XmlReader](../) skannar de första bytena i strömmen för att leta efter en byte order mark eller annat tecken på kodning. När kodningen har bestämt används den för att fortsätta läsa strömmen, och bearbetningen fortsätter med att parsra indata som en ström av (Unicode-)tecken. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Inställningarna för den nya [XmlReader](../)-instansen. Detta värde kan vara **nullptr**. |

### Returvärde

Ett objekt som används för att läsa XML-data i strömmen.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) metod


Skapar en ny [XmlReader](../) instans med den angivna strömmen, bas-URI och inställningarna.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen som innehåller XML-data. [XmlReader](../) skannar de första bytena i strömmen för att leta efter en byte order mark eller annat tecken på kodning. När kodningen har bestämt används den för att fortsätta läsa strömmen, och bearbetningen fortsätter med att parsra indata som en ström av (Unicode-)tecken. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Inställningarna för den nya [XmlReader](../)-instansen. Detta värde kan vara **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | Bas-URI för den entitet eller det dokument som läses. Detta värde kan vara **nullptr**. **[Security](../../../system.security/) Observera** Bas-URI:n används för att lösa den relativa URI:n för XML-dokumentet. Använd inte en bas-URI från en opålitlig källa. |

### Returvärde

Ett objekt som används för att läsa XML-data i strömmen.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metod


Skapar en ny [XmlReader](../) instans med den angivna strömmen, inställningarna och kontextinformationen för parsning.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen som innehåller XML-data. [XmlReader](../) skannar de första bytena i strömmen för att leta efter en byte order mark eller annat tecken på kodning. När kodningen har bestämt används den för att fortsätta läsa strömmen, och bearbetningen fortsätter med att parsra indata som en ström av (Unicode-)tecken. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Inställningarna för den nya [XmlReader](../)-instansen. Detta värde kan vara **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Den kontextinformation som krävs för att parsra XML-fragmentet. Kontextinformationen kan inkludera [XmlNameTable](../../xmlnametable/) att använda, kodning, namnrymdsområde, den aktuella **xml:lang**- och **xml:space**-omfånget, bas-URI och dokumenttypsdefinition. Detta värde kan vara **nullptr**. |

### Returvärde

Ett objekt som används för att läsa XML-data i strömmen.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) metod


Skapar en ny [XmlReader](../) instans genom att använda den angivna textläsaren.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Textläsaren från vilken XML-data läses. En textläsare returnerar en ström av Unicode-tecken, så kodningen som anges i XML-deklarationen används inte av XML-läsaren för att avkoda dataströmmen. |

### Returvärde

Ett objekt som används för att läsa XML-data i strömmen.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) metod


Skapar en ny [XmlReader](../) instans genom att använda den angivna textläsaren och inställningarna.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Textläsaren från vilken XML-data läses. En textläsare returnerar en ström av Unicode-tecken, så kodningen som anges i XML-deklarationen används inte av XML-läsaren för att avkoda dataströmmen. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Inställningarna för den nya [XmlReader](../). Detta värde kan vara **nullptr**. |

### Returvärde

Ett objekt som används för att läsa XML-data i strömmen.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) metod


Skapar en ny [XmlReader](../) instans genom att använda den angivna textläsaren, inställningarna och bas-URI:n.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Textläsaren från vilken XML-data läses. En textläsare returnerar en ström av Unicode-tecken, så kodningen i XML-deklarationen används inte av [XmlReader](../) för att avkoda dataströmmen. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Inställningarna för den nya [XmlReader](../)-instansen. Detta värde kan vara **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | Bas-URI för den entitet eller det dokument som läses. Detta värde kan vara **nullptr**. **[Security](../../../system.security/) Observera** Bas-URI:n används för att lösa den relativa URI:n för XML-dokumentet. Använd inte en bas-URI från en opålitlig källa. |

### Returvärde

Ett objekt som används för att läsa XML-data i strömmen.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metod


Skapar en ny [XmlReader](../) instans genom att använda den angivna textläsaren, inställningarna och kontextinformationen för parsning.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Textläsaren från vilken XML-data läses. En textläsare returnerar en ström av Unicode-tecken, så kodningen i XML-deklarationen används inte av XML-läsaren för att avkoda dataströmmen. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Inställningarna för den nya [XmlReader](../)-instansen. Detta värde kan vara **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Den kontextinformation som krävs för att parsra XML-fragmentet. Kontextinformationen kan inkludera [XmlNameTable](../../xmlnametable/) att använda, kodning, namnrymdsområde, den aktuella **xml:lang**- och **xml:space**-omfånget, bas-URI och dokumenttypsdefinition. Detta värde kan vara **nullptr**. |

### Returvärde

Ett objekt som används för att läsa XML-data i strömmen.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) metod


Skapar en ny [XmlReader](../) instans genom att använda den angivna XML-läsaren och inställningarna.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | Objektet som du vill använda som den underliggande XML-läsaren. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Inställningarna för den nya [XmlReader](../)-instansen. Konformitetsnivån för objektet [XmlReaderSettings](../../xmlreadersettings/) måste antingen matcha konformitetsnivån för den underliggande läsaren, eller så måste den vara inställd på [ConformanceLevel::Auto](../../conformancelevel/). |

### Returvärde

Ett objekt som omsluter det angivna [XmlReader](../)-objektet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlReader](../)
* Klass [String](../../../system/string/)
* Klass [XmlReaderSettings](../../xmlreadersettings/)
* Klass [XmlParserContext](../../xmlparsercontext/)
* Klass [Stream](../../../system.io/stream/)
* Klass [TextReader](../../../system.io/textreader/)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)