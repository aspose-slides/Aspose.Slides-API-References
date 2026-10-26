---
title: Create()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 URI로 새로운 XmlReader 인스턴스를 생성합니다.
type: docs
weight: 1015
url: /ko/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) 메서드

지정된 URI로 새로운 [XmlReader](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | XML 데이터를 포함하는 파일의 URI입니다. [XmlUrlResolver](../../xmlurlresolver/) 클래스는 경로를 정규화된 데이터 표현으로 변환하는 데 사용됩니다. |

### 반환값

스트림에서 XML 데이터를 읽는 데 사용되는 객체입니다.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) 메서드

지정된 URI와 설정을 사용하여 새로운 [XmlReader](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | XML 데이터를 포함하는 파일의 URI입니다. [XmlReaderSettings](../../xmlreadersettings/) 객체의 [XmlResolver](../../xmlresolver/) 객체는 경로를 정규화된 데이터 표현으로 변환하는 데 사용됩니다. XmlReaderSettings::get_XmlResolver 값이 **nullptr**인 경우, 새로운 [XmlUrlResolver](../../xmlurlresolver/) 객체가 사용됩니다. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | 새로운 [XmlReader](../) 인스턴스에 대한 설정입니다. 이 값은 **nullptr**일 수 있습니다. |

### 반환값

스트림에서 XML 데이터를 읽는 데 사용되는 객체입니다.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) 메서드

지정된 URI, 설정 및 구문 분석을 위한 컨텍스트 정보를 사용하여 새로운 [XmlReader](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | XML 데이터를 포함하는 파일의 URI입니다. [XmlReaderSettings](../../xmlreadersettings/) 객체의 [XmlResolver](../../xmlresolver/) 객체는 경로를 정규화된 데이터 표현으로 변환하는 데 사용됩니다. XmlReaderSettings::get_XmlResolver 값이 **nullptr**인 경우, 새로운 [XmlUrlResolver](../../xmlurlresolver/) 객체가 사용됩니다. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 새로운 [XmlReader](../) 인스턴스에 대한 설정입니다. 이 값은 **nullptr**일 수 있습니다. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML 조각을 구문 분석하는 데 필요한 컨텍스트 정보입니다. 컨텍스트 정보에는 사용할 [XmlNameTable](../../xmlnametable/), 인코딩, 네임스페이스 범위, 현재 **xml:lang** 및 **xml:space** 범위, 기본 URI 및 DTD가 포함될 수 있습니다. 이 값은 **nullptr**일 수 있습니다. |

### 반환값

스트림에서 XML 데이터를 읽는 데 사용되는 객체입니다.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) 메서드

지정된 스트림과 기본 설정을 사용하여 새로운 [XmlReader](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML 데이터를 포함하는 스트림입니다. [XmlReader](../)는 스트림의 처음 몇 바이트를 검사하여 바이트 순서 표시(BOM) 또는 다른 인코딩 표시를 찾습니다. 인코딩이 결정되면 해당 인코딩을 사용하여 스트림을 계속 읽고, 입력을 (Unicode) 문자 스트림으로 구문 분석합니다. |

### 반환값

스트림에서 XML 데이터를 읽는 데 사용되는 객체입니다.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) 메서드

지정된 스트림과 설정을 사용하여 새로운 [XmlReader](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML 데이터를 포함하는 스트림입니다. [XmlReader](../)는 스트림의 처음 몇 바이트를 검사하여 바이트 순서 표시(BOM) 또는 다른 인코딩 표시를 찾습니다. 인코딩이 결정되면 해당 인코딩을 사용하여 스트림을 계속 읽고, 입력을 (Unicode) 문자 스트림으로 구문 분석합니다. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | 새로운 [XmlReader](../) 인스턴스에 대한 설정입니다. 이 값은 **nullptr**일 수 있습니다. |

### 반환값

스트림에서 XML 데이터를 읽는 데 사용되는 객체입니다.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) 메서드

지정된 스트림, 기본 URI 및 설정을 사용하여 새로운 [XmlReader](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML 데이터를 포함하는 스트림입니다. [XmlReader](../)는 스트림의 처음 몇 바이트를 검사하여 바이트 순서 표시(BOM) 또는 다른 인코딩 표시를 찾습니다. 인코딩이 결정되면 해당 인코딩을 사용하여 스트림을 계속 읽고, 입력을 (Unicode) 문자 스트림으로 구문 분석합니다. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 새로운 [XmlReader](../) 인스턴스에 대한 설정입니다. 이 값은 **nullptr**일 수 있습니다. |
| baseUri | const [String](../../../system/string/)\& | 읽는 엔터티 또는 문서의 기본 URI입니다. 이 값은 **nullptr**일 수 있습니다. **[Security](../../../system.security/) Note** 기본 URI는 XML 문서의 상대 URI를 해결하는 데 사용됩니다. 신뢰할 수 없는 소스의 기본 URI를 사용하지 마십시오. |

### 반환값

스트림에서 XML 데이터를 읽는 데 사용되는 객체입니다.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) 메서드

