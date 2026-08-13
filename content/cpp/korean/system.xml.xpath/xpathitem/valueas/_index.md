---
title: ValueAs()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 유형으로 항목의 값을 반환합니다.
type: docs
weight: 131
url: /ko/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) 메서드

지정된 유형으로 항목의 값을 반환합니다.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 항목 값을 반환할 유형. |

### 반환 값

요청된 유형으로 항목의 값.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) 메서드

파생 클래스에서 재정의될 경우, 네임스페이스 접두사를 해석하기 위해 지정된 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체를 사용하여 지정된 유형으로 항목의 값을 반환합니다.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 항목 값을 반환할 유형. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 네임스페이스 접두사를 해석하는 데 사용되는 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체. |

### 반환 값

요청된 유형으로 항목의 값.

## 참조

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [XPathItem](../)
* 클래스 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)