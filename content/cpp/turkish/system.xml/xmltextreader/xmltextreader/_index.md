---
title: XmlTextReader()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen akış ile XmlTextReader sınıfının yeni bir örneğini başlatır.
type: docs
weight: 482
url: /tr/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) constructor

Belirtilen akış ile [XmlTextReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Okunacak XML verisini içeren akış. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) constructor

Belirtilen URL ve akış ile [XmlTextReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Harici kaynakları çözümlemek için kullanılacak URL. [XmlTextReader::get_BaseURI](../get_baseuri/) bu değere ayarlanır. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Okunacak XML verisini içeren akış. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Belirtilen akış ve [XmlNameTable](../../xmlnametable/) ile [XmlTextReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Okunacak XML verisini içeren akış. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Kullanılacak [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Belirtilen URL, akış ve [XmlNameTable](../../xmlnametable/) ile [XmlTextReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Harici kaynakları çözümlemek için kullanılacak URL. [XmlTextReader::get_BaseURI](../get_baseuri/) bu değere ayarlanır. **url** **nullptr** ise, **BaseURI** [String::Empty](../../../system/string/empty/) olarak ayarlanır. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Okunacak XML verisini içeren akış. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Kullanılacak [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) constructor

Belirtilen TextReader ile [XmlTextReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Okunacak XML verisini içeren TextReader. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) constructor

Belirtilen URL ve TextReader ile [XmlTextReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Harici kaynakları çözümlemek için kullanılacak URL. [XmlTextReader::get_BaseURI](../get_baseuri/) bu değere ayarlanır. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Okunacak XML verisini içeren TextReader. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Belirtilen TextReader ve [XmlNameTable](../../xmlnametable/) ile [XmlTextReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Okunacak XML verisini içeren TextReader. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Kullanılacak [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Belirtilen URL, TextReader ve [XmlNameTable](../../xmlnametable/) ile [XmlTextReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Harici kaynakları çözümlemek için kullanılacak URL. [XmlTextReader::get_BaseURI](../get_baseuri/) bu değere ayarlanır. **url** **nullptr** ise, **BaseURI** [String::Empty](../../../system/string/empty/) olarak ayarlanır. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Okunacak XML verisini içeren TextReader. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Kullanılacak [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Belirtilen akış, XmlNodeType ve [XmlParserContext](../../xmlparsercontext/) ile [XmlTextReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Ayrıştırılacak XML parçacığını içeren akış. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML parçacığının XmlNodeType'ı. Bu aynı zamanda parçacığın ne içerebileceğini belirler. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) içinde **xmlFragment** ayrıştırılır. Bu, kullanılacak [XmlNameTable](../../xmlnametable/), kodlama, ad alanı kapsamı, geçerli **xml:lang**, ve **xml:space** kapsamını içerir. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Belirtilen dize, XmlNodeType ve [XmlParserContext](../../xmlparsercontext/) ile [XmlTextReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Ayrıştırılacak XML parçacığını içeren dize. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML parçacığının XmlNodeType'ı. Bu aynı zamanda parçacık dizesinin ne içerebileceğini belirler. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) içinde **xmlFragment** ayrıştırılır. Bu, kullanılacak [XmlNameTable](../../xmlnametable/), kodlama, ad alanı kapsamı, geçerli **xml:lang**, ve **xml:space** kapsamını içerir. |

## XmlTextReader::XmlTextReader(const String\&) constructor

Belirtilen dosya ile [XmlTextReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | XML verisini içeren dosyanın URL'si. [XmlTextReader::get_BaseURI](../get_baseuri/) bu değere ayarlanır. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) constructor

Belirtilen dosya ve [XmlNameTable](../../xmlnametable/) ile [XmlTextReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Okunacak XML verisini içeren dosyanın URL'si. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Kullanılacak [XmlNameTable](../../xmlnametable/). |

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