---
title: Load()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 URL에서 XML 문서를 로드합니다.
type: docs
weight: 508
url: /ko/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) 메서드

지정된 URL에서 XML 문서를 로드합니다.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [String](../../../system/string/) | 로드할 XML 문서를 포함하는 파일의 URL입니다. URL은 로컬 파일이거나 HTTP URL([Web](../../../system.web/) 주소)일 수 있습니다. |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) 메서드

지정된 스트림에서 XML 문서를 로드합니다.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 로드할 XML 문서를 포함하는 스트림입니다. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) 메서드

지정된 TextReader에서 XML 문서를 로드합니다.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | 문서에 XML 데이터를 공급하는 데 사용되는 TextReader입니다. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) 메서드

지정된 [XmlReader](../../xmlreader/)에서 XML 문서를 로드합니다.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | 로드할 XML 데이터를 문서에 공급하는 데 사용되는 [XmlReader](../../xmlreader/)입니다. |

## 참고

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlDocument](../)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [TextReader](../../../system.io/textreader/)
* 클래스 [XmlReader](../../xmlreader/)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)