---
title: Create()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 파일 이름을 사용하여 새로운 XmlWriter 인스턴스를 생성합니다.
type: docs
weight: 469
url: /ko/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) 메서드


지정된 파일 이름을 사용하여 새로운 [XmlWriter](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | 쓰기 원하는 파일입니다. [XmlWriter](../) 은 지정된 경로에 파일을 만들고 XML 1.0 텍스트 구문으로 씁니다. **outputFileName** 은 파일 시스템 경로여야 합니다. |

### 반환 값

[XmlWriter](../) 객체입니다.

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) 메서드


파일 이름과 [XmlWriterSettings](../../xmlwritersettings/) 객체를 사용하여 새로운 [XmlWriter](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | 쓰기 원하는 파일입니다. [XmlWriter](../) 은 지정된 경로에 파일을 만들고 XML 1.0 텍스트 구문으로 씁니다. **outputFileName** 은 파일 시스템 경로여야 합니다. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | [XmlWriterSettings](../../xmlwritersettings/) 객체는 새로운 [XmlWriter](../) 인스턴스를 구성하는 데 사용됩니다. 이것이 **nullptr** 인 경우, 기본 설정을 가진 [XmlWriterSettings](../../xmlwritersettings/) 가 사용됩니다. [XmlWriter](../) 가 XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) 메서드와 함께 사용되는 경우, 올바른 설정을 가진 [XmlWriterSettings](../../xmlwritersettings/) 객체를 얻기 위해 XslCompiledTransform::get_OutputSettings 값을 사용해야 합니다. 이는 생성된 [XmlWriter](../) 객체가 올바른 출력 설정을 갖도록 보장합니다. |

### 반환 값

[XmlWriter](../) 객체입니다.

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) 메서드


지정된 스트림을 사용하여 새로운 [XmlWriter](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 쓰기 원하는 스트림입니다. [XmlWriter](../) 은 XML 1.0 텍스트 구문을 작성하고 지정된 스트림에 추가합니다. |

### 반환 값

[XmlWriter](../) 객체입니다.

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) 메서드


스트림과 [XmlWriterSettings](../../xmlwritersettings/) 객체를 사용하여 새로운 [XmlWriter](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 쓰기 원하는 스트림입니다. [XmlWriter](../) 은 XML 1.0 텍스트 구문을 작성하고 지정된 스트림에 추가합니다. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | [XmlWriterSettings](../../xmlwritersettings/) 객체는 새로운 [XmlWriter](../) 인스턴스를 구성하는 데 사용됩니다. 이것이 **nullptr** 인 경우, 기본 설정을 가진 [XmlWriterSettings](../../xmlwritersettings/) 가 사용됩니다. [XmlWriter](../) 가 XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) 메서드와 함께 사용되는 경우, 올바른 설정을 가진 [XmlWriterSettings](../../xmlwritersettings/) 객체를 얻기 위해 XslCompiledTransform::get_OutputSettings 값을 사용해야 합니다. 이는 생성된 [XmlWriter](../) 객체가 올바른 출력 설정을 갖도록 보장합니다. |

### 반환 값

[XmlWriter](../) 객체입니다.

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) 메서드


지정된 TextWriter 를 사용하여 새로운 [XmlWriter](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 쓰기 원하는 TextWriter 입니다. [XmlWriter](../) 은 XML 1.0 텍스트 구문을 작성하고 지정된 TextWriter에 추가합니다. |

### 반환 값

[XmlWriter](../) 객체입니다.

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) 메서드


TextWriter와 [XmlWriterSettings](../../xmlwritersettings/) 객체를 사용하여 새로운 [XmlWriter](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 쓰기 원하는 TextWriter 입니다. [XmlWriter](../) 은 XML 1.0 텍스트 구문을 작성하고 지정된 TextWriter에 추가합니다. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | [XmlWriterSettings](../../xmlwritersettings/) 객체는 새로운 [XmlWriter](../) 인스턴스를 구성하는 데 사용됩니다. 이것이 **nullptr** 인 경우, 기본 설정을 가진 [XmlWriterSettings](../../xmlwritersettings/) 가 사용됩니다. [XmlWriter](../) 가 XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) 메서드와 함께 사용되는 경우, 올바른 설정을 가진 [XmlWriterSettings](../../xmlwritersettings/) 객체를 얻기 위해 XslCompiledTransform::get_OutputSettings 값을 사용해야 합니다. 이는 생성된 [XmlWriter](../) 객체가 올바른 출력 설정을 갖도록 보장합니다. |

### 반환 값

[XmlWriter](../) 객체입니다.

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) 메서드


지정된 [Text::StringBuilder](../../../system.text/stringbuilder/) 를 사용하여 새로운 [XmlWriter](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | 쓰기 대상 [Text::StringBuilder](../../../system.text/stringbuilder/) 입니다. [XmlWriter](../) 가 기록한 내용이 [Text::StringBuilder](../../../system.text/stringbuilder/) 에 추가됩니다. |

### 반환 값

[XmlWriter](../) 객체입니다.

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) 메서드


[Text::StringBuilder](../../../system.text/stringbuilder/) 와 [XmlWriterSettings](../../xmlwritersettings/) 객체를 사용하여 새로운 [XmlWriter](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | 쓰기 대상 [Text::StringBuilder](../../../system.text/stringbuilder/) 입니다. [XmlWriter](../) 가 기록한 내용이 [Text::StringBuilder](../../../system.text/stringbuilder/) 에 추가됩니다. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | [XmlWriterSettings](../../xmlwritersettings/) 객체는 새로운 [XmlWriter](../) 인스턴스를 구성하는 데 사용됩니다. 이것이 **nullptr** 인 경우, 기본 설정을 가진 [XmlWriterSettings](../../xmlwritersettings/) 가 사용됩니다. [XmlWriter](../) 가 XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) 메서드와 함께 사용되는 경우, 올바른 설정을 가진 [XmlWriterSettings](../../xmlwritersettings/) 객체를 얻기 위해 XslCompiledTransform::get_OutputSettings 값을 사용해야 합니다. 이는 생성된 [XmlWriter](../) 객체가 올바른 출력 설정을 갖도록 보장합니다. |

### 반환 값

[XmlWriter](../) 객체입니다.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) 메서드


지정된 [XmlWriter](../) 객체를 사용하여 새로운 [XmlWriter](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | 기본 작가로 사용할 [XmlWriter](../) 객체입니다. |

### 반환 값

[XmlWriter](../) 객체는 지정된 [XmlWriter](../) 객체를 감싸는 객체입니다.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) 메서드


지정된 [XmlWriter](../) 와 [XmlWriterSettings](../../xmlwritersettings/) 객체를 사용하여 새로운 [XmlWriter](../) 인스턴스를 생성합니다.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | 기본 작가로 사용할 [XmlWriter](../) 객체입니다. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | [XmlWriterSettings](../../xmlwritersettings/) 객체는 새로운 [XmlWriter](../) 인스턴스를 구성하는 데 사용됩니다. 이것이 **nullptr** 인 경우, 기본 설정을 가진 [XmlWriterSettings](../../xmlwritersettings/) 가 사용됩니다. [XmlWriter](../) 가 XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) 메서드와 함께 사용되는 경우, 올바른 설정을 가진 [XmlWriterSettings](../../xmlwritersettings/) 객체를 얻기 위해 XslCompiledTransform::get_OutputSettings 값을 사용해야 합니다. 이는 생성된 [XmlWriter](../) 객체가 올바른 출력 설정을 갖도록 보장합니다. |

### 반환 값

[XmlWriter](../) 객체는 지정된 [XmlWriter](../) 객체를 감싸는 객체입니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlWriter](../)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlWriterSettings](../../xmlwritersettings/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [TextWriter](../../../system.io/textwriter/)
* 클래스 [StringBuilder](../../../system.text/stringbuilder/)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)