---
title: ReadElementContentAs()
second_title: Aspose.Slides C++용 API 레퍼런스
description: 요청된 형식으로 요소 내용을 읽습니다.
type: docs
weight: 586
url: /ko/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) 메서드

요청된 형식으로 요소 내용을 읽습니다.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 반환될 값의 형식입니다. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) 객체로, 형식 변환과 관련된 네임스페이스 접두사를 해결하는 데 사용됩니다. |

### 반환값

요청된 형식 객체로 변환된 요소 내용입니다.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) 메서드

지정된 로컬 이름 및 네임스페이스 URI가 현재 요소와 일치하는지 확인한 다음, 요청된 형식으로 요소 내용을 읽습니다.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 반환될 값의 형식입니다. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) 객체로, 형식 변환과 관련된 네임스페이스 접두사를 해결하는 데 사용됩니다. |
| localName | [String](../../../system/string/) | 요소의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 요소의 네임스페이스 URI입니다. |

### 반환값

요청된 형식 객체로 변환된 요소 내용입니다.

## 또한 보기

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* 클래스 [XmlReader](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)