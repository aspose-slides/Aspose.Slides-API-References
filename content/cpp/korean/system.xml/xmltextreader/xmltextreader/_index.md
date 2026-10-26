---
title: XmlTextReader()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 스트림으로 XmlTextReader 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 482
url: /ko/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) constructor

지정된 스트림으로 [XmlTextReader](../) 클래스를 새 인스턴스로 초기화합니다.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 읽을 XML 데이터가 포함된 스트림. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) constructor

지정된 URL과 스트림으로 [XmlTextReader](../) 클래스를 새 인스턴스로 초기화합니다.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 외부 리소스를 해결하는 데 사용할 URL입니다. [XmlTextReader::get_BaseURI](../get_baseuri/)가 이 값으로 설정됩니다. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 읽을 XML 데이터가 포함된 스트림. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

지정된 스트림과 [XmlNameTable](../../xmlnametable/)으로 [XmlTextReader](../) 클래스를 새 인스턴스로 초기화합니다.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 읽을 XML 데이터가 포함된 스트림. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/)을(를) 사용합니다. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

지정된 URL, 스트림 및 [XmlNameTable](../../xmlnametable/)으로 [XmlTextReader](../) 클래스를 새 인스턴스로 초기화합니다.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 외부 리소스를 해결하는 데 사용할 URL입니다. [XmlTextReader::get_BaseURI](../get_baseuri/)가 이 값으로 설정됩니다. **url**이 **nullptr**인 경우, **BaseURI**는 [String::Empty](../../../system/string/empty/)로 설정됩니다. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 읽을 XML 데이터가 포함된 스트림. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/)을(를) 사용합니다. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) constructor

지정된 TextReader로 [XmlTextReader](../) 클래스를 새 인스턴스로 초기화합니다.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 읽을 XML 데이터가 포함된 TextReader. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) constructor

지정된 URL과 TextReader로 [XmlTextReader](../) 클래스를 새 인스턴스로 초기화합니다.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 외부 리소스를 해결하는 데 사용할 URL입니다. [XmlTextReader::get_BaseURI](../get_baseuri/)가 이 값으로 설정됩니다. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 읽을 XML 데이터가 포함된 TextReader. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

지정된 TextReader와 [XmlNameTable](../../xmlnametable/)으로 [XmlTextReader](../) 클래스를 새 인스턴스로 초기화합니다.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 읽을 XML 데이터가 포함된 TextReader. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/)을(를) 사용합니다. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

지정된 URL, TextReader 및 [XmlNameTable](../../xmlnametable/)으로 [XmlTextReader](../) 클래스를 새 인스턴스로 초기화합니다.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 외부 리소스를 해결하는 데 사용할 URL입니다. [XmlTextReader::get_BaseURI](../get_baseuri/)가 이 값으로 설정됩니다. **url**이 **nullptr**인 경우, **BaseURI**는 [String::Empty](../../../system/string/empty/)로 설정됩니다. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 읽을 XML 데이터가 포함된 TextReader. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/)을(를) 사용합니다. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

지정된 스트림, XmlNodeType 및 [XmlParserContext](../../xmlparsercontext/)으로 [XmlTextReader](../) 클래스를 새 인스턴스로 초기화합니다.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 파싱할 XML 조각이 포함된 스트림. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML 조각의 XmlNodeType입니다. 이는 조각이 포함할 수 있는 내용을 결정합니다. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | **xmlFragment**를 파싱할 [XmlParserContext](../../xmlparsercontext/)입니다. 여기에는 사용할 [XmlNameTable](../../xmlnametable/), 인코딩, 네임스페이스 범위, 현재 **xml:lang**, **xml:space** 범위가 포함됩니다. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

지정된 문자열, XmlNodeType 및 [XmlParserContext](../../xmlparsercontext/)으로 [XmlTextReader](../) 클래스를 새 인스턴스로 초기화합니다.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | 파싱할 XML 조각이 포함된 문자열. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML 조각의 XmlNodeType입니다. 이는 조각 문자열이 포함할 수 있는 내용을 결정합니다. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | **xmlFragment**를 파싱할 [XmlParserContext](../../xmlparsercontext/)입니다. 여기에는 사용할 [XmlNameTable](../../xmlnametable/), 인코딩, 네임스페이스 범위, 현재 **xml:lang**, **xml:space** 범위가 포함됩니다. |

## XmlTextReader::XmlTextReader(const String\&) constructor

지정된 파일로 [XmlTextReader](../) 클래스를 새 인스턴스로 초기화합니다.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | XML 데이터가 포함된 파일의 URL입니다. [XmlTextReader::get_BaseURI](../get_baseuri/)가 이 값으로 설정됩니다. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) constructor

지정된 파일 및 [XmlNameTable](../../xmlnametable/)으로 [XmlTextReader](../) 클래스를 새 인스턴스로 초기화합니다.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 읽을 XML 데이터가 포함된 파일의 URL입니다. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/)를 사용합니다. |

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