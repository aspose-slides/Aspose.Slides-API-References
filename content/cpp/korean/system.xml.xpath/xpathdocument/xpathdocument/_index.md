---
title: XPathDocument()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 XmlReader 객체에 포함된 XML 데이터를 사용하여 XPathDocument 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 1
url: /ko/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) constructor

지정된 [XmlReader](../../../system.xml/xmlreader/) 객체에 포함된 XML 데이터를 사용하여 [XPathDocument](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | The [XmlReader](../../../system.xml/xmlreader/) object that contains the XML data. |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) constructor

지정된 [XmlReader](../../../system.xml/xmlreader/) 객체에 포함된 XML 데이터를 사용하고 지정된 공백 처리 방식을 적용하여 [XPathDocument](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | The [XmlReader](../../../system.xml/xmlreader/) object that contains the XML data. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | An XmlSpace object. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) constructor

지정된 TextReader 객체에 포함된 XML 데이터를 사용하여 [XPathDocument](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | The TextReader object that contains the XML data. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) constructor

지정된 Stream 객체에 포함된 XML 데이터를 사용하여 [XPathDocument](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The Stream object that contains the XML data. |

## XPathDocument::XPathDocument(const String\&) constructor

지정된 파일에 포함된 XML 데이터를 사용하여 [XPathDocument](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | The path of the file that contains the XML data. |

## XPathDocument::XPathDocument(const String\&, XmlSpace) constructor

지정된 공백 처리 방식을 적용한 파일에 포함된 XML 데이터를 사용하여 [XPathDocument](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | The path of the file that contains the XML data. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | An XmlSpace object. |

## 참고

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathDocument](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)