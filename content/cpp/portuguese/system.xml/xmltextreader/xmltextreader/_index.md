---
title: XmlTextReader()
second_title: Referência da API Aspose.Slides for C++
description: Inicializa uma nova instância da classe XmlTextReader com o fluxo especificado.
type: docs
weight: 482
url: /pt/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) construtor


Inicializa uma nova instância da classe [XmlTextReader](../) com o fluxo especificado.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O fluxo contendo os dados XML a serem lidos. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) construtor


Inicializa uma nova instância da classe [XmlTextReader](../) com a URL e o fluxo especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | A URL a ser usada para resolver recursos externos. O [XmlTextReader::get_BaseURI](../get_baseuri/) é definido para este valor. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O fluxo contendo os dados XML a serem lidos. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) construtor


Inicializa uma nova instância da classe [XmlTextReader](../) com o fluxo e o [XmlNameTable](../../xmlnametable/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O fluxo contendo os dados XML a serem lidos. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | O [XmlNameTable](../../xmlnametable/) a ser usado. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) construtor


Inicializa uma nova instância da classe [XmlTextReader](../) com a URL, o fluxo e [XmlNameTable](../../xmlnametable/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | A URL a ser usada para resolver recursos externos. O [XmlTextReader::get_BaseURI](../get_baseuri/) é definido para este valor. Se **url** for **nullptr**, **BaseURI** será definido como [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O fluxo contendo os dados XML a serem lidos. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | O [XmlNameTable](../../xmlnametable/) a ser usado. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) construtor


Inicializa uma nova instância da classe [XmlTextReader](../) com o TextReader especificado.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | O TextReader contendo os dados XML a serem lidos. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) construtor


Inicializa uma nova instância da classe [XmlTextReader](../) com a URL e o TextReader especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | A URL a ser usada para resolver recursos externos. O [XmlTextReader::get_BaseURI](../get_baseuri/) é definido para este valor. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | O TextReader contendo os dados XML a serem lidos. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) construtor


Inicializa uma nova instância da classe [XmlTextReader](../) com o TextReader e [XmlNameTable](../../xmlnametable/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | O TextReader contendo os dados XML a serem lidos. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | O [XmlNameTable](../../xmlnametable/) a ser usado. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) construtor


Inicializa uma nova instância da classe [XmlTextReader](../) com a URL, o TextReader e [XmlNameTable](../../xmlnametable/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | A URL a ser usada para resolver recursos externos. O [XmlTextReader::get_BaseURI](../get_baseuri/) é definido para este valor. Se **url** for **nullptr**, **BaseURI** será definido como [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | O TextReader contendo os dados XML a serem lidos. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | O [XmlNameTable](../../xmlnametable/) a ser usado. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) construtor


Inicializa uma nova instância da classe [XmlTextReader](../) com o fluxo, o XmlNodeType e [XmlParserContext](../../xmlparsercontext/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O fluxo contendo o fragmento XML a ser analisado. |
| fragType | [XmlNodeType](../../xmlnodetype/) | O XmlNodeType do fragmento XML. Isso também determina o que o fragmento pode conter. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | O [XmlParserContext](../../xmlparsercontext/) no qual o **xmlFragment** será analisado. Isso inclui o [XmlNameTable](../../xmlnametable/) a ser usado, codificação, escopo de namespace, o **xml:lang** atual e o escopo **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) construtor


Inicializa uma nova instância da classe [XmlTextReader](../) com a string, o XmlNodeType e [XmlParserContext](../../xmlparsercontext/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | A string contendo o fragmento XML a ser analisado. |
| fragType | [XmlNodeType](../../xmlnodetype/) | O XmlNodeType do fragmento XML. Isso também determina o que a string de fragmento pode conter. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | O [XmlParserContext](../../xmlparsercontext/) no qual o **xmlFragment** será analisado. Isso inclui o [XmlNameTable](../../xmlnametable/) a ser usado, codificação, escopo de namespace, o **xml:lang** atual e o escopo **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&) construtor


Inicializa uma nova instância da classe [XmlTextReader](../) com o arquivo especificado.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | A URL do arquivo que contém os dados XML. O [XmlTextReader::get_BaseURI](../get_baseuri/) é definido para este valor. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) construtor


Inicializa uma nova instância da classe [XmlTextReader](../) com o arquivo e [XmlNameTable](../../xmlnametable/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | A URL do arquivo que contém os dados XML a serem lidos. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | O [XmlNameTable](../../xmlnametable/) a ser usado. |

## See Also

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)