지정된 스트림, 설정 및 구문 분석을 위한 컨텍스트 정보를 사용하여 새로운 [XmlReader](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML 데이터를 포함하는 스트림입니다. [XmlReader](../)는 스트림의 처음 몇 바이트를 검사하여 바이트 순서 표시(BOM) 또는 다른 인코딩 표시를 찾습니다. 인코딩이 결정되면 해당 인코딩을 사용하여 스트림을 계속 읽고, 입력을 (Unicode) 문자 스트림으로 구문 분석합니다. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 새로운 [XmlReader](../) 인스턴스에 대한 설정입니다. 이 값은 **nullptr**일 수 있습니다. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML 조각을 구문 분석하는 데 필요한 컨텍스트 정보입니다. 컨텍스트 정보에는 사용할 [XmlNameTable](../../xmlnametable/), 인코딩, 네임스페이스 범위, 현재 **xml:lang** 및 **xml:space** 범위, 기본 URI 및 DTD가 포함될 수 있습니다. 이 값은 **nullptr**일 수 있습니다. |

### 반환값

스트림에서 XML 데이터를 읽는 데 사용되는 객체입니다.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) 메서드

지정된 텍스트 리더를 사용하여 새로운 [XmlReader](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML 데이터를 읽는 텍스트 리더입니다. 텍스트 리더는 Unicode 문자 스트림을 반환하므로 XML 선언에 지정된 인코딩은 XML 리더가 데이터 스트림을 디코딩하는 데 사용되지 않습니다. |

### 반환값

스트림에서 XML 데이터를 읽는 데 사용되는 객체입니다.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) 메서드

지정된 텍스트 리더와 설정을 사용하여 새로운 [XmlReader](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML 데이터를 읽는 텍스트 리더입니다. 텍스트 리더는 Unicode 문자 스트림을 반환하므로 XML 선언에 지정된 인코딩은 XML 리더가 데이터 스트림을 디코딩하는 데 사용되지 않습니다. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | 새로운 [XmlReader](../)에 대한 설정입니다. 이 값은 **nullptr**일 수 있습니다. |

### 반환값

스트림에서 XML 데이터를 읽는 데 사용되는 객체입니다.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) 메서드

지정된 텍스트 리더, 설정 및 기본 URI를 사용하여 새로운 [XmlReader](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML 데이터를 읽는 텍스트 리더입니다. 텍스트 리더는 Unicode 문자 스트림을 반환하므로 XML 선언에 지정된 인코딩은 [XmlReader](../)가 데이터 스트림을 디코딩하는 데 사용되지 않습니다. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 새로운 [XmlReader](../) 인스턴스에 대한 설정입니다. 이 값은 **nullptr**일 수 있습니다. |
| baseUri | const [String](../../../system/string/)\& | 읽는 엔터티 또는 문서의 기본 URI입니다. 이 값은 **nullptr**일 수 있습니다. **[Security](../../../system.security/) Note** 기본 URI는 XML 문서의 상대 URI를 해결하는 데 사용됩니다. 신뢰할 수 없는 소스의 기본 URI를 사용하지 마십시오. |

### 반환값

스트림에서 XML 데이터를 읽는 데 사용되는 객체입니다.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) 메서드

지정된 텍스트 리더, 설정 및 구문 분석을 위한 컨텍스트 정보를 사용하여 새로운 [XmlReader](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML 데이터를 읽는 텍스트 리더입니다. 텍스트 리더는 Unicode 문자 스트림을 반환하므로 XML 선언에 지정된 인코딩은 XML 리더가 데이터 스트림을 디코딩하는 데 사용되지 않습니다. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 새로운 [XmlReader](../) 인스턴스에 대한 설정입니다. 이 값은 **nullptr**일 수 있습니다. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML 조각을 구문 분석하는 데 필요한 컨텍스트 정보입니다. 컨텍스트 정보에는 사용할 [XmlNameTable](../../xmlnametable/), 인코딩, 네임스페이스 범위, 현재 **xml:lang** 및 **xml:space** 범위, 기본 URI 및 DTD가 포함될 수 있습니다. 이 값은 **nullptr**일 수 있습니다. |

### 반환값

스트림에서 XML 데이터를 읽는 데 사용되는 객체입니다.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) 메서드

지정된 XML 리더와 설정을 사용하여 새로운 [XmlReader](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | 기본 XML 리더로 사용하려는 객체입니다. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 새로운 [XmlReader](../) 인스턴스에 대한 설정입니다. [XmlReaderSettings](../../xmlreadersettings/) 객체의 준수 수준은 기본 리더의 준수 수준과 일치하거나 [ConformanceLevel::Auto](../../conformancelevel/)으로 설정되어야 합니다. |

### 반환값

지정된 [XmlReader](../) 객체를 감싸는 객체입니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlReader](../)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlReaderSettings](../../xmlreadersettings/)
* 클래스 [XmlParserContext](../../xmlparsercontext/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [TextReader](../../../system.io/textreader/)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)