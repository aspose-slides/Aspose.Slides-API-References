---
title: ValueAs()
second_title: Aspose.Slides for C++ API 레퍼런스
description: IXmlNamespaceResolver 객체를 사용하여 네임스페이스 접두사를 해석하도록 지정된 타입으로 검증된 XML 요소 또는 속성의 값을 반환합니다.
type: docs
weight: 144
url: /ko/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) 메서드

검증된 XML 요소 또는 속성의 값을 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체를 사용하여 네임스페이스 접두사를 해석하도록 지정된 타입으로 반환합니다.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 검증된 XML 요소 또는 속성의 값을 반환할 타입. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 네임스페이스 접두사를 해석하는 데 사용되는 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체. |

### 반환 값

요청된 타입으로 변환된 검증된 XML 요소 또는 속성의 값.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 클래스 [XmlAtomicValue](../)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)