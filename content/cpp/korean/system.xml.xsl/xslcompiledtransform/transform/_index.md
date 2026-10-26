---
title: Transform()
second_title: Aspose.Slides for C++ API 레퍼런스
description: IXPathNavigable 객체가 지정한 입력 문서를 사용하여 변환을 실행하고 결과를 XmlWriter에 출력합니다.
type: docs
weight: 40
url: /ko/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) 메서드

IXPathNavigable 객체가 지정한 입력 문서를 사용하여 변환을 실행하고 결과를 [XmlWriter](../../../system.xml/xmlwriter/)에 출력합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체입니다. [XmlNode](../../../system.xml/xmlnode/)(일반적으로 [XmlDocument](../../../system.xml/xmldocument/))이거나 변환할 데이터를 포함하는 XPathDocument일 수 있습니다. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 출력하려는 [XmlWriter](../../../system.xml/xmlwriter/)입니다. 스타일 시트에 **xsl:output** 요소가 포함된 경우, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 값에서 반환된 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 객체를 사용하여 [XmlWriter](../../../system.xml/xmlwriter/)를 생성해야 합니다. 이렇게 하면 [XmlWriter](../../../system.xml/xmlwriter/)에 올바른 출력 설정이 적용됩니다. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) 메서드

IXPathNavigable 객체가 지정한 입력 문서를 사용하여 변환을 실행하고 결과를 [XmlWriter](../../../system.xml/xmlwriter/)에 출력합니다. [XsltArgumentList](../../xsltargumentlist/)는 추가 실행 시간 인수를 제공합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체입니다. [XmlNode](../../../system.xml/xmlnode/)(일반적으로 [XmlDocument](../../../system.xml/xmldocument/))이거나 변환할 데이터를 포함하는 XPathDocument일 수 있습니다. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환에 입력으로 사용되는 네임스페이스 자격 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/)입니다. 이 값은 **nullptr**일 수 있습니다. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 출력하려는 [XmlWriter](../../../system.xml/xmlwriter/)입니다. 스타일 시트에 **xsl:output** 요소가 포함된 경우, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 값에서 반환된 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 객체를 사용하여 [XmlWriter](../../../system.xml/xmlwriter/)를 생성해야 합니다. 이렇게 하면 [XmlWriter](../../../system.xml/xmlwriter/)에 올바른 출력 설정이 적용됩니다. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) 메서드

IXPathNavigable 객체가 지정한 입력 문서를 사용하여 변환을 실행하고 결과를 TextWriter에 출력합니다. [XsltArgumentList](../../xsltargumentlist/)는 추가 실행 시간 인수를 제공합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체입니다. [XmlNode](../../../system.xml/xmlnode/)(일반적으로 [XmlDocument](../../../system.xml/xmldocument/))이거나 변환할 데이터를 포함하는 XPathDocument일 수 있습니다. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환에 입력으로 사용되는 네임스페이스 자격 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/)입니다. 이 값은 **nullptr**일 수 있습니다. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 출력하려는 TextWriter입니다. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) 메서드

IXPathNavigable 객체가 지정한 입력 문서를 사용하여 변환을 실행하고 결과를 스트림에 출력합니다. [XsltArgumentList](../../xsltargumentlist/)은 추가 런타임 인수를 제공합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체입니다. [XmlNode](../../../system.xml/xmlnode/)(일반적으로 [XmlDocument](../../../system.xml/xmldocument/))이거나 변환할 데이터를 포함하는 XPathDocument일 수 있습니다. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환에 입력으로 사용되는 네임스페이스 자격 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/)입니다. 이 값은 **nullptr**일 수 있습니다. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 출력하려는 스트림입니다. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) 메서드

[XmlReader](../../../system.xml/xmlreader/) 객체가 지정한 입력 문서를 사용하여 변환을 실행하고 결과를 [XmlWriter](../../../system.xml/xmlwriter/)에 출력합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 입력 문서를 포함하는 [XmlReader](../../../system.xml/xmlreader/)입니다. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 출력하려는 [XmlWriter](../../../system.xml/xmlwriter/)입니다. 스타일 시트에 **xsl:output** 요소가 포함된 경우, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 값에서 반환된 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 객체를 사용하여 [XmlWriter](../../../system.xml/xmlwriter/)를 생성해야 합니다. 이렇게 하면 [XmlWriter](../../../system.xml/xmlwriter/)에 올바른 출력 설정이 적용됩니다. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) 메서드

