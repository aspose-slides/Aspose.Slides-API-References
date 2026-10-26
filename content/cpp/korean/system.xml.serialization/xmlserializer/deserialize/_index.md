---
title: Deserialize()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XML 문서를 객체로 역직렬화합니다.
type: docs
weight: 14
url: /ko/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) 메서드

XML 문서를 객체로 역직렬화합니다.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 문서를 읽어올 스트림. |

### 반환 값

[Object](../../../system/object/)은(는) 이전에 주어진 문서에 직렬화된 객체입니다.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) 메서드

XML 문서를 객체로 역직렬화합니다.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | 문서를 읽어올 리더. |

### 반환 값

[Object](../../../system/object/)은(는) 이전에 주어진 문서에 직렬화된 객체입니다.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) 메서드

XML 문서를 객체로 역직렬화합니다.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 문서를 읽어올 리더. |

### 반환 값

[Object](../../../system/object/)은(는) 이전에 주어진 문서에 직렬화된 객체입니다.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) 메서드

XML 문서를 객체로 역직렬화합니다.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 문서를 읽어올 리더. |
| encodingStyle | [String](../../../system/string/) | 객체를 직렬화하는 데 사용되는 스타일. |

### 반환 값

[Object](../../../system/object/)은(는) 이전에 주어진 문서에 직렬화된 객체입니다.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [XmlSerializer](../)
* 클래스 [TextReader](../../../system.io/textreader/)
* 클래스 [XmlReader](../../../system.xml/xmlreader/)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml::Serialization](../../)
* 라이브러리 [Aspose.Slides](../../../)