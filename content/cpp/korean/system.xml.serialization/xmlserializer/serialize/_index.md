---
title: Serialize()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문서를 XML로 직렬화합니다.
type: docs
weight: 27
url: /ko/system.xml.serialization/xmlserializer/serialize/
---
## XmlSerializer::Serialize(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>) method

문서를 XML로 직렬화합니다.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::Stream> stream, System::SharedPtr<Object> o)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 대상 스트림. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/)를 직렬화합니다. |

## XmlSerializer::Serialize(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>) method

문서를 XML로 직렬화합니다.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::TextWriter> textWriter, System::SharedPtr<Object> o)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| textWriter | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | 대상 스트림. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/)를 직렬화합니다. |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>) method

문서를 XML로 직렬화합니다.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | 대상 스트림. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/)를 직렬화합니다. |

## XmlSerializer::Serialize(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) method

문서를 XML로 직렬화합니다.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::Stream> stream, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 대상 스트림. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/)를 직렬화합니다. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | 네임스페이스 저장소. |

## XmlSerializer::Serialize(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) method

문서를 XML로 직렬화합니다.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<IO::TextWriter> textWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| textWriter | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | 대상 스트림. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/)를 직렬화합니다. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | 네임스페이스 저장소. |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) method

문서를 XML로 직렬화합니다.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | 대상 스트림. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/)를 직렬화합니다. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | 네임스페이스 저장소. |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String) method

문서를 XML로 직렬화합니다.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces, String encodingStyle)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | 대상 스트림. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/)를 직렬화합니다. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | 네임스페이스 저장소. |
| encodingStyle | [String](../../../system/string/) | 직렬화 중에 사용할 스타일. |

## XmlSerializer::Serialize(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String, String) method

문서를 XML로 직렬화합니다.

```cpp
void System::Xml::Serialization::XmlSerializer::Serialize(System::SharedPtr<XmlWriter> xmlWriter, System::SharedPtr<Object> o, System::SharedPtr<XmlSerializerNamespaces> namespaces, String encodingStyle, String id)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlWriter | [System::SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\> | 대상 스트림. |
| o | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/)를 직렬화합니다. |
| namespaces | [System::SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../../xmlserializernamespaces/)\> | 네임스페이스 저장소. |
| encodingStyle | [String](../../../system/string/) | 직렬화 중에 사용할 스타일. |
| id | [String](../../../system/string/) | [Object](../../../system/object/)를 직렬화 중에 사용할 ID. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [Object](../../../system/object/)
* 클래스 [XmlSerializer](../)
* 클래스 [TextWriter](../../../system.io/textwriter/)
* 클래스 [XmlWriter](../../../system.xml/xmlwriter/)
* 클래스 [XmlSerializerNamespaces](../../xmlserializernamespaces/)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml::Serialization](../../)
* Library [Aspose.Slides](../../../)