[XmlReader](../../../system.xml/xmlreader/) 객체가 지정한 입력 문서를 사용하여 변환을 실행하고 결과를 [XmlWriter](../../../system.xml/xmlwriter/)에 출력합니다. [XsltArgumentList](../../xsltargumentlist/)은 추가 실행 시간 인수를 제공합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 입력 문서를 포함하는 [XmlReader](../../../system.xml/xmlreader/)입니다. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환에 입력으로 사용되는 네임스페이스 자격 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/)입니다. 이 값은 **nullptr**일 수 있습니다. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 출력하려는 [XmlWriter](../../../system.xml/xmlwriter/)입니다. 스타일 시트에 **xsl:output** 요소가 포함된 경우, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 값에서 반환된 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 객체를 사용하여 [XmlWriter](../../../system.xml/xmlwriter/)를 생성해야 합니다. 이렇게 하면 [XmlWriter](../../../system.xml/xmlwriter/)에 올바른 출력 설정이 적용됩니다. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) 메서드

[XmlReader](../../../system.xml/xmlreader/) 객체가 지정한 입력 문서를 사용하여 변환을 실행하고 결과를 TextWriter에 출력합니다. [XsltArgumentList](../../xsltargumentlist/)는 추가 실행 시간 인수를 제공합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 입력 문서를 포함하는 [XmlReader](../../../system.xml/xmlreader/)입니다. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환에 입력으로 사용되는 네임스페이스 자격 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/)입니다. 이 값은 **nullptr**일 수 있습니다. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 출력하려는 TextWriter입니다. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) 메서드

[XmlReader](../../../system.xml/xmlreader/) 객체가 지정한 입력 문서를 사용하여 변환을 실행하고 결과를 스트림에 출력합니다. [XsltArgumentList](../../xsltargumentlist/)는 추가 실행 시간 인수를 제공합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 입력 문서를 포함하는 [XmlReader](../../../system.xml/xmlreader/)입니다. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환에 입력으로 사용되는 네임스페이스 자격 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/)입니다. 이 값은 **nullptr**일 수 있습니다. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 출력하려는 스트림입니다. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) 메서드

URI로 지정된 입력 문서를 사용하여 변환을 실행하고 결과를 [XmlWriter](../../../system.xml/xmlwriter/)에 출력합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 입력 문서의 URI입니다. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 출력하려는 [XmlWriter](../../../system.xml/xmlwriter/)입니다. 스타일 시트에 **xsl:output** 요소가 포함된 경우, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 값에서 반환된 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 객체를 사용하여 [XmlWriter](../../../system.xml/xmlwriter/)를 생성해야 합니다. 이렇게 하면 [XmlWriter](../../../system.xml/xmlwriter/)에 올바른 출력 설정이 적용됩니다. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) 메서드

URI로 지정된 입력 문서를 사용하여 변환을 실행하고 결과를 [XmlWriter](../../../system.xml/xmlwriter/)에 출력합니다. [XsltArgumentList](../../xsltargumentlist/)는 추가 실행 시간 인수를 제공합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 입력 문서의 URI입니다. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환에 입력으로 사용되는 네임스페이스 자격 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/)입니다. 이 값은 **nullptr**일 수 있습니다. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 출력하려는 [XmlWriter](../../../system.xml/xmlwriter/)입니다. 스타일 시트에 **xsl:output** 요소가 포함된 경우, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 값에서 반환된 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 객체를 사용하여 [XmlWriter](../../../system.xml/xmlwriter/)를 생성해야 합니다. 이렇게 하면 [XmlWriter](../../../system.xml/xmlwriter/)에 올바른 출력 설정이 적용됩니다. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) 메서드

