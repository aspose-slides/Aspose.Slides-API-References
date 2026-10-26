---
title: XmlTextReader()
second_title: Aspose.Slides for C++ Dokumentacja API
description: Inicjalizuje nową instancję klasy XmlTextReader z określonym strumieniem.
type: docs
weight: 482
url: /pl/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlTextReader](../) z określonym strumieniem.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień zawierający dane XML do odczytu. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlTextReader](../) z określonym adresem URL i strumieniem.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Adres URL używany do rozwiązywania zasobów zewnętrznych. Właściwość [XmlTextReader::get_BaseURI](../get_baseuri/) jest ustawiona na tę wartość. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień zawierający dane XML do odczytu. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlTextReader](../) z określonym strumieniem i [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień zawierający dane XML do odczytu. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Używany [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlTextReader](../) z określonym adresem URL, strumieniem i [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Adres URL używany do rozwiązywania zasobów zewnętrznych. Właściwość [XmlTextReader::get_BaseURI](../get_baseuri/) jest ustawiona na tę wartość. Jeśli **url** jest **nullptr**, **BaseURI** jest ustawiony na [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień zawierający dane XML do odczytu. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Używany [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlTextReader](../) z określonym TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader zawierający dane XML do odczytu. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlTextReader](../) z określonym adresem URL i TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Adres URL używany do rozwiązywania zasobów zewnętrznych. Właściwość [XmlTextReader::get_BaseURI](../get_baseuri/) jest ustawiona na tę wartość. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader zawierający dane XML do odczytu. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlTextReader](../) z określonym TextReader i [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader zawierający dane XML do odczytu. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Używany [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlTextReader](../) z określonym adresem URL, TextReader i [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Adres URL używany do rozwiązywania zasobów zewnętrznych. Właściwość [XmlTextReader::get_BaseURI](../get_baseuri/) jest ustawiona na tę wartość. Jeśli **url** jest **nullptr**, **BaseURI** jest ustawiony na [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader zawierający dane XML do odczytu. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Używany [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlTextReader](../) z określonym strumieniem, XmlNodeType i [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień zawierający fragment XML do przetworzenia. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Typ XmlNodeType fragmentu XML. Określa również, co fragment może zawierać. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) w którym **xmlFragment** ma być przetwarzany. Obejmuje to [XmlNameTable](../../xmlnametable/) do użycia, kodowanie, zakres przestrzeni nazw, bieżące **xml:lang** i zakres **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlTextReader](../) z określonym ciągiem znaków, XmlNodeType i [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Ciąg znaków zawierający fragment XML do przetworzenia. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Typ XmlNodeType fragmentu XML. Określa również, co fragment może zawierać. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) w którym **xmlFragment** ma być przetwarzany. Obejmuje to [XmlNameTable](../../xmlnametable/) do użycia, kodowanie, zakres przestrzeni nazw, bieżące **xml:lang** i zakres **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&) konstruktor


Inicjalizuje nową instancję klasy [XmlTextReader](../) z określonym plikiem.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Adres URL pliku zawierającego dane XML. Właściwość [XmlTextReader::get_BaseURI](../get_baseuri/) jest ustawiona na tę wartość. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlTextReader](../) z określonym plikiem i [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Adres URL pliku zawierającego dane XML do odczytu. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Używany [XmlNameTable](../../xmlnametable/). |

## Zobacz także

* Wyliczenie [XmlNodeType](../../xmlnodetype/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [XmlTextReader](../)
* Klasa [String](../../../system/string/)
* Klasa [XmlNameTable](../../xmlnametable/)
* Klasa [TextReader](../../../system.io/textreader/)
* Klasa [XmlParserContext](../../xmlparsercontext/)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)