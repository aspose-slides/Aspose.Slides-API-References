---
title: Create()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří novou instanci XmlReader se zadaným URI.
type: docs
weight: 1015
url: /cs/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) metoda


Vytvoří novou [XmlReader](../) instanci se specifikovaným URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI souboru, který obsahuje XML data. Třída [XmlUrlResolver](../../xmlurlresolver/) se používá k převodu cesty na kanonickou datovou reprezentaci. |

### Návratová hodnota

Objekt, který se používá k čtení XML dat ve streamu.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) metoda


Vytvoří novou [XmlReader](../) instanci pomocí specifikovaného URI a nastavení.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI souboru obsahujícího XML data. Objekt [XmlResolver](../../xmlresolver/) na objektu [XmlReaderSettings](../../xmlreadersettings/) se používá k převodu cesty na kanonickou datovou reprezentaci. Pokud je hodnota XmlReaderSettings::get_XmlResolver **nullptr**, je použita nová [XmlUrlResolver](../../xmlurlresolver/) objekt. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Nastavení pro novou [XmlReader](../) instanci. Tato hodnota může být **nullptr**. |

### Návratová hodnota

Objekt, který se používá k čtení XML dat ve streamu.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metoda


Vytvoří novou [XmlReader](../) instanci pomocí specifikovaného URI, nastavení a kontextových informací pro parsování.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI souboru obsahujícího XML data. Objekt [XmlResolver](../../xmlresolver/) na objektu [XmlReaderSettings](../../xmlreadersettings/) se používá k převodu cesty na kanonickou datovou reprezentaci. Pokud je hodnota XmlReaderSettings::get_XmlResolver **nullptr**, je použita nová [XmlUrlResolver](../../xmlurlresolver/) objekt. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Nastavení pro novou [XmlReader](../) instanci. Tato hodnota může být **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Kontextové informace potřebné k parsování XML fragmentu. Kontextové informace mohou zahrnovat [XmlNameTable](../../xmlnametable/) k použití, kódování, rozsah jmenného prostoru, aktuální **xml:lang** a **xml:space** rozsah, základní URI a definici typu dokumentu. Tato hodnota může být **nullptr**. |

### Návratová hodnota

Objekt, který se používá k čtení XML dat ve streamu.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) metoda


Vytvoří novou [XmlReader](../) instanci pomocí specifikovaného streamu s výchozími nastaveními.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream, který obsahuje XML data. [XmlReader](../) prohledává první bajty streamu a hledá značku pořadí bajtů nebo jiný znak kódování. Když je kódování určeno, použije se k dalšímu čtení streamu a zpracování pokračuje parsováním vstupu jako streamu (Unicode) znaků. |

### Návratová hodnota

Objekt, který se používá k čtení XML dat ve streamu.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) metoda


Vytvoří novou [XmlReader](../) instanci se specifikovaným streamem a nastavením.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream, který obsahuje XML data. [XmlReader](../) prohledává první bajty streamu a hledá značku pořadí bajtů nebo jiný znak kódování. Když je kódování určeno, použije se k dalšímu čtení streamu a zpracování pokračuje parsováním vstupu jako streamu (Unicode) znaků. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Nastavení pro novou [XmlReader](../) instanci. Tato hodnota může být **nullptr**. |

### Návratová hodnota

Objekt, který se používá k čtení XML dat ve streamu.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) metoda


Vytvoří novou [XmlReader](../) instanci pomocí specifikovaného streamu, základního URI a nastavení.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream, který obsahuje XML data. [XmlReader](../) prohledává první bajty streamu a hledá značku pořadí bajtů nebo jiný znak kódování. Když je kódování určeno, použije se k dalšímu čtení streamu a zpracování pokračuje parsováním vstupu jako streamu (Unicode) znaků. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Nastavení pro novou [XmlReader](../) instanci. Tato hodnota může být **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | Základní URI pro entitu nebo dokument, který se čte. Tato hodnota může být **nullptr**. **[Security](../../../system.security/) Poznámka** Základní URI se používá k vyřešení relativního URI XML dokumentu. Nepoužívejte základní URI z nedůvěryhodného zdroje. |

### Návratová hodnota

Objekt, který se používá k čtení XML dat ve streamu.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metoda


