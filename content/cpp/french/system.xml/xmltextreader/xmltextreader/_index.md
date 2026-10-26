---
title: XmlTextReader()
second_title: Référence de l'API Aspose.Slides for C++
description: Initialise une nouvelle instance de la classe XmlTextReader avec le flux spécifié.
type: docs
weight: 482
url: /fr/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) constructeur


Initialise une nouvelle instance de la classe [XmlTextReader](../) avec le flux spécifié.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux contenant les données XML à lire. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) constructeur


Initialise une nouvelle instance de la classe [XmlTextReader](../) avec l’URL et le flux spécifiés.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L’URL à utiliser pour résoudre les ressources externes. Le [XmlTextReader::get_BaseURI](../get_baseuri/) est défini sur cette valeur. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux contenant les données XML à lire. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructeur


Initialise une nouvelle instance de la classe [XmlTextReader](../) avec le flux et le [XmlNameTable](../../xmlnametable/) spécifiés.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux contenant les données XML à lire. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Le [XmlNameTable](../../xmlnametable/) à utiliser. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructeur


Initialise une nouvelle instance de la classe [XmlTextReader](../) avec l’URL, le flux et le [XmlNameTable](../../xmlnametable/) spécifiés.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L’URL à utiliser pour résoudre les ressources externes. Le [XmlTextReader::get_BaseURI](../get_baseuri/) est défini sur cette valeur. Si **url** est **nullptr**, **BaseURI** est défini sur [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux contenant les données XML à lire. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Le [XmlNameTable](../../xmlnametable/) à utiliser. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) constructeur


Initialise une nouvelle instance de la classe [XmlTextReader](../) avec le TextReader spécifié.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Le TextReader contenant les données XML à lire. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) constructeur


Initialise une nouvelle instance de la classe [XmlTextReader](../) avec l’URL et le TextReader spécifiés.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L’URL à utiliser pour résoudre les ressources externes. Le [XmlTextReader::get_BaseURI](../get_baseuri/) est défini sur cette valeur. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Le TextReader contenant les données XML à lire. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructeur


Initialise une nouvelle instance de la classe [XmlTextReader](../) avec le TextReader et le [XmlNameTable](../../xmlnametable/) spécifiés.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Le TextReader contenant les données XML à lire. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Le [XmlNameTable](../../xmlnametable/) à utiliser. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructeur


Initialise une nouvelle instance de la classe [XmlTextReader](../) avec l’URL, le TextReader et le [XmlNameTable](../../xmlnametable/) spécifiés.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L’URL à utiliser pour résoudre les ressources externes. Le [XmlTextReader::get_BaseURI](../get_baseuri/) est défini sur cette valeur. Si **url** est **nullptr**, **BaseURI** est défini sur [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Le TextReader contenant les données XML à lire. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Le [XmlNameTable](../../xmlnametable/) à utiliser. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructeur


Initialise une nouvelle instance de la classe [XmlTextReader](../) avec le flux, le XmlNodeType et le [XmlParserContext](../../xmlparsercontext/) spécifiés.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux contenant le fragment XML à analyser. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Le XmlNodeType du fragment XML. Ceci détermine également ce que le fragment peut contenir. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Le [XmlParserContext](../../xmlparsercontext/) dans lequel le **xmlFragment** doit être analysé. Cela inclut le [XmlNameTable](../../xmlnametable/) à utiliser, le codage, la portée des espaces de noms, le **xml:lang** actuel et la portée du **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructeur


Initialise une nouvelle instance de la classe [XmlTextReader](../) avec la chaîne, le XmlNodeType et le [XmlParserContext](../../xmlparsercontext/) spécifiés.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | La chaîne contenant le fragment XML à analyser. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Le XmlNodeType du fragment XML. Ceci détermine également ce que la chaîne de fragment peut contenir. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Le [XmlParserContext](../../xmlparsercontext/) dans lequel le **xmlFragment** doit être analysé. Cela inclut le [XmlNameTable](../../xmlnametable/) à utiliser, le codage, la portée des espaces de noms, le **xml:lang** actuel et la portée du **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&) constructeur


Initialise une nouvelle instance de la classe [XmlTextReader](../) avec le fichier spécifié.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L’URL du fichier contenant les données XML. Le [XmlTextReader::get_BaseURI](../get_baseuri/) est défini sur cette valeur. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) constructeur


Initialise une nouvelle instance de la classe [XmlTextReader](../) avec le fichier et le [XmlNameTable](../../xmlnametable/) spécifiés.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L’URL du fichier contenant les données XML à lire. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Le [XmlNameTable](../../xmlnametable/) à utiliser. |

## Voir aussi

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [XmlTextReader](../)
* Classe [String](../../../system/string/)
* Classe [XmlNameTable](../../xmlnametable/)
* Classe [TextReader](../../../system.io/textreader/)
* Classe [XmlParserContext](../../xmlparsercontext/)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)