URI로 지정된 입력 문서를 사용하여 변환을 실행하고 결과를 TextWriter에 출력합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 입력 문서의 URI입니다. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환에 입력으로 사용되는 네임스페이스 자격 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/)입니다. 이 값은 **nullptr**일 수 있습니다. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 출력하려는 TextWriter입니다. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) 메서드

URI로 지정된 입력 문서를 사용하여 변환을 실행하고 결과를 스트림에 출력합니다. [XsltArgumentList](../../xsltargumentlist/)은 추가 실행 시간 인수를 제공합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 입력 문서의 URI입니다. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환에 입력으로 사용되는 네임스페이스 자격 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/)입니다. 이 값은 **nullptr**일 수 있습니다. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 출력하려는 스트림입니다. |

## XslCompiledTransform::Transform(const String\&, const String\&) 메서드

URI로 지정된 입력 문서를 사용하여 변환을 실행하고 결과를 파일에 출력합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 입력 문서의 URI입니다. |
| resultsFile | const [String](../../../system/string/)\& | 출력 파일의 URI입니다. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) 메서드

[XmlReader](../../../system.xml/xmlreader/) 객체가 지정한 입력 문서를 사용하여 변환을 실행하고 결과를 [XmlWriter](../../../system.xml/xmlwriter/)에 출력합니다. [XsltArgumentList](../../xsltargumentlist/)는 추가 실행 시간 인수를 제공하며 [XmlResolver](../../../system.xml/xmlresolver/)는 XSLT **document()** 함수를 해결합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 입력 문서를 포함하는 [XmlReader](../../../system.xml/xmlreader/)입니다. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 변환에 입력으로 사용되는 네임스페이스 자격 인수를 포함하는 [XsltArgumentList](../../xsltargumentlist/)입니다. 이 값은 **nullptr**일 수 있습니다. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 출력하려는 [XmlWriter](../../../system.xml/xmlwriter/)입니다. 스타일 시트에 **xsl:output** 요소가 포함된 경우, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 값에서 반환된 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 객체를 사용하여 [XmlWriter](../../../system.xml/xmlwriter/)를 생성해야 합니다. 이렇게 하면 [XmlWriter](../../../system.xml/xmlwriter/)에 올바른 출력 설정이 적용됩니다. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** 함수를 해결하는 [XmlResolver](../../../system.xml/xmlresolver/)입니다. 이 값이 **nullptr**이면 **document()** 함수가 해결되지 않습니다. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) 메서드

IXPathNavigable 객체가 지정한 입력 문서를 사용하여 변환을 실행하고 결과를 [XmlWriter](../../../system.xml/xmlwriter/)에 출력합니다. [XsltArgumentList](../../xsltargumentlist/)는 추가 실행 시간 인수를 제공하며 [XmlResolver](../../../system.xml/xmlresolver/)는 XSLT **document()** 함수를 해결합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 객체가 지정한 변환할 문서입니다. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) 형식의 인수 목록입니다. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 출력하려는 [XmlWriter](../../../system.xml/xmlwriter/)입니다. 스타일 시트에 **xsl:output** 요소가 포함된 경우, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) 값에서 반환된 [XmlWriterSettings](../../../system.xml/xmlwritersettings/) 객체를 사용하여 [XmlWriter](../../../system.xml/xmlwriter/)를 생성해야 합니다. 이렇게 하면 [XmlWriter](../../../system.xml/xmlwriter/)에 올바른 출력 설정이 적용됩니다. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** 함수를 해결하는 [XmlResolver](../../../system.xml/xmlresolver/)입니다. 이 값이 **nullptr**이면 **document()** 함수가 해결되지 않습니다. |

## 또한 보기

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* 클래스 [XmlWriter](../../../system.xml/xmlwriter/)
* 클래스 [XslCompiledTransform](../)
* 클래스 [XsltArgumentList](../../xsltargumentlist/)
* 클래스 [TextWriter](../../../system.io/textwriter/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [XmlReader](../../../system.xml/xmlreader/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlResolver](../../../system.xml/xmlresolver/)
* 네임스페이스 [System::Xml::Xsl](../../)
* 라이브러리 [Aspose.Slides](../../../)