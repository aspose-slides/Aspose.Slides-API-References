---
title: XmlTextReader()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ مثيلًا جديدًا من الفئة XmlTextReader باستخدام الدفق المحدد.
type: docs
weight: 482
url: /ar/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) المُنشئ

يُنشئ مثيلًا جديدًا للفئة [XmlTextReader](../) مع الدفق المحدد.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | الدفق الذي يحتوي على بيانات XML للقراءة. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) المُنشئ

يُنشئ مثيلًا جديدًا للفئة [XmlTextReader](../) مع عنوان URL المحدد والدفق.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | عنوان URL لاستخدامه في حل الموارد الخارجية. يتم تعيين [XmlTextReader::get_BaseURI](../get_baseuri/) إلى هذه القيمة. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | الدفق الذي يحتوي على بيانات XML للقراءة. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) المُنشئ

يُنشئ مثيلًا جديدًا للفئة [XmlTextReader](../) مع الدفق المحدد و[XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | الدفق الذي يحتوي على بيانات XML للقراءة. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | ال[XmlNameTable](../../xmlnametable/) للاستخدام. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) المُنشئ

يُنشئ مثيلًا جديدًا للفئة [XmlTextReader](../) مع عنوان URL المحدد والدفق و[XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | عنوان URL لاستخدامه في حل الموارد الخارجية. يتم تعيين [XmlTextReader::get_BaseURI](../get_baseuri/) إلى هذه القيمة. إذا كان **url** يساوي **nullptr**، يتم تعيين **BaseURI** إلى [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | الدفق الذي يحتوي على بيانات XML للقراءة. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | ال[XmlNameTable](../../xmlnametable/) للاستخدام. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) المُنشئ

يُنشئ مثيلًا جديدًا للفئة [XmlTextReader](../) مع القارئ النصي المحدد.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | القارئ النصي الذي يحتوي على بيانات XML للقراءة. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) المُنشئ

يُنشئ مثيلًا جديدًا للفئة [XmlTextReader](../) مع عنوان URL والقارئ النصي المحدد.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | عنوان URL لاستخدامه في حل الموارد الخارجية. يتم تعيين [XmlTextReader::get_BaseURI](../get_baseuri/) إلى هذه القيمة. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | القارئ النصي الذي يحتوي على بيانات XML للقراءة. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) المُنشئ

يُنشئ مثيلًا جديدًا للفئة [XmlTextReader](../) مع القارئ النصي المحدد و[XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | القارئ النصي الذي يحتوي على بيانات XML للقراءة. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | ال[XmlNameTable](../../xmlnametable/) للاستخدام. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlParserContext\>\&) المُنشئ

يُنشئ مثيلًا جديدًا للفئة [XmlTextReader](../) مع عنوان URL والقارئ النصي و[XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | عنوان URL لاستخدامه في حل الموارد الخارجية. يتم تعيين [XmlTextReader::get_BaseURI](../get_baseuri/) إلى هذه القيمة. إذا كان **url** يساوي **nullptr**، يتم تعيين **BaseURI** إلى [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | القارئ النصي الذي يحتوي على بيانات XML للقراءة. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | ال[XmlNameTable](../../xmlnametable/) للاستخدام. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) المُنشئ

يُنشئ مثيلًا جديدًا للفئة [XmlTextReader](../) مع الدفق المحدد وXmlNodeType و[XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | الدفق الذي يحتوي على جزء XML للتحليل. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType لجزء XML. يحدد أيضًا ما يمكن أن يحتويه الجزء. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | الـ[XmlParserContext](../../xmlparsercontext/) الذي سيُحَلَّ فيه **xmlFragment**. يشمل ذلك الـ[XmlNameTable](../../xmlnametable/) للاستخدام، الترميز، نطاق الفضاء الاسمي، **xml:lang** الحالي، ونطاق **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) المُنشئ

يُنشئ مثيلًا جديدًا للفئة [XmlTextReader](../) مع السلسلة المحددة وXmlNodeType و[XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | السلسلة التي تحتوي على جزء XML للتحليل. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType لجزء XML. يحدد أيضًا ما يمكن أن تحتويه السلسلة. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | الـ[XmlParserContext](../../xmlparsercontext/) الذي سيُحَلَّ فيه **xmlFragment**. يشمل ذلك الـ[XmlNameTable](../../xmlnametable/) للاستخدام، الترميز، نطاق الفضاء الاسمي، **xml:lang** الحالي، ونطاق **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&) المُنشئ

يُنشئ مثيلًا جديدًا للفئة [XmlTextReader](../) مع الملف المحدد.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | عنوان URL للملف الذي يحتوي على بيانات XML. يتم تعيين [XmlTextReader::get_BaseURI](../get_baseuri/) إلى هذه القيمة. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) المُنشئ

يُنشئ مثيلًا جديدًا للفئة [XmlTextReader](../) مع الملف المحدد و[XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | عنوان URL للملف الذي يحتوي على بيانات XML للقراءة. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | الـ[XmlNameTable](../../xmlnametable/) للاستخدام. |

## انظر أيضًا

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