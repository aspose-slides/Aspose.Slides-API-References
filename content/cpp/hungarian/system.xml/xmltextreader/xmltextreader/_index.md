---
title: XmlTextReader()
second_title: Aspose.Slides C++ API referencia
description: Új példányt hoz létre az XmlTextReader osztályból a megadott streammel.
type: docs
weight: 482
url: /hu/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) konstruktor

Új példányt hoz létre a(z) [XmlTextReader](../) osztályból a megadott streammel.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Az XML adatot tartalmazó stream, amelyet beolvasni. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) konstruktor

Új példányt hoz létre a(z) [XmlTextReader](../) osztályból a megadott URL-lel és streammel.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | A külső erőforrások feloldásához használandó URL. A [XmlTextReader::get_BaseURI](../get_baseuri/) erre az értékre van beállítva. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Az XML adatot tartalmazó stream, amelyet beolvasni. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) konstruktor

Új példányt hoz létre a(z) [XmlTextReader](../) osztályból a megadott streammel és [XmlNameTable](../../xmlnametable/)-vel.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Az XML adatot tartalmazó stream, amelyet beolvasni. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | A használandó [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) konstruktor

Új példányt hoz létre a(z) [XmlTextReader](../) osztályból a megadott URL-lel, streammel és [XmlNameTable](../../xmlnametable/)-val.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | A külső erőforrások feloldásához használandó URL. A [XmlTextReader::get_BaseURI](../get_baseuri/) erre az értékre van beállítva. Ha **url** **nullptr**, **BaseURI** értéke [String::Empty](../../../system/string/empty/) lesz. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Az XML adatot tartalmazó stream, amelyet beolvasni. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | A használandó [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) konstruktor

Új példányt hoz létre a(z) [XmlTextReader](../) osztályból a megadott TextReader-rel.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Az XML adatot tartalmazó TextReader, amelyet beolvasni. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) konstruktor

Új példányt hoz létre a(z) [XmlTextReader](../) osztályból a megadott URL-lel és TextReader-rel.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | A külső erőforrások feloldásához használandó URL. A [XmlTextReader::get_BaseURI](../get_baseuri/) erre az értékre van beállítva. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Az XML adatot tartalmazó TextReader, amelyet beolvasni. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) konstruktor

Új példányt hoz létre a(z) [XmlTextReader](../) osztályból a megadott TextReader-rel és [XmlNameTable](../../xmlnametable/)-val.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Az XML adatot tartalmazó TextReader, amelyet beolvasni. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | A használandó [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) konstruktor

Új példányt hoz létre a(z) [XmlTextReader](../) osztályból a megadott URL-lel, TextReader-rel és [XmlNameTable](../../xmlnametable/)-val.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | A külső erőforrások feloldásához használandó URL. A [XmlTextReader::get_BaseURI](../get_baseuri/) erre az értékre van beállítva. Ha **url** **nullptr**, **BaseURI** értéke [String::Empty](../../../system/string/empty/) lesz. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Az XML adatot tartalmazó TextReader, amelyet beolvasni. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | A használandó [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) konstruktor

Új példányt hoz létre a(z) [XmlTextReader](../) osztályból a megadott streammel, XmlNodeType-tal és [XmlParserContext](../../xmlparsercontext/)-val.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Az XML fragmentumot tartalmazó stream, amelyet feldolgozni. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Az XML fragmentum XmlNodeType-ja. Ez határozza meg, hogy a fragmentum mit tartalmazhat. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | A [XmlParserContext](../../xmlparsercontext/), amelyben a **xmlFragment** feldolgozásra kerül. Ez tartalmazza a használandó [XmlNameTable](../../xmlnametable/), kódolást, névtérkörnyezetet, a jelenlegi **xml:lang** értéket és az **xml:space** környezetet. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) konstruktor

Új példányt hoz létre a(z) [XmlTextReader](../) osztályból a megadott karakterlánccal, XmlNodeType-tal és [XmlParserContext](../../xmlparsercontext/)-val.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Az XML fragmentumot tartalmazó karakterlánc, amelyet feldolgozni. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Az XML fragmentum XmlNodeType-ja. Ez határozza meg, hogy a fragmentum karakterlánc mit tartalmazhat. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | A [XmlParserContext](../../xmlparsercontext/), amelyben a **xmlFragment** feldolgozásra kerül. Ez tartalmazza a használandó [XmlNameTable](../../xmlnametable/), kódolást, névtérkörnyezetet, a jelenlegi **xml:lang** értéket és az **xml:space** környezetet. |

## XmlTextReader::XmlTextReader(const String\&) konstruktor

Új példányt hoz létre a(z) [XmlTextReader](../) osztályból a megadott fájllal.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Az XML adatot tartalmazó fájl URL-je. A [XmlTextReader::get_BaseURI](../get_baseuri/) erre az értékre van beállítva. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) konstruktor

Új példányt hoz létre a(z) [XmlTextReader](../) osztályból a megadott fájllal és [XmlNameTable](../../xmlnametable/)-val.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Az XML adatot tartalmazó fájl URL-je, amelyet beolvasni. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | A használandó [XmlNameTable](../../xmlnametable/). |

## Lásd még

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