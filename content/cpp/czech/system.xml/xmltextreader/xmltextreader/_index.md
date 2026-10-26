---
title: XmlTextReader()
second_title: Aspose.Slides pro C++ – reference API
description: Inicializuje novou instanci třídy XmlTextReader se zadaným proudem.
type: docs
weight: 482
url: /cs/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) konstruktor

Inicializuje novou instanci třídy [XmlTextReader](../) se zadaným proudem.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Proud obsahující XML data ke čtení. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) konstruktor

Inicializuje novou instanci třídy [XmlTextReader](../) se zadanou URL a proudem.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL použité k řešení externích prostředků. [XmlTextReader::get_BaseURI](../get_baseuri/) je nastavena na tuto hodnotu. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Proud obsahující XML data ke čtení. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) konstruktor

Inicializuje novou instanci třídy [XmlTextReader](../) se zadaným proudem a [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Proud obsahující XML data ke čtení. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) k použití. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) konstruktor

Inicializuje novou instanci třídy [XmlTextReader](../) se zadanou URL, proudem a [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL použité k řešení externích prostředků. [XmlTextReader::get_BaseURI](../get_baseuri/) je nastavena na tuto hodnotu. Pokud je **url** **nullptr**, **BaseURI** je nastavena na [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Proud obsahující XML data ke čtení. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) k použití. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) konstruktor

Inicializuje novou instanci třídy [XmlTextReader](../) se zadaným TextReaderem.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader obsahující XML data ke čtení. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) konstruktor

Inicializuje novou instanci třídy [XmlTextReader](../) se zadanou URL a TextReaderem.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL použité k řešení externích prostředků. [XmlTextReader::get_BaseURI](../get_baseuri/) je nastavena na tuto hodnotu. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader obsahující XML data ke čtení. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) konstruktor

Inicializuje novou instanci třídy [XmlTextReader](../) se zadaným TextReaderem a [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader obsahující XML data ke čtení. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) k použití. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) konstruktor

Inicializuje novou instanci třídy [XmlTextReader](../) se zadanou URL, TextReaderem a [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL použité k řešení externích prostředků. [XmlTextReader::get_BaseURI](../get_baseuri/) je nastavena na tuto hodnotu. Pokud je **url** **nullptr**, **BaseURI** je nastavena na [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader obsahující XML data ke čtení. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) k použití. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) konstruktor

Inicializuje novou instanci třídy [XmlTextReader](../) se zadaným proudem, XmlNodeType a [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Proud obsahující XML fragment k analýze. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType XML fragmentu. Toto také určuje, co může fragment obsahovat. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) ve kterém má být **xmlFragment** analyzován. To zahrnuje [XmlNameTable](../../xmlnametable/) k použití, kódování, rozsah oboru názvů, aktuální **xml:lang**, a **xml:space** rozsah. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) konstruktor

Inicializuje novou instanci třídy [XmlTextReader](../) se zadaným řetězcem, XmlNodeType a [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Řetězec obsahující XML fragment k analýze. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType XML fragmentu. Toto také určuje, co může řetězec fragmentu obsahovat. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) ve kterém má být **xmlFragment** analyzován. To zahrnuje [XmlNameTable](../../xmlnametable/) k použití, kódování, rozsah oboru názvů, aktuální **xml:lang**, a **xml:space** rozsah. |

## XmlTextReader::XmlTextReader(const String\&) konstruktor

Inicializuje novou instanci třídy [XmlTextReader](../) se zadaným souborem.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL souboru obsahujícího XML data. [XmlTextReader::get_BaseURI](../get_baseuri/) je nastavena na tuto hodnotu. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) konstruktor

Inicializuje novou instanci třídy [XmlTextReader](../) se zadaným souborem a [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL souboru obsahujícího XML data ke čtení. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) k použití. |

## Viz také

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Stream](../../../system.io/stream/)
* Třída [XmlTextReader](../)
* Třída [String](../../../system/string/)
* Třída [XmlNameTable](../../xmlnametable/)
* Třída [TextReader](../../../system.io/textreader/)
* Třída [XmlParserContext](../../xmlparsercontext/)
* Obor názvů [System::Xml](../../)
* Library [Aspose.Slides](../../../)