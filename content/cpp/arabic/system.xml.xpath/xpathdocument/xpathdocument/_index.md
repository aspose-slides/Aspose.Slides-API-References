---
title: XPathDocument()
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: يقوم بإنشاء مثيل جديد من الفئة XPathDocument من بيانات XML الموجودة في كائن XmlReader المحدد.
type: docs
weight: 1
url: /ar/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) constructor

يُنشئ مثيلاً جديداً من الفئة [XPathDocument](../) باستخدام بيانات XML الموجودة في الكائن [XmlReader](../../../system.xml/xmlreader/) المحدد.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | الكائن [XmlReader](../../../system.xml/xmlreader/) الذي يحتوي على بيانات XML. |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) constructor

يُنشئ مثيلاً جديداً من الفئة [XPathDocument](../) باستخدام بيانات XML الموجودة في الكائن [XmlReader](../../../system.xml/xmlreader/) المحدد مع معالجة المسافات البيضاء المحددة.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | الكائن [XmlReader](../../../system.xml/xmlreader/) الذي يحتوي على بيانات XML. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | كائن XmlSpace. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) constructor

يُنشئ مثيلاً جديداً من الفئة [XPathDocument](../) باستخدام بيانات XML الموجودة في كائن TextReader المحدد.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | كائن TextReader الذي يحتوي على بيانات XML. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) constructor

يُنشئ مثيلاً جديداً من الفئة [XPathDocument](../) باستخدام بيانات XML الموجودة في كائن Stream المحدد.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | كائن Stream الذي يحتوي على بيانات XML. |

## XPathDocument::XPathDocument(const String\&) constructor

يُنشئ مثيلاً جديداً من الفئة [XPathDocument](../) باستخدام بيانات XML الموجودة في الملف المحدد.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | مسار الملف الذي يحتوي على بيانات XML. |

## XPathDocument::XPathDocument(const String\&, XmlSpace) constructor

يُنشئ مثيلاً جديداً من الفئة [XPathDocument](../) باستخدام بيانات XML الموجودة في الملف مع معالجة المسافات البيضاء المحددة.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | مسار الملف الذي يحتوي على بيانات XML. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | كائن XmlSpace. |

## انظر أيضًا

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathDocument](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)