---
title: ValueAs()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 IXmlNamespaceResolver 객체를 사용하여 네임스페이스 접두사를 해결하고, 현재 노드의 값을 지정된 Type으로 반환합니다.
type: docs
weight: 378
url: /ko/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) 메서드

현재 노드의 값을 지정된 Type으로 반환합니다, 지정된 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체를 사용하여 네임스페이스 접두사를 해결합니다.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 현재 노드의 값을 반환할 Type. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 네임스페이스 접두사를 해결하는 데 사용되는 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체. |

### 반환값

요청된 Type으로 현재 노드의 값.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)