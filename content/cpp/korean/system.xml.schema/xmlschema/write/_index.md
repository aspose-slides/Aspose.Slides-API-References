---
title: Write()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 제공된 데이터 스트림에 XML 스키마를 씁니다.
type: docs
weight: 339
url: /ko/system.xml.schema/xmlschema/write/
---
## XmlSchema::Write(const SharedPtr\<IO::Stream\>\&) 메서드

제공된 데이터 스트림에 XML [Schema](../../)을 씁니다.

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<IO::Stream> &stream)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 제공된 데이터 스트림. |

## XmlSchema::Write(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNamespaceManager\>\&) 메서드

지정된 [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)를 사용하여 제공된 스트림에 XML [Schema](../../)을 씁니다.

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<IO::Stream> &stream, const SharedPtr<XmlNamespaceManager> &namespaceManager)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 제공된 데이터 스트림. |
| namespaceManager | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/). |

## XmlSchema::Write(const SharedPtr\<IO::TextWriter\>\&) 메서드

제공된 [IO::TextWriter](../../../system.io/textwriter/)에 XML [Schema](../../)을 씁니다.

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<IO::TextWriter> &writer)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| writer | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 쓰기 대상인 [IO::TextWriter](../../../system.io/textwriter/). |

## XmlSchema::Write(const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) 메서드

제공된 TextWriter에 XML [Schema](../../)을 씁니다.

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<IO::TextWriter> &writer, const SharedPtr<XmlNamespaceManager> &namespaceManager)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| writer | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 쓰기 대상인 [IO::TextWriter](../../../system.io/textwriter/). |
| namespaceManager | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/). |

## XmlSchema::Write(const SharedPtr\<XmlWriter\>\&) 메서드

제공된 [XmlWriter](../../../system.xml/xmlwriter/)에 XML [Schema](../../)을 씁니다.

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<XmlWriter> &writer)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| writer | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 쓰기 대상인 [XmlWriter](../../../system.xml/xmlwriter/). |

## XmlSchema::Write(const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) 메서드

제공된 [XmlWriter](../../../system.xml/xmlwriter/)에 XML [Schema](../../)을 씁니다.

```cpp
void System::Xml::Schema::XmlSchema::Write(const SharedPtr<XmlWriter> &writer, const SharedPtr<XmlNamespaceManager> &namespaceManager)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| writer | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 쓰기 대상인 [XmlWriter](../../../system.xml/xmlwriter/). |
| namespaceManager | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/). |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [XmlSchema](../)
* 클래스 [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* 클래스 [TextWriter](../../../system.io/textwriter/)
* 클래스 [XmlWriter](../../../system.xml/xmlwriter/)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)