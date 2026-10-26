---
title: XmlTextReader()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicializa una nueva instancia de la clase XmlTextReader con el flujo especificado.
type: docs
weight: 482
url: /es/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) constructor

Inicializa una nueva instancia de la clase [XmlTextReader](../) con el flujo especificado.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo que contiene los datos XML a leer. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) constructor

Inicializa una nueva instancia de la clase [XmlTextReader](../) con la URL y el flujo especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | La URL a usar para resolver recursos externos. [XmlTextReader::get_BaseURI](../get_baseuri/) se establece a este valor. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo que contiene los datos XML a leer. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Inicializa una nueva instancia de la clase [XmlTextReader](../) con el flujo y [XmlNameTable](../../xmlnametable/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo que contiene los datos XML a leer. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | El [XmlNameTable](../../xmlnametable/) a usar. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Inicializa una nueva instancia de la clase [XmlTextReader](../) con la URL, el flujo y [XmlNameTable](../../xmlnametable/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | La URL a usar para resolver recursos externos. [XmlTextReader::get_BaseURI](../get_baseuri/) se establece a este valor. Si **url** es **nullptr**, **BaseURI** se establece a [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo que contiene los datos XML a leer. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | El [XmlNameTable](../../xmlnametable/) a usar. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) constructor

Inicializa una nueva instancia de la clase [XmlTextReader](../) con el TextReader especificado.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | El TextReader que contiene los datos XML a leer. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) constructor

Inicializa una nueva instancia de la clase [XmlTextReader](../) con la URL y el TextReader especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | La URL a usar para resolver recursos externos. [XmlTextReader::get_BaseURI](../get_baseuri/) se establece a este valor. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | El TextReader que contiene los datos XML a leer. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Inicializa una nueva instancia de la clase [XmlTextReader](../) con el TextReader y [XmlNameTable](../../xmlnametable/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | El TextReader que contiene los datos XML a leer. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | El [XmlNameTable](../../xmlnametable/) a usar. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Inicializa una nueva instancia de la clase [XmlTextReader](../) con la URL, el TextReader y [XmlNameTable](../../xmlnametable/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | La URL a usar para resolver recursos externos. [XmlTextReader::get_BaseURI](../get_baseuri/) se establece a este valor. Si **url** es **nullptr**, **BaseURI** se establece a [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | El TextReader que contiene los datos XML a leer. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | El [XmlNameTable](../../xmlnametable/) a usar. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Inicializa una nueva instancia de la clase [XmlTextReader](../) con el flujo, XmlNodeType y [XmlParserContext](../../xmlparsercontext/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo que contiene el fragmento XML a analizar. |
| fragType | [XmlNodeType](../../xmlnodetype/) | El XmlNodeType del fragmento XML. Esto también determina lo que el fragmento puede contener. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | El [XmlParserContext](../../xmlparsercontext/) en el que se debe analizar **xmlFragment**. Esto incluye el [XmlNameTable](../../xmlnametable/) a usar, codificación, alcance de espacio de nombres, el **xml:lang** actual y el alcance de **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Inicializa una nueva instancia de la clase [XmlTextReader](../) con la cadena, XmlNodeType y [XmlParserContext](../../xmlparsercontext/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | La cadena que contiene el fragmento XML a analizar. |
| fragType | [XmlNodeType](../../xmlnodetype/) | El XmlNodeType del fragmento XML. Esto también determina lo que la cadena fragmento puede contener. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | El [XmlParserContext](../../xmlparsercontext/) en el que se debe analizar **xmlFragment**. Esto incluye el [XmlNameTable](../../xmlnametable/) a usar, codificación, alcance de espacio de nombres, el **xml:lang** actual y el alcance de **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&) constructor

Inicializa una nueva instancia de la clase [XmlTextReader](../) con el archivo especificado.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | La URL del archivo que contiene los datos XML. [XmlTextReader::get_BaseURI](../get_baseuri/) se establece a este valor. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) constructor

Inicializa una nueva instancia de la clase [XmlTextReader](../) con el archivo y [XmlNameTable](../../xmlnametable/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | La URL del archivo que contiene los datos XML a leer. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | El [XmlNameTable](../../xmlnametable/) a usar. |

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