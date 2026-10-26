---
title: XmlTextReader()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza una nuova istanza della classe XmlTextReader con lo stream specificato.
type: docs
weight: 482
url: /it/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) costruttore

Inizializza una nuova istanza della classe [XmlTextReader](../) con lo stream specificato.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream contenente i dati XML da leggere. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) costruttore

Inizializza una nuova istanza della classe [XmlTextReader](../) con l'URL e lo stream specificati.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L'URL da utilizzare per la risoluzione delle risorse esterne. Il [XmlTextReader::get_BaseURI](../get_baseuri/) è impostato a questo valore. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream contenente i dati XML da leggere. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) costruttore

Inizializza una nuova istanza della classe [XmlTextReader](../) con lo stream e il [XmlNameTable](../../xmlnametable/) specificati.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream contenente i dati XML da leggere. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Il [XmlNameTable](../../xmlnametable/) da utilizzare. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) costruttore

Inizializza una nuova istanza della classe [XmlTextReader](../) con l'URL, lo stream e il [XmlNameTable](../../xmlnametable/) specificati.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L'URL da utilizzare per la risoluzione delle risorse esterne. Il [XmlTextReader::get_BaseURI](../get_baseuri/) è impostato a questo valore. Se **url** è **nullptr**, **BaseURI** è impostato a [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream contenente i dati XML da leggere. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Il [XmlNameTable](../../xmlnametable/) da utilizzare. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) costruttore

Inizializza una nuova istanza della classe [XmlTextReader](../) con il TextReader specificato.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Il TextReader contenente i dati XML da leggere. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) costruttore

Inizializza una nuova istanza della classe [XmlTextReader](../) con l'URL e il TextReader specificati.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L'URL da utilizzare per la risoluzione delle risorse esterne. Il [XmlTextReader::get_BaseURI](../get_baseuri/) è impostato a questo valore. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Il TextReader contenente i dati XML da leggere. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) costruttore

Inizializza una nuova istanza della classe [XmlTextReader](../) con il TextReader e il [XmlNameTable](../../xmlnametable/) specificati.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Il TextReader contenente i dati XML da leggere. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Il [XmlNameTable](../../xmlnametable/) da utilizzare. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) costruttore

Inizializza una nuova istanza della classe [XmlTextReader](../) con l'URL, il TextReader e il [XmlNameTable](../../xmlnametable/) specificati.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L'URL da utilizzare per la risoluzione delle risorse esterne. Il [XmlTextReader::get_BaseURI](../get_baseuri/) è impostato a questo valore. Se **url** è **nullptr**, **BaseURI** è impostato a [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Il TextReader contenente i dati XML da leggere. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Il [XmlNameTable](../../xmlnametable/) da utilizzare. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) costruttore

Inizializza una nuova istanza della classe [XmlTextReader](../) con lo stream, XmlNodeType e il [XmlParserContext](../../xmlparsercontext/) specificati.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream contenente il frammento XML da analizzare. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Il XmlNodeType del frammento XML. Questo determina anche ciò che il frammento può contenere. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Il [XmlParserContext](../../xmlparsercontext/) in cui il **xmlFragment** deve essere analizzato. Include il [XmlNameTable](../../xmlnametable/) da usare, la codifica, l'ambito del namespace, l'**xml:lang** corrente e l'ambito **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) costruttore

Inizializza una nuova istanza della classe [XmlTextReader](../) con la stringa, XmlNodeType e il [XmlParserContext](../../xmlparsercontext/) specificati.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | La stringa contenente il frammento XML da analizzare. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Il XmlNodeType del frammento XML. Questo determina anche ciò che la stringa del frammento può contenere. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Il [XmlParserContext](../../xmlparsercontext/) in cui il **xmlFragment** deve essere analizzato. Include il [XmlNameTable](../../xmlnametable/) da usare, la codifica, l'ambito del namespace, l'**xml:lang** corrente e l'ambito **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&) costruttore

Inizializza una nuova istanza della classe [XmlTextReader](../) con il file specificato.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L'URL del file contenente i dati XML. Il [XmlTextReader::get_BaseURI](../get_baseuri/) è impostato a questo valore. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) costruttore

Inizializza una nuova istanza della classe [XmlTextReader](../) con il file e il [XmlNameTable](../../xmlnametable/) specificati.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L'URL del file contenente i dati XML da leggere. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Il [XmlNameTable](../../xmlnametable/) da utilizzare. |

## Vedi anche

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