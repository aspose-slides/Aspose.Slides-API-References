---
title: ReadContentAs()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 타입의 객체로 내용을 읽습니다.
type: docs
weight: 456
url: /ko/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) 메서드

지정된 타입의 객체로 내용을 읽습니다.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 반환될 값의 형식. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) 객체로, 형식 변환과 관련된 네임스페이스 접두사를 해결하는 데 사용됩니다. 예를 들어, [XmlQualifiedName](../../xmlqualifiedname/) 객체를 **xs:string**으로 변환할 때 사용할 수 있습니다. 이 값은 **nullptr**일 수 있습니다. |

### 반환값

요청된 타입으로 변환된 결합된 텍스트 콘텐츠 또는 속성 값.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)