Vytvoří novou [XmlReader](../) instanci pomocí specifikovaného streamu, nastavení a kontextových informací pro parsování.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream, který obsahuje XML data. [XmlReader](../) prohledává první bajty streamu a hledá značku pořadí bajtů nebo jiný znak kódování. Když je kódování určeno, použije se k dalšímu čtení streamu a zpracování pokračuje parsováním vstupu jako streamu (Unicode) znaků. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Nastavení pro novou [XmlReader](../) instanci. Tato hodnota může být **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Kontextové informace potřebné k parsování XML fragmentu. Kontextové informace mohou zahrnovat [XmlNameTable](../../xmlnametable/) k použití, kódování, rozsah jmenného prostoru, aktuální **xml:lang** a **xml:space** rozsah, základní URI a definici typu dokumentu. Tato hodnota může být **nullptr**. |

### Návratová hodnota

Objekt, který se používá k čtení XML dat ve streamu.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) metoda


Vytvoří novou [XmlReader](../) instanci pomocí specifikovaného textového čtečky.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Textový čtečka, ze které se mají číst XML data. Textový čtečka vrací stream Unicode znaků, takže kódování uvedené v XML deklaraci není použito XML čtečkou k dekódování datového streamu. |

### Návratová hodnota

Objekt, který se používá k čtení XML dat ve streamu.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) metoda


Vytvoří novou [XmlReader](../) instanci pomocí specifikovaného textového čtečky a nastavení.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Textový čtečka, ze které se mají číst XML data. Textový čtečka vrací stream Unicode znaků, takže kódování uvedené v XML deklaraci není použito XML čtečkou k dekódování datového streamu. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Nastavení pro novou [XmlReader](../). Tato hodnota může být **nullptr**. |

### Návratová hodnota

Objekt, který se používá k čtení XML dat ve streamu.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) metoda


Vytvoří novou [XmlReader](../) instanci pomocí specifikovaného textového čtečky, nastavení a základního URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Textový čtečka, ze které se mají číst XML data. Textový čtečka vrací stream Unicode znaků, takže kódování uvedené v XML deklaraci není použito [XmlReader](../) k dekódování datového streamu. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Nastavení pro novou [XmlReader](../) instanci. Tato hodnota může být **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | Základní URI pro entitu nebo dokument, který se čte. Tato hodnota může být **nullptr**. **[Security](../../../system.security/) Poznámka** Základní URI se používá k vyřešení relativního URI XML dokumentu. Nepoužívejte základní URI z nedůvěryhodného zdroje. |

### Návratová hodnota

Objekt, který se používá k čtení XML dat ve streamu.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metoda


Vytvoří novou [XmlReader](../) instanci pomocí specifikovaného textového čtečky, nastavení a kontextových informací pro parsování.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Textový čtečka, ze které se mají číst XML data. Textový čtečka vrací stream Unicode znaků, takže kódování uvedené v XML deklaraci není použito XML čtečkou k dekódování datového streamu. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Nastavení pro novou [XmlReader](../) instanci. Tato hodnota může být **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Kontextové informace potřebné k parsování XML fragmentu. Kontextové informace mohou zahrnovat [XmlNameTable](../../xmlnametable/) k použití, kódování, rozsah jmenného prostoru, aktuální **xml:lang** a **xml:space** rozsah, základní URI a definici typu dokumentu. Tato hodnota může být **nullptr**. |

### Návratová hodnota

Objekt, který se používá k čtení XML dat ve streamu.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) metoda


Vytvoří novou [XmlReader](../) instanci pomocí specifikovaného XML čtečky a nastavení.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | Objekt, který chcete použít jako podkladový XML čtečka. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Nastavení pro novou [XmlReader](../) instanci. Úroveň shody objektu [XmlReaderSettings](../../xmlreadersettings/) musí buď odpovídat úrovni shody podkladového čtečky, nebo musí být nastavena na [ConformanceLevel::Auto](../../conformancelevel/). |

### Návratová hodnota

Objekt, který je zabalený kolem specifikovaného [XmlReader](../) objektu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlReader](../)
* Třída [String](../../../system/string/)
* Třída [XmlReaderSettings](../../xmlreadersettings/)
* Třída [XmlParserContext](../../xmlparsercontext/)
* Třída [Stream](../../../system.io/stream/)
* Třída [TextReader](../../../system.io/textreader/)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)