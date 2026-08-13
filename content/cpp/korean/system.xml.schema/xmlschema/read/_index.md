---
title: Read()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "제공된 IO::TextReader에서 XML 스키마를 읽습니다."
type: docs
weight: 365
url: /ko/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) 메서드

제공된 [IO::TextReader](../../../system.io/textreader/)에서 XML [Schema](../../)을 읽습니다.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 읽을 XML [Schema](../../)를 포함하는 [IO::TextReader](../../../system.io/textreader/). |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../) 구문 오류에 대한 정보를 받는 검증 이벤트 핸들러. |

### 반환값

XML [Schema](../../)을 나타내는 [XmlSchema](../) 객체.

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) 메서드

제공된 스트림에서 XML [Schema](../../)을 읽습니다.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 제공된 데이터 스트림. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../) 구문 오류에 대한 정보를 받는 검증 이벤트 핸들러. |

### 반환값

XML [Schema](../../)을 나타내는 [XmlSchema](../) 객체.

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) 메서드

제공된 [XmlReader](../../../system.xml/xmlreader/)에서 XML [Schema](../../)을 읽습니다.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 읽을 XML [Schema](../../)를 포함하는 [XmlReader](../../../system.xml/xmlreader/). |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../) 구문 오류에 대한 정보를 받는 검증 이벤트 핸들러. |

### 반환값

XML [Schema](../../)을 나타내는 [XmlSchema](../) 객체.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)