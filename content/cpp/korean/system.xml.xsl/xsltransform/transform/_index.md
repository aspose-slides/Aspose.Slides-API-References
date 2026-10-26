---
title: Transform()
second_title: C++용 Aspose.Slides API 레퍼런스
description: XPathNavigator에 있는 XML 데이터를 지정된 args를 사용하여 변환하고 결과를 XmlReader에 출력합니다.
type: docs
weight: 40
url: /ko/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

지정된 **args**를 사용하여 XPathNavigator의 XML 데이터를 변환하고 결과를 [XmlReader](../../../system.xml/xmlreader/)에 출력합니다.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 변환될 데이터를 포함하는 XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** 함수를 해석하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). 이 값이 **nullptr**이면 **document()** 함수가 해석되지 않습니다. 이 메서드가 완료된 후 [XmlResolver](../../../system.xml/xmlresolver/)는 캐시되지 않습니다. |

### 반환 값

변환 결과를 포함하는 [XmlReader](../../../system.xml/xmlreader/).

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) method

지정된 **args**를 사용하여 XPathNavigator의 XML 데이터를 변환하고 결과를 [XmlReader](../../../system.xml/xmlreader/)에 출력합니다.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 변환될 데이터를 포함하는 XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |

### 반환 값

변환 결과를 포함하는 [XmlReader](../../../system.xml/xmlreader/).

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

지정된 args를 사용하여 XPathNavigator의 XML 데이터를 변환하고 결과를 [XmlWriter](../../../system.xml/xmlwriter/)에 출력합니다.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 변환될 데이터를 포함하는 XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 출력하려는 [XmlWriter](../../../system.xml/xmlwriter/). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** 함수를 해석하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). 이 값이 **nullptr**이면 **document()** 함수가 해석되지 않습니다. 이 메서드가 완료된 후 [XmlResolver](../../../system.xml/xmlresolver/)는 캐시되지 않습니다. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

지정된 args를 사용하여 XPathNavigator의 XML 데이터를 변환하고 결과를 [XmlWriter](../../../system.xml/xmlwriter/)에 출력합니다.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 변환될 데이터를 포함하는 XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 출력하려는 [XmlWriter](../../../system.xml/xmlwriter/). |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

지정된 **args**를 사용하여 XPathNavigator의 XML 데이터를 변환하고 결과를 스트림에 출력합니다.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 변환될 데이터를 포함하는 XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 출력하려는 스트림. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** 함수를 해석하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). 이 값이 **nullptr**이면 **document()** 함수가 해석되지 않습니다. 이 메서드가 완료된 후 [XmlResolver](../../../system.xml/xmlresolver/)는 캐시되지 않습니다. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

지정된 **args**를 사용하여 XPathNavigator의 XML 데이터를 변환하고 결과를 스트림에 출력합니다.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 변환될 데이터를 포함하는 XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 출력하려는 스트림. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

지정된 **args**를 사용하여 XPathNavigator의 XML 데이터를 변환하고 결과를 TextWriter에 출력합니다.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 변환될 데이터를 포함하는 XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 출력하려는 TextWriter. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** 함수를 해석하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). 이 값이 **nullptr**이면 **document()** 함수가 해석되지 않습니다. 이 메서드가 완료된 후 [XmlResolver](../../../system.xml/xmlresolver/)는 캐시되지 않습니다. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

지정된 **args**를 사용하여 XPathNavigator의 XML 데이터를 변환하고 결과를 TextWriter에 출력합니다.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 변환될 데이터를 포함하는 XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 출력하려는 TextWriter. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

지정된 **args**를 사용하여 IXPathNavigable의 XML 데이터를 변환하고 결과를 [XmlReader](../../../system.xml/xmlreader/)에 출력합니다.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체. 일반적으로 [XmlDocument](../../../system.xml/xmldocument/)인 [XmlNode](../../../system.xml/xmlnode/)이거나, 변환할 데이터를 포함하는 XPathDocument일 수 있습니다. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** 함수를 해석하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). 이 값이 **nullptr**이면 **document()** 함수가 해석되지 않습니다. 이 메서드가 완료된 후 [XmlResolver](../../../system.xml/xmlresolver/)는 캐시되지 않습니다. |

### 반환 값

변환 결과를 포함하는 [XmlReader](../../../system.xml/xmlreader/).

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) method

지정된 **args**를 사용하여 IXPathNavigable의 XML 데이터를 변환하고 결과를 [XmlReader](../../../system.xml/xmlreader/)에 출력합니다.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체. 일반적으로 [XmlDocument](../../../system.xml/xmldocument/)인 [XmlNode](../../../system.xml/xmlnode/)이거나, 변환할 데이터를 포함하는 XPathDocument일 수 있습니다. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |

### 반환 값

변환 결과를 포함하는 [XmlReader](../../../system.xml/xmlreader/).

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

지정된 **args**를 사용하여 IXPathNavigable의 XML 데이터를 변환하고 결과를 TextWriter에 출력합니다.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체. 일반적으로 [XmlDocument](../../../system.xml/xmldocument/)인 [XmlNode](../../../system.xml/xmlnode/)이거나, 변환할 데이터를 포함하는 XPathDocument일 수 있습니다. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 출력하려는 TextWriter. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** 함수를 해석하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). 이 값이 **nullptr**이면 **document()** 함수가 해석되지 않습니다. 이 메서드가 완료된 후 [XmlResolver](../../../system.xml/xmlresolver/)는 캐시되지 않습니다. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

지정된 **args**를 사용하여 IXPathNavigable의 XML 데이터를 변환하고 결과를 TextWriter에 출력합니다.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체. 일반적으로 [XmlDocument](../../../system.xml/xmldocument/)인 [XmlNode](../../../system.xml/xmlnode/)이거나, 변환할 데이터를 포함하는 XPathDocument일 수 있습니다. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 출력하려는 TextWriter. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

지정된 **args**를 사용하여 IXPathNavigable의 XML 데이터를 변환하고 결과를 스트림에 출력합니다.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체. 일반적으로 [XmlDocument](../../../system.xml/xmldocument/)인 [XmlNode](../../../system.xml/xmlnode/)이거나, 변환할 데이터를 포함하는 XPathDocument일 수 있습니다. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 출력하려는 스트림. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** 함수를 해석하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). 이 값이 **nullptr**이면 **document()** 함수가 해석되지 않습니다. 이 [XslTransform::Transform](./) 메서드가 완료된 후 [XmlResolver](../../../system.xml/xmlresolver/)는 캐시되지 않습니다. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

지정된 **args**를 사용하여 IXPathNavigable의 XML 데이터를 변환하고 결과를 스트림에 출력합니다.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체. 일반적으로 [XmlDocument](../../../system.xml/xmldocument/)인 [XmlNode](../../../system.xml/xmlnode/)이거나, 변환할 데이터를 포함하는 XPathDocument일 수 있습니다. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 출력하려는 스트림. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

지정된 **args**를 사용하여 IXPathNavigable의 XML 데이터를 변환하고 결과를 [XmlWriter](../../../system.xml/xmlwriter/)에 출력합니다.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체. 일반적으로 [XmlDocument](../../../system.xml/xmldocument/)인 [XmlNode](../../../system.xml/xmlnode/)이거나, 변환할 데이터를 포함하는 XPathDocument일 수 있습니다. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 출력하려는 [XmlWriter](../../../system.xml/xmlwriter/). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** 함수를 해석하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). 이 값이 **nullptr**이면 **document()** 함수가 해석되지 않습니다. 이 메서드가 완료된 후 [XmlResolver](../../../system.xml/xmlresolver/)는 캐시되지 않습니다. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

지정된 **args**를 사용하여 IXPathNavigable의 XML 데이터를 변환하고 결과를 [XmlWriter](../../../system.xml/xmlwriter/)에 출력합니다.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체. 일반적으로 [XmlDocument](../../../system.xml/xmldocument/)인 [XmlNode](../../../system.xml/xmlnode/)이거나, 변환할 데이터를 포함하는 XPathDocument일 수 있습니다. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환 입력에 사용되는 네임스페이스가 지정된 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 출력하려는 [XmlWriter](../../../system.xml/xmlwriter/). |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

입력 파일의 XML 데이터를 변환하고 결과를 출력 파일에 출력합니다.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | 변환할 소스 문서의 URL. |
| outputfile | const [String](../../../system/string/)\& | 출력 파일의 URL. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** 함수를 해석하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). 이 값이 **nullptr**이면 **document()** 함수가 해석되지 않습니다. 이 [XslTransform::Transform](./) 메서드가 완료된 후 [XmlResolver](../../../system.xml/xmlresolver/)는 캐시되지 않습니다. |

## XslTransform::Transform(const String\&, const String\&) method

입력 파일의 XML 데이터를 변환하고 결과를 출력 파일에 출력합니다.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | 변환할 소스 문서의 URL. |
| outputfile | const [String](../../../system/string/)\& | 출력 파일의 URL. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlReader](../../../system.xml/xmlreader/)
* 클래스 [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* 클래스 [XsltArgumentList](../../xsltargumentlist/)
* 클래스 [XmlResolver](../../../system.xml/xmlresolver/)
* 클래스 [XslTransform](../)
* 클래스 [XmlWriter](../../../system.xml/xmlwriter/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [TextWriter](../../../system.io/textwriter/)
* 클래스 [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)