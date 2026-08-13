---
title: XmlTextWriter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 스트림 및 인코딩을 사용하여 XmlTextWriter 클래스의 인스턴스를 생성합니다.
type: docs
weight: 183
url: /ko/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor

지정된 스트림 및 인코딩을 사용하여 [XmlTextWriter](../) 클래스의 인스턴스를 생성합니다.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 작성하려는 스트림 |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 생성할 인코딩. 인코딩이 **nullptr**인 경우 스트림을 UTF-8로 쓰고 **ProcessingInstruction**에서 인코딩 속성을 생략합니다. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) constructor

지정된 파일을 사용하여 [XmlTextWriter](../) 클래스의 인스턴스를 생성합니다.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 작성할 파일 이름입니다. 파일이 존재하면 해당 파일을 잘라내고 새로운 내용으로 덮어씁니다. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 생성할 인코딩. 인코딩이 **nullptr**인 경우 파일을 UTF-8로 쓰고 **ProcessingInstruction**에서 인코딩 속성을 생략합니다. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) constructor

지정된 TextWriter를 사용하여 [XmlTextWriter](../) 클래스의 인스턴스를 생성합니다.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 작성할 TextWriter입니다. TextWriter가 이미 올바른 인코딩으로 설정되어 있다고 가정합니다. |

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [Encoding](../../../system.text/encoding/)
* 클래스 [XmlTextWriter](../)
* 클래스 [String](../../../system/string/)
* 클래스 [TextWriter](../../../system.io/textwriter